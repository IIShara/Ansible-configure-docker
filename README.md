# Ansible-configure-docker

## Поддерживаемые дистрибутивы Linux
* CentOS

## Описание ролей
* **role/docker_install** - Установка docker из официального репозитория
* **role/docker_compose_install** - Установка docker_compose
* **role/docker_deploy** - Запуск docker compose
* **role/gitlab_runner_install** - Установка gitlab_runner

## Результат:
Сервер Gitlab доступный по адресу http://gitlab.local 
* **Login:** root
* **Password:** P@ssw0rd

Сервер Grafana доступный по адресу http://grafana.local
* **Login:** admin
* **Password:** admin
