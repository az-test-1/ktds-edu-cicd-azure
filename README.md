# ktds-edu-cicd-azure
> [KTDS교육자료] Azure 기반 CICD 활용 실무



본 교육은 Azure기반 환경에서 CI방법과 GitOps 방식의 Deploy를 학습하며  Azure DevOps Pipeline, Github Action, ArgoCD를 활용하여 실습한다.

문의: 송양종( yj.song@kt.com / ssongmantop@gmail.com )



# 교육목표

* Azure 환경에서 소스코드 형상관리 및 Build, Deploy를 이해할 수 있다.
* Pipeline 수행에 필요한 Runner(Self-hosted Agent 등)의 구축 및 구동방식을 이해할 수 있다.
* GitOps 기반의 배포와 ArgoCD 구축 및 작동 방식을 이해할 수 있다.
* Github Action을 활용한 Pipeline 을 구축할 수 있다.




# 시작전에 ([바로가기](./beforebegin/beforebegin.md))

- mobaXterm 설치, gitbash 설치, typora 설치

- 교육자료 download 및 Typora 로 readme.md 파일오픈

- 개인 VM 서버 주소 확인 및  SSH (Mobaxterm) 실행



# CICD배포전략 ([바로가기](./textbook/K8sTrafficFlow.md))  

* 배포구조 및 전략의 이해
* Azure ACR 확인 및 Docker Pull/Push [실습]
* Sample Code 생성/빌드 및 k8s deploy[실습]



# Azure DevOps

* Repo, Pipeline 구조이해
* Self-hosted Agent 설정[실습]
* CI Pipeline 설정 및 수행[실습]



# Github Action

* Repo, Action 구조 이해
* Self-hosted Agent 설정[실습]
* CI Pipeline 설정 및 수행[실습]



# ArgoCD

* GitOps 이해와 ArgoCD의 관계 이해
* ArgoCD 구축 및 기본 설정[실습]
* RBAC 관리[실습]
* ArgoCD 중앙관리를 위한 전략[실습]

