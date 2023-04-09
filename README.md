# Что такое DevOps. СI/СD - Borobov Ivan
---
### Задание 1
#### Что нужно сделать:
1. `Установите себе jenkins по инструкции из лекции или любым другим способом из официальной документации. Использовать Docker в этом задании нежелательно. `
2. `Установите на машину с jenkins golang.`
3. `Используя свой аккаунт на GitHub, сделайте себе форк репозитория. В этом же репозитории находится дополнительный материал для выполнения ДЗ. `
4. `Создайте в jenkins Freestyle Project, подключите получившийся репозиторий к нему и произведите запуск тестов и сборку проекта go test . и docker build ..`  
`В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.`
#### Ответ:
1. ![install jenkins](https://github.com/Borobov/gitlab-hw3/blob/37e6e6c83fafb14de90938b8177764449e7c0b3b/img/jankins.png)
2. ![install go](https://github.com/Borobov/gitlab-hw3/blob/37e6e6c83fafb14de90938b8177764449e7c0b3b/img/go.png)
3. ![jankins setting 1](https://github.com/Borobov/gitlab-hw3/blob/ec9b55f721a32a6c20f3cccfb5fb45ab20ce68aa/img/jenkins-setting-1.png)
4. ![jankins setting 2](https://github.com/Borobov/gitlab-hw3/blob/ec9b55f721a32a6c20f3cccfb5fb45ab20ce68aa/img/jenkins-setting-2.png)
5. ![result 1](https://github.com/Borobov/gitlab-hw3/blob/ec9b55f721a32a6c20f3cccfb5fb45ab20ce68aa/img/jankins-result-1.png)
6. ![result 2](https://github.com/Borobov/gitlab-hw3/blob/ec9b55f721a32a6c20f3cccfb5fb45ab20ce68aa/img/jankins-result-2.png)

---

### Задение 2
#### Что нужно сделать:
1. `Создайте новый проект pipeline.`
2. `Перепишите сборку из задания 1 на declarative в виде кода.`
`В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.`
#### Ответ:

---

### Задение 3
#### Что нужно сделать:
1. Установите на машину Nexus.
2. Создайте raw-hosted репозиторий.
3. Измените pipeline так, чтобы вместо Docker-образа собирался бинарный go-файл. Команду можно скопировать из Dockerfile.
4. Загрузите файл в репозиторий с помощью jenkins.  

В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.
#### Ответ:
1. ![install nexus](https://github.com/Borobov/gitlab-hw3/blob/e99653e4e8e54df152c4aa5fa1c2d8f36004d561/img/Nexus.png)
2. ![nexus repo](https://github.com/Borobov/gitlab-hw3/blob/28edf7842fca3527249e0f4014d59596940dfffb/img/3-nexus-repo.png)
3. ![jenkins setting repo](https://github.com/Borobov/gitlab-hw3/blob/28edf7842fca3527249e0f4014d59596940dfffb/img/3-jenkins-setting-nexus.png)
4. ![nexus result repo](https://github.com/Borobov/gitlab-hw3/blob/28edf7842fca3527249e0f4014d59596940dfffb/img/3-nexus-repo-2.png)
