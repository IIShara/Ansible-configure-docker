# Ansible-configure-docker

## Запуск
ansible-playbook -i hosts playbook.yml -K

## Поддерживаемые дистрибутивы Linux
* CentOS

## Описание ролей
* **role/docker_install** - Установка docker из официального репозитория
* **role/docker_compose_install** - Установка docker_compose
* **role/docker_deploy** - Запуск docker compose
* **role/gitlab_runner_install** - Установка gitlab_runner

## Результат:
**1. Сервер Gitlab** 
* **URL:** http://gitlab.local 
* **Login:** root
* **Password:** P@ssw0rd

**2. Сервер Grafana** 
* **URL:** http://grafana.local
* **Login:** admin
* **Password:** admin

**3. Сервер Nginx**
