Фреймворк Spring (семинары)
Урок 11. Spring Actuator. Настройка мониторинга с Prometheus и Grafana.

Домашнее задание

Задание:

Создайте новый микросервис на базе Spring Boot и включите в него зависимости Spring Actuator, Prometheus и Grafana.

Настройте Spring Actuator в вашем микросервисе для сбора следующих метрик: информации о состоянии приложения (
/actuator/health
), использования памяти (
/actuator/metrics/jvm.memory.used
), количества HTTP запросов (
/actuator/metrics/http.server.requests
), и любых других метрик по вашему выбору.

Создайте файл конфигурации Prometheus (
prometheus.yml
), в котором определите конфигурацию для сбора метрик из вашего микросервиса. Настройте интервал сбора и выберите метрики, которые вы хотите собирать.
