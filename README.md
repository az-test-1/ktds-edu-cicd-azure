# [KTDS교육자료] Azure 기반 CICD 활용 실무


본 교육은 Azure 기반 환경에서 CI방법과 GitOps 방식의 Deploy를 학습하며  AKS, Github Action, ArgoCD를 활용하여 실습한다.

문의: 송양종( yj.song@kt.com / ssongmantop@gmail.com )



# 교육목표

* Azure 환경에서 소스코드 형상관리 및 Build, Deploy를 이해할 수 있다.
* Pipeline 수행에 필요한 Runner(Self-hosted Agent 등)의 구축 및 구동방식을 이해할 수 있다.
* GitOps 기반의 배포와 ArgoCD 구축 및 작동 방식을 이해할 수 있다.
* Github Action을 활용한 Pipeline을 구축할 수 있다.




# 시작전에 ([바로가기](./05.beforebegin/beforebegin.md))

- mobaXterm 설치, gitbash 설치, typora 설치

- 교육자료 download 및 Typora 로 readme.md 파일오픈

- 개인 VM 서버 주소 확인 및  SSH (Mobaxterm) 실행

- Sample Source Fork 및 Clone

- 소스내 eduUserID 일괄 수정



# CICD 기본 ([바로가기](./10.CICD_Basic/10.CICD_Basic.md))

* CICD 기본정보 학습
* 배포구조 이해를 위한 CI/CD Flow
* Branch 전략, Application Versioning, Container Image Tagging



# Container 기본 ([바로가기](./20.ContainerBasic/05.AzureAKS설정.md))

* Azure 및 AKS 설정
  * Azure Portal Login, AKS 설정, Sample App 배포

* ACR 인증처 분석(Azure Service Principal, Azure AD, ACR Token, ACR Admin 계정)
  * Container login, pull/push test

* AKS ACR 연결 방법 분석
* Dockerizing(docker build, docker buildx), Cache, 소요시간 테스트
* Kustomize 이해, Overlay 구조 이해



# Github Action ([바로가기](./30.GithubAction/10.GithubAction구조.md))

* Github Action 구조 및 동작 흐름 이해
* Github Action 수행을 위한 Github 환경 설정
* Workflow 이해를 위한 단계별 수행
* Github-hosted runner, Self-hosted runner 이해
* Self-hosted runner 구축 (VM기반, AKS기반(ARC)) 
* Self-hosted Agent 설정[실습]
* CI Pipeline 설정 및 수행[실습]



# ArgoCD ([바로가기](./40.ArgoCD/10.GitOps와ArgoCD.md))

* GitOps 이해와 ArgoCD의 관계 이해
* ArgoCD 구축 및 기본 설정, RBAC 관리
* ArgoCD App생성



# VM 기반 CICD ([바로가기](./50.VMBasedCICD/10.VMBasedCICD.md))

* VM 기반 CICD 아키텍처
* Sample Workflow
