# Commit Message Convention

## 제목 형식

```
[<type>] <subject>
```

- `type`: 변경의 종류 (아래 목록 참고)
- `subject`: 변경 내용을 간결하게 (명령형, 현재 시제, 50자 이내)

## Type 목록

| Type | 설명 |
|------|------|
| `feat` | 새로운 기능 추가 |
| `fix` | 버그 수정 |
| `docs` | 문서 수정 |
| `style` | 코드 포맷 등 기능 변경 없는 수정 |
| `refactor` | 리팩토링 |
| `chore` | 빌드, 설정 등 기타 변경 |

## 예시

```
[feat] 로그인 기능 추가
[fix] 비밀번호 유효성 검사 오류 수정
[docs] README 작성
[chore] .gitignore 추가
```

## 본문 (선택)

제목 아래 빈 줄을 두고 작성. 변경 이유나 상세 내용을 서술.
