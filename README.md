Репозиторий содержит файлы для модификации docker образа Wso2 Identity Server

Работа файлов темы и локализации проверена на версии docker образа [wso2/wso2is v5.11.0](https://hub.docker.com/layers/wso2/wso2is/5.11.0/images/sha256-d58d6dc1cda8d93667af3ee2a7c9c81ab1208f8c7529133b54b353f280497ec2?context=explore).

Клонируем файлы темы из репозитория

```git clone https://github.com/19Crimson/wso2-theme.git```

Копируем файлы темы в контейнер

```docker cp {REPO_PATH}/wso2-theme/authenticationendpoint {C_NAME}:home/wso2carbon/wso2is-5.11.0/repository/deployment/server/webapps/```

REPO_PATH - путь до папки с репозиторием wso2-theme

C_NAME - имя контейнера
