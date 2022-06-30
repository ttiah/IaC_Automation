# Ansible

## 1. Ansible 개요

### 1.1 용어

#### 1.1.1 제어노드(Control Node)
#### 1.1.2 관리노드(Managed Node)
#### 1.1.3 플러그인(Plugin)
#### 1.1.4 모듈(Module)
#### 1.1.5 작업(Task)
#### 1.1.6 Ad-hoc 명령
#### 1.1.7 플레이(Play)
#### 1.1.8 플레이북(Playbook)
#### 1.1.9 역할(Role)
#### 1.1.10 컬렉션(Collection)

### 1.2 Ansible 설치

#### 1.2.1 관리노드 요구사항

- SSH 통신이 가능해야 함
- SFTP를 사용할 수 있어야 함
- SFTP를 사용할 수 없는 경우 SCP 사용 가능
- Python2(2.7 이상) 및 Python3(3.5 이상) 설치

#### 1.2.2 Ansible 설치

```bash
$ sudo apt update
$ sudo apt install -y software-properties-common
$ sudo apt-add-repository -y -u ppa:ansible/ansible
$ sudo apt install -y ansible
```

#### 1.2.3 Ansible 명령 쉘 자동완성

```bash
$ sudo apt install -y python3-argcomplete
$ sudo activate-global-python-argcomplete3
```

#### 1.2.4 Ansible Lint 설치

```bash
$ sudo apt install -y ansible-lint
$ exec bash
```
