# Kubernetes for the Absolute Beginners

Udemy 강의 [Learn Kubernetes](https://www.udemy.com/course/learn-kubernetes)를 들으며 정리하는 학습 노트입니다.
강의 내용을 바탕으로 직접 실습하고, 막혔던 부분과 해결 과정을 함께 기록합니다.

## 목차

### 01. Kubernetes Overview

| 문서 | 내용 |
|------|------|
| [Containers Overview](./01.Kubernetes%20Overview/01.Containers%20Overview.md) | Docker의 목적, 컨테이너와 가상 머신 비교 |
| [Kubernetes Overview](./01.Kubernetes%20Overview/02.Kubernetes%20Overview.md) | 노드, 클러스터, 마스터, 구성요소, kubectl |
| [Docker vs containerd](./01.Kubernetes%20Overview/03.Docker%20vs%20ContainerD.md) | CRI/OCI, dockershim 제거 배경, containerd CLI |

### 02. Kubernetes Concepts

| 문서 | 내용 |
|------|------|
| [Minikube Practice](./02.Kubernetes%20Concepts/01.Minikube%20Practice.md) | minikube 설치, 샘플 앱 배포, arm64 트러블슈팅 |
| [Pod](./02.Kubernetes%20Concepts/02.Pod.md) | Pod 개념, 스케일링, 멀티 컨테이너 Pod |

## 실습 환경

- Apple Silicon (arm64), macOS
- Docker Desktop + minikube (Docker 드라이버)
- kubectl

## 진행 상황

- [x] 01. Kubernetes Overview
- [ ] 02. Kubernetes Concepts (진행 중)
