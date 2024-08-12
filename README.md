# Terraform으로 AKS에 Apache Airflow 배포 및 Git으로 DAG 관리

이 리포지토리는 [Terraform을 사용하여 AKS에 Airflow 배포하기](https://statisticsfox.github.io/Data%20Engineering/Terraform%EC%9C%BC%EB%A1%9C%20AKS%EC%97%90%20airflow%20%EB%9D%84%EC%9A%B0%EA%B3%A0%20git%EC%9C%BC%EB%A1%9C%20DAG%20%EA%B4%80%EB%A6%AC%ED%95%98%EA%B8%B0/) 블로그 글(저자 본인)을 기반으로, Terraform과 Helm을 사용해 AKS에 Apache Airflow를 배포하고, Git을 통해 DAG를 관리하는 방법을 제공합니다.

## 주요 내용

- Terraform으로 AKS 인프라 구성
- Helm으로 Airflow 설치
- Git으로 DAG 관리 자동화

## 요구 사항

- Azure CLI
- Terraform CLI
- Helm CLI
- kubectl

## 사용 방법

1. 이 리포지토리를 클론합니다.
2. Terraform을 실행하여 AKS를 설정합니다.
3. Helm을 사용해 Airflow를 배포합니다.
4. Git을 통해 DAG 파일을 관리합니다.

자세한 내용은 [블로그 글](https://statisticsfox.github.io/Data%20Engineering/Terraform%EC%9C%BC%EB%A1%9C%20AKS%EC%97%90%20airflow%20%EB%9D%84%EC%9A%B0%EA%B3%A0%20git%EC%9C%BC%EB%A1%9C%20DAG%20%EA%B4%80%EB%A6%AC%ED%95%98%EA%B8%B0/)을 참고하세요.
