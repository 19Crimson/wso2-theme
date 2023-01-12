Репозиторий содержит файлы для модификации docker образа Wso2 Identity Server

Клонируем файлы темы из репозитория

```git clone https://github.com/19Crimson/wso2-theme.git```

Копируем файлы темы в контейнер

```docker cp {REPO_PATH}/wso2-theme/authenticationendpoint {C_NAME}:home/wso2carbon/wso2is-5.11.0/repository/deployment/server/webapps/```

REPO_PATH - путь до папки с репозиторием wso2-theme

C_NAME - имя контейнера
