# AWS-Cloud-Security-Project
## Git Convention

### Branch
- `main`: 완료된 작업
- `feat/*`: 새로운 실습 및 구성
- `fix/*`: 오류 수정
- `docs/*`: 문서 작성 및 수정

### Commit
`<type>: <message>`

- `feat`: 새로운 실습 및 구성 추가
- `fix`: 오류 수정
- `docs`: 문서 및 결과 정리
- `refactor`: 기존 구성 개선
- `chore`: 기타 설정 및 관리

### Rules
- `main` 브랜치에 직접 push하지 않고 PR을 통해 병합
- 커밋은 작업 단위로 작성
- AWS Key, `.env`, 인증서 Private Key 등 민감정보 커밋 금지
- Terraform State 등 민감정보가 포함될 수 있는 파일은 `.gitignore`로 관리
