# Backend в production
В данном репозитории я буду собирать и описывать тот инструментарий, который мы используем в повседневной работе.
Список содержит как инструменты, так и библиотеки.
Используемые моей командой языки: Golang, PHP.

## DevOps
Wiki:
DevOps (акроним от англ. development и operations) — методология активного взаимодействия специалистов по разработке со специалистами по информационно-технологическому обслуживанию и взаимная интеграция их рабочих процессов друг в друга для обеспечения качества продукта. Предназначена для эффективной организации создания и обновления программных продуктов и услуг. Основана на идее тесной взаимозависимости создания продукта и эксплуатации программного обеспечения, которая прививается команде как культура создания продукта. 

### DevOps подразумевает ряд слоев:

#### Кодирование — разработка и анализ кода, инструменты контроля версий, слияние кода;
* Инструменты:
* IDE
* Lint
* Git

#### Сборка — инструменты непрерывной интеграции, статус сборки;
Инструменты:
* Gitlab
* Jenkins
* TeamCity

#### Тестирование — инструменты непрерывного тестирования, обеспечивающие быструю и своевременную оценку бизнес-рисков;
Инструменты:
* Lint
* Unit
* SonarQube
* Sonarcloud
* др тесты

#### Упаковка — репозиторий артефактов, предварительная установка приложения;
Инструменты:
* Gitlab
* Jenkins
* TeamCity

#### Релиз — управление изменениями, официальное утверждение выпуска, автоматизация выпуска;
Инструменты:

#### Настройка — конфигурация и управление инфраструктурой, Инфраструктура как инструменты кода;
Инструменты:
* Ansible
* Terraform
* Helm
* K8s
* Chef
* Puppet 
* SaltStack
* Docker

#### Мониторинг — измерение производительности приложений, взаимодействие с конечным пользователем;
Инструменты:
* NewRelic
* DataDog
* APM
* Prometheus + grafana
* ELK
* Zabix

#### Уведомления - уведомления об прохождении слоев, уведомления об ошибках выполнения приложения, ошибках инфраструктуры.
Инструменты:
* Slack
* PagerDuty
* Sentry

#### Непрерывная поставка
Инструменты:
* Gitlab
* Jenkins
* TeamCity

#### Непрерывная интеграция
Инструменты:
* Gitlab CI
* AWS CodePipeline 
* CircleCI
* Jenkins
* TeamCity
* Azure Pipelines

### Clouds
* AWS
* GSP
* Azure

### Code quality
* Lint
* SonarQube
* Sonarcloud
* тесты

### Golang

### PHP

### Как частные случаи методологии DevOps существуют:
#### GitOps
* Werf

#### CiOps
* Gitlab CI
* AWS CodePipeline 
* CircleCI
* Jenkins
* TeamCity
* Azure Pipelines

#### ChatOps
* Slack
* Telegram

#### TestOps


Пришел к выводу, что такие подходы как DevOps, GitOps, CiOps, ChatOps, TestOps сильно улучшают качество кода.
