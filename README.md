# 👋 Hi, I'm Jeonghun Park

### Infrastructure / System Engineer

Linux 기반 서버와 네트워크 인프라를 공부하고 있습니다.

가상화 환경에서 서버와 네트워크를 직접 구축하고,  
서비스 간 연동 과정에서 발생하는 문제의 원인을 분석하고 해결하는 과정에 관심이 있습니다.

<br>

## 🙋 About Me

- 🐧 Linux 기반 서버 구축 및 운영 실습
- 🌐 Network Infrastructure 구성 및 Troubleshooting
- 🖥️ VMware 기반 가상화 인프라 구축
- 🐳 Docker 기반 서비스 구성
- 🔀 Load Balancing / Reverse Proxy 구성
- 🗄️ Database 구축 및 접근 제어
- 🔧 장애 원인 분석 및 서비스 연동 점검
- ☁️ Cloud Infrastructure 학습 중

<br>

## 🛠 Tech Stack

### 🖥 Infrastructure

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Rocky Linux](https://img.shields.io/badge/Rocky%20Linux-10B981?style=flat-square&logo=rockylinux&logoColor=white)
![VMware](https://img.shields.io/badge/VMware-607078?style=flat-square&logo=vmware&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

### 🌐 Network

![Cisco](https://img.shields.io/badge/Network-1BA0D7?style=flat-square&logo=cisco&logoColor=white)
![VyOS](https://img.shields.io/badge/VyOS-0066CC?style=flat-square&logoColor=white)

`TCP/IP` `VLAN` `OSPF` `NAT` `ACL` `Routing` `DNS` `DHCP`

### 🌍 Web / Server

![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Apache](https://img.shields.io/badge/Apache-D22128?style=flat-square&logo=apache&logoColor=white)
![HAProxy](https://img.shields.io/badge/HAProxy-106DA9?style=flat-square&logo=haproxy&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

`BIND` `Postfix` `Dovecot` `NFS` `FTP`

### 🗄 Database

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white)

### 💻 Development

![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)

### 🔧 Tools

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ%20IDEA-000000?style=flat-square&logo=intellijidea&logoColor=white)

<br>

# 🚀 Projects

## 🌱 Jigubium Infrastructure Project

### VMware 기반 사내 서비스 인프라 구축

본사와 지사를 가정하여  
네트워크, 서버, 데이터베이스 및 컨테이너 환경을 구축한 팀 프로젝트입니다.

### 주요 구성

- VMware 기반 가상 네트워크 구성
- VyOS Routing / NAT 구성
- Web / DB / DNS / DHCP Server 구축
- FTP / NFS / Mail Server 구축
- DB 전용 네트워크 구성
- Docker 기반 Web Application 구성
- HAProxy Round Robin Load Balancing
- Redis 기반 Session Sharing
- Nginx HTTPS Reverse Proxy
- MySQL Database 구축 및 접근 제어
- 서비스 장애 및 네트워크 연결 문제 Troubleshooting

### Architecture

```text
Client
  │
  ▼
VyOS
  │
  ├── Web / DNS / Mail / NFS / FTP
  │
  └── DB Network
          │
          └── MySQL
