# Фреймворк Spring (семинары)
## Урок 11. Spring Actuator. Настройка мониторинга с Prometheus и Grafana.

#### Домашнее задание

Задание:

Создайте новый микросервис на базе Spring Boot и включите в него зависимости Spring Actuator, `Prometheus` и `Grafana`.

Настройте Spring `Actuator` в вашем микросервисе для сбора следующих метрик: информации о состоянии приложения (
`/actuator/health`
), 

- Использования памяти (
`/actuator/metrics/jvm.memory.used`
), 

- Количества HTTP запросов (
`/actuator/metrics/http.server.requests`
), 

И любых других метрик по вашему выбору.

Создайте файл конфигурации `Prometheus` (
`prometheus.yml`
), в котором определите конфигурацию для сбора метрик из вашего микросервиса. Настройте интервал сбора и выберите метрики, которые вы хотите собирать.

### Архитектура проекта:

`MySpringActuatorProjectApplication.java:` Основной класс Spring Boot приложения, точка входа.

`MyController.java: `Класс контроллера для обработки HTTP-запросов.

`application.properties:` Файл настроек приложения.

`pom.xml:` Файл конфигурации Maven.

# Prometheus
![img1](https://github.com/ShumAhd/Spring-framework-11/blob/main/img/2024-02-23_180708.jpg)

![img2](https://github.com/ShumAhd/Spring-framework-11/blob/main/img/2024-02-23_182049.jpg)

### Файл конфиг Prometheus [prometheus.yml](https://github.com/ShumAhd/Spring-framework-11/blob/main/img/prometheus.yml)

# Grafana
![img3](https://github.com/ShumAhd/Spring-framework-11/blob/main/img/graf_5.png)

