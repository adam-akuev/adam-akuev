# 👋 Привет! Меня зовут Адам Акуев

**Java Developer | Microservices | Spring Ecosystem**

*Создаю современные бэкенд-решения с использованием микросервисной архитектуры*

---

## 🛠 Технологический стек

| **Категория** | **Технологии** |
|---------------|----------------|
| **Backend** | `Java` `Spring Boot` `Spring Cloud` `Spring Data` |
| **Базы данных** | `PostgreSQL` `Redis` `H2` |
| **Message Brokers** | `Kafka` `RabbitMQ` |
| **Инфраструктура** | `Docker` `Docker Compose` `Maven` `Git` |
| **Изучаю** | `Kubernetes` `AWS` `Prometheus` `Grafana` |

---

## 🚀 Ключевые проекты

### 🎬 Cinema Management System
**Микросервисная платформа для управления кинотеатром**

```java
@SpringBootApplication
@EnableEurekaClient
public class CinemaApplication {
    public static void main(String[] args) {
        SpringApplication.run(CinemaApplication.class, args);
    }
}
```

Архитектура:

text
┌─────────────┐    ┌─────────────┐    ┌─────────────┐
│   Gateway   │───▶│ Movie Service │───▶│  PostgreSQL  │
└─────────────┘    └─────────────┘    └─────────────┘
        │
┌─────────────┐    ┌─────────────┐    ┌─────────────┐
│ User Service│───▶│Booking Service│───▶│    Redis    │
└─────────────┘    └─────────────┘    └─────────────┘
        │                  │
┌─────────────┐    ┌─────────────┐
│   MongoDB   │    │    Kafka    │
└─────────────┘    └─────────────┘
Особенности:

🏗 Микросервисная архитектура (5+ независимых сервисов)

🔄 Асинхронная коммуникация через Kafka

🐳 Полная контейнеризация с Docker

⚙ Централизованная конфигурация Spring Cloud Config

🔍 Service Discovery с Eureka

🚪 API Gateway для маршрутизации

📊 Активность на GitHub
<div align="center">
https://streak-stats.demolab.com/?user=admin-aluev&theme=dark&hide_border=true
https://github-readme-stats.vercel.app/api?username=admin-aluev&show_icons=true&theme=dark&hide_border=true

</div>
📫 Контакты
<div align="center">
📱 Telegram	@Adams_095
📧 Email	akuev2005@mail.ru
💼 GitHub	admin-aluev
📍 Локация	Россия, Москва (MSK)
</div>
<div align="center">
🎯 В активном поиске стажировки/первой работы в Java-разработке!
📞 Готов к техническому собеседованию в любое время

</div>
