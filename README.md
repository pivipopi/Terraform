# Terraform

- https://app.terraform.io/ 에서 깃허브를 이용하여 인스턴스 배포

# 테라폼 클라우드에 깃허브로 작업한 내용 올리기

- Workspaces > Create a new Workspace > Version control workflow
- 깃허브를 눌러 인증이 안되어 있다면 깃허브 인증을 하고 진행할 것
- 생성할 workspace를 선택한 뒤 생성을 누른다.

# 생성후 변수 설정

- Variables > Terraform Variables
  - 사용할 리전을 설정
  - 사용할 액세스 키와 시크릿 키를 설정해준다.

# 배포
- Runs > Actions
  - 실행하는 사유를 적은 뒤 시작을 누른다.
  - plan이 끝나면 Confirm & Apply를 물어보는데, 맞다면 okay를 눌러 배포를 한다.

# 디렉토리 구조
```
.
├── data_source.tf
├── local.tf
├── main.tf
├── my_sshkey
├── output.tf
├── providr.tf
├── security-group.tf
└── variable.tf
```
