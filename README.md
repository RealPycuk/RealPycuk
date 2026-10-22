<h1 align="center">Руслан Хуснутдинов</h1>
<p align="center"><b>Junior DevOps Engineer</b> · Санкт-Петербург</p>

<p align="center">
  <a href="https://t.me/rusyajez"><img src="https://img.shields.io/badge/Telegram-@rusyajez-26A5E4?logo=telegram&logoColor=white" alt="Telegram"></a>
  <a href="mailto:ruslaniusuper@gmail.com"><img src="https://img.shields.io/badge/Email-ruslaniusuper@gmail.com-EA4335?logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

### Обо мне

- 🎓 Студент 4 курса СПбГЭТУ «ЛЭТИ», ФКТИ, направление «Информационные системы и технологии»
- 🛠 С октября 2025 года поддерживаю собственную инфраструктуру из двух Linux-серверов: сервисы в Docker, Telegram-бот на Python, мониторинг на Prometheus и Grafana, ежедневные бэкапы PostgreSQL, автоматические обновления по cron, защита SSH, fail2ban, firewall
- 🎯 Ищу позицию Junior DevOps / Infrastructure Engineer
- 🌍 Английский B2

### Стек

**Инфраструктура**<br>
<img src="https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black" alt="Linux">
<img src="https://img.shields.io/badge/Ubuntu-E95420?logo=ubuntu&logoColor=white" alt="Ubuntu">
<img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white" alt="Docker">
<img src="https://img.shields.io/badge/Docker_Compose-2496ED?logo=docker&logoColor=white" alt="Docker Compose">
<img src="https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white" alt="Kubernetes">
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white" alt="GitHub Actions">
<img src="https://img.shields.io/badge/Prometheus-E6522C?logo=prometheus&logoColor=white" alt="Prometheus">
<img src="https://img.shields.io/badge/Grafana-F46800?logo=grafana&logoColor=white" alt="Grafana">
<img src="https://img.shields.io/badge/Ansible-EE0000?logo=ansible&logoColor=white" alt="Ansible">

**Языки и базы данных**<br>
<img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/Bash-4EAA25?logo=gnubash&logoColor=white" alt="Bash">
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white" alt="PostgreSQL">
<img src="https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white" alt="FastAPI">
<img src="https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white" alt="Git">

**Сейчас изучаю**<br>
<img src="https://img.shields.io/badge/Nginx-009639?logo=nginx&logoColor=white" alt="Nginx">

### Проекты

| Проект | Что сделано |
|---|---|
| [docker-deploy-rollback](https://github.com/RealPycuk/docker-deploy-rollback) | Деплой по git-тегу для Docker Compose: сборка образа на сервере, health check и автоматический откат, SSH-ключ с forced command. CI гоняет сквозной тест: рабочая, сломанная и снова рабочая версия. Разбор реального инцидента с проверкой здоровья |
| [monitoring-stack](https://github.com/RealPycuk/monitoring-stack) | Prometheus, Alertmanager, Grafana, node и blackbox exporter в Docker Compose: 10 алертов в Telegram с юнит-тестами promtool, дашборд из provisioning. CI поднимает весь стек и проверяет, что цели опрашиваются и правила загружены |
| [ansible-server-setup](https://github.com/RealPycuk/ansible-server-setup) | Плейбук из 6 ролей настраивает Ubuntu-сервер с нуля: SSH hardening, fail2ban, ufw, Docker, мониторинг по тегу. CI применяет его к чистой VM дважды и проверяет идемпотентность |
| [job-watch](https://github.com/RealPycuk/job-watch) | Telegram-бот поиска IT-вакансий под резюме: Хабр Карьера, Geekjob, «Работа России», Telegram-каналы; фильтр по роли, уровню, городу и зарплате; сопроводительные письма через GigaChat API. Многопользовательский по приглашениям, ключи шифруются, Docker, CI и 46 тестов, включая сквозной сценарий регистрации |
| [hello-world-minikube](https://github.com/RealPycuk/hello-world-minikube) | FastAPI в Kubernetes: Deployment на 2 реплики, Service, пробы, лимиты ресурсов, hardening контейнера. CI собирает образ и деплоит его в тестовый кластер kind |
