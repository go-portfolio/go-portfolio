# 🚀 Алексей Павлов

Решения на **Go**

---

## 📂 Содержание

- **[rest-api](https://github.com/go-portfolio/rest-api)** — REST API с авторизацией (JWT) и PostgreSQL  
- **[concurrency-scraper](./concurrency-scraper/)** — Веб-скрейпер с использованием goroutines и worker pool  
- **[websocket-chat](https://github.com/go-portfolio/websocket-chat)** — Онлайн-чат с авторизацией и комнатами (WebSocket)  
- **[http-middleware](https://github.com/go-portfolio/http-middleware/)** — Собственная HTTP middleware-библиотека  
- **[go-service-profiling](https://github.com/go-portfolio/go-service-profiling/)** — Демонстрация профилирования CPU, памяти и задержек (pprof, trace)  
- **[go-grpc-benchmark](https://github.com/go-portfolio/go-grpc-benchmark/)** — Нагрузочное тестирование и профилирование gRPC-сервисов (Prometheus + OpenTelemetry)  
- **[order-pipeline](https://github.com/go-portfolio/order-pipeline/)** — Order Pipeline на Go + gRPC + Kafka + Redis  

---

## 🎯 Цель

Продемонстрировать практические навыки, необходимые **Go-разработчику уровня Middle/Senior**:

- Разработка REST API и микросервисов  
- Работа с PostgreSQL, Docker и миграциями  
- Использование goroutines, каналов и context  
- Реализация gRPC-сервисов  
- Создание CLI-инструментов  
- Разработка real-time сервисов (WebSocket)  
- Написание собственных библиотек и middleware  
- Анализ и оптимизация производительности (pprof, benchmark)

---

## 🛠️ Технологии

- **Go (1.22+)**  
- **PostgreSQL**  
- **Docker / Docker Compose**  
- **gRPC / Protocol Buffers**  
- **Prometheus / OpenTelemetry**  
- **WebSocket**  
- **JWT**  

---

## ⚙️ Как запустить проекты

Каждый проект из репозитория содержит собственный `README.md` с инструкциями по запуску.  
Обычно достаточно:

```bash
git clone https://github.com/go-portfolio/<project-name>.git
cd <project-name>
go run ./...
