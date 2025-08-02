### EPILOG - 책 속 인물이 영상으로


<h1 align="center"> 
 EPI-LOG
  
</h1>


<h3 align="center"> 
 책 속의 인물을 주인공으로 캐스팅하여 영상으로 만들어주는 서비스
</h3>

<br/>


<img width="1920" height="1080" alt="제목을-입력해주세요_-005 (2)" src="https://github.com/user-attachments/assets/0a9e8db3-bb0f-40b2-b75f-b257efe19584" />
<br/>

---
## ✍️ 프로젝트 정보
- 프로젝트 개발 기간: 2025.6.30 ~ 2025.7.31

<!--  여기다가 간단한 프로젝트 설명-->

## ✍️ 프로젝트 소개

### 📝 Medium
https://medium.com/@dnjsgml0578/2025-summer-silicon-valley-bootcamp-epilog-3f3290fceeea



## 🎥 프로젝트 데모

1. 책 입력하기
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/bd1356ee-8ea8-4f57-aa70-bef44503dfb7" />


2. 캐릭터 분석하기
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/2b7d2bf9-6f6e-41d1-888f-4e5dd95a49c6" />


3. 대본 생성하기
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/6d392acd-b9f4-4769-a451-8f86a6abc530" />


4. 영상 생성 및 조회하기
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/5f6051f4-c907-44bf-a89a-e61ec7cf2a98" />




## ⚙️ System Architecture
<img width="1734" height="1034" alt="수정본7" src="https://github.com/user-attachments/assets/5d5aedfe-3eb8-45c6-b64b-cf475f597a84" />



## 📚 Tech Stack

