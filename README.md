# Docker-Web-Stacks
Конфигурации Docker Compose и настройки веб-серверов для различных CMS и фреймворков

# Описание инфраструктурных проектов

В данном репозитории собраны готовые конфигурационные файлы для развертывания веб-стеков и систем мониторинга в контейнерах Docker.

## Реализованные связки и стек:
* **WordPress:** Docker Compose + Nginx + MariaDB
* **Joomla:** Docker Compose + Nginx + MariaDB
* **Laravel:** Docker Compose + Apache + PostgreSQL
* **Zabbix:** Docker Compose + Nginx + MariaDB (система мониторинга)

## Что настроено внутри проектов:
1. Изоляция сервисов внутри локальных сетей Docker (networks).
2. Постоянное хранение данных баз данных и конфигураций через Docker Volumes.
3. Базовая настройка Nginx в качестве Reverse Proxy.