| Position |  Stack |
|--------|---------|
| 🎨 **Frontend** | ![React](https://img.shields.io/badge/-React-61DAFB?logo=react&logoColor=white&style=flat) ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white&style=flat) ![Vite](https://img.shields.io/badge/-Vite-646CFF?logo=vite&logoColor=white&style=flat) ![Yarn](https://img.shields.io/badge/-Yarn-2C8EBB?logo=yarn&logoColor=white&style=flat) ![TailwindCSS](https://img.shields.io/badge/-TailwindCSS-06B6D4?logo=tailwindcss&logoColor=white&style=flat) ![ESLint](https://img.shields.io/badge/-ESLint-4B32C3?logo=eslint&logoColor=white&style=flat) ![Prettier](https://img.shields.io/badge/-Prettier-F7B93E?logo=prettier&logoColor=white&style=flat) ![Axios](https://img.shields.io/badge/-Axios-5A29E4?logo=axios&logoColor=white&style=flat) |
| 🛠 **Backend** | ![Django](https://img.shields.io/badge/-Django-092E20?logo=django&logoColor=white&style=flat) ![RabbitMQ](https://img.shields.io/badge/-RabbitMQ-FF6600?logo=rabbitmq&logoColor=white&style=flat) ![Celery](https://img.shields.io/badge/-Celery-37814A?logo=celery&logoColor=white&style=flat) ![DRF](https://img.shields.io/badge/-DRF-ff1709?logo=django&logoColor=white&style=flat) |
| 🗄 **Database** | ![MySQL](https://img.shields.io/badge/-MySQL-4479A1?logo=mysql&logoColor=white&style=flat) ![Redis](https://img.shields.io/badge/-Redis-DC382D?logo=redis&logoColor=white&style=flat) |
| 🤖 **AI** | ![Gemini](https://img.shields.io/badge/-Gemini-4285F4?logo=google&logoColor=white&style=flat) ![Veo](https://img.shields.io/badge/-Veo3-FFCD00?style=flat) |
| ⚙️ **DevOps** | ![Docker](https://img.shields.io/badge/-Docker-2496ED?logo=docker&logoColor=white&style=flat) ![GitHub Actions](https://img.shields.io/badge/-GitHub_Actions-2088FF?logo=githubactions&logoColor=white&style=flat) ![Vercel](https://img.shields.io/badge/-Vercel-000000?logo=vercel&logoColor=white&style=flat) ![Traefik](https://img.shields.io/badge/-Traefik-24A1C1?logo=traefikproxy&logoColor=white&style=flat) |
| 📊 **Monitoring** | ![Prometheus](https://img.shields.io/badge/-Prometheus-E6522C?logo=prometheus&logoColor=white&style=flat) ![Grafana](https://img.shields.io/badge/-Grafana-F46800?logo=grafana&logoColor=white&style=flat) ![cAdvisor](https://img.shields.io/badge/-cAdvisor-9ACD32?style=flat) |


## 🗺️ ERD
<img width="2650" height="1082" alt="2025-Team-E-Version4 (4)" src="https://github.com/user-attachments/assets/b7d0dac9-1f81-40da-a150-b9c989d68005" />



## 📄 API

## Monitoring
| 항목 | 설명 |
|------|------|
| 역할 | 메트릭 수집 및 시각화를 위한 데이터 소스 |
| 수집 대상 | Django, Celery, DB, cAdvisor 등 |
| 시각화 도구 | Grafana |

### 🧩 Django (애플리케이션 모니터링)
<img width="1400" height="529" alt="image" src="https://github.com/user-attachments/assets/e0316586-4bbe-429e-bf05-04c0cc7f167f" />


### 📄 Loki
| 항목 | 설명 |
|------|------|
| 역할 | 로그 수집 및 검색 시스템 |
| 수집 대상 | Django, Celery, Traefik 등 주요 서비스 |
| 시각화 도구 | Grafana Explore 탭에서 로그 검색 가능 |

<img width="1400" height="529" alt="image" src="https://github.com/user-attachments/assets/5f6e2ffc-1a45-4172-af35-4be0c65873a1" />


## 📌 Installation
### how to start?
```env
DJANGO_SECRET_KEY=

DEBUG=
DJANGO_ENV=

DB_NAME=
DB_ROOT_PASSWORD=
DB_HOST=
DB_PORT=

REDIS_HOST=
REDIS_PORT=

GOOGLE_CLOUD_PROJECT_ID=
GOOGLE_CLOUD_LOCATION=
GOOGLE_CLOUD_GCS_BUCKET=
GOOGLE_GENAI_USE_VERTEXAI=

GEMINI_API_KEY=

AWS_ACCESS_KEY_ID=
AWS_SECRET_ACCESS_KEY=
AWS_STORAGE_BUCKET_NAME=
AWS_S3_REGION_NAME=

ELEVENLABS_API_KEY=

DB_USER=
DB_PASSWORD=

GRAFANA_ADMIN_USER=
GRAFANA_ADMIN_PASSWORD=
GRAFANA_ROLE=

RABBITMQ_USER=
RABBITMQ_PASSWORD=
```

## 👪 Member
<table>
  <tr>
    <th>Name</th>
    <td>정원희</td>
    <td>현승곤</td>
    <td>조준민</td>
    <td>오건은</td>
    <td>김예진</td>
  </tr>
  <tr>
    <th>Position</th>
    <td>DevOps<br/>Leader<br/>Backend</td>
    <td>Backend<br/>Frontend</td>
    <td>Backend</td>
    <td>Frontend</td>
    <td>Frontend</td>
  </tr>
  <tr>
    <th>GitHub</th>
    <td><a href="https://github.com/daiseek"><img src="https://img.shields.io/badge/daiseek-181717?style=flat&logo=github&logoColor=white"/></a></td>
    <td><a href="https://github.com/invalidhuman"><img src="https://img.shields.io/badge/invalidhuman-181717?style=flat&logo=github&logoColor=white"/></a></td>
    <td><a href="https://github.com/coom1222"><img src="https://img.shields.io/badge/coom1222-181717?style=flat&logo=github&logoColor=white"/></a></td>
    <td><a href="https://github.com/siillvergun"><img src="https://img.shields.io/badge/siillvergun-181717?style=flat&logo=github&logoColor=white"/></a></td>
    <td><a href="https://github.com/KimYeJin1004"><img src="https://img.shields.io/badge/KimYeJin1004-181717?style=flat&logo=github&logoColor=white"/></a></td>
  </tr>
</table>
