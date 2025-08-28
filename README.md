# 👋 Hi, I'm Konda Shravan

**Full Stack Developer | 9 Years Experience | React.js, Vue.js, Spring Boot, Node.js, Microservices**

📍 Hyderabad, India  
📧 konda.shravan@outlook.com  
📞 +91 9550033748  
🔗 [LinkedIn](https://linkedin.com/in/kondas1202)

---

## 🧑‍💻 About Me

I’m a Full Stack Developer with **9 years of experience** building scalable, performant, and secure web applications across multiple frameworks and cloud platforms. I've delivered solutions for clients across domains, collaborating with global teams in agile environments.

I’m proficient in both frontend and backend development using:

- **Frontend:** React.js, Vue.js, HTML5, CSS3, Bootstrap, Tailwind  
- **Backend:** Spring Boot, Spring Framework, **Microservices Architecture**, Node.js  
- **Cloud:** AWS (EC2, S3, Lambda), Azure (App Services, Functions)  
- **DevOps:** CI/CD pipelines, GitHub Actions, Jenkins, Docker, Kubernetes  
- **Databases:** MySQL, PostgreSQL, MongoDB  
- **Languages:** Java, C#, JavaScript/TypeScript, Ruby  
- **Tools:** Git, Jira, VS Code, IntelliJ, Postman  

I’m also certified at **A2 level in German** and open to **relocation across Europe**.

---

## 🏗️ Spring Boot & Microservices Expertise

- Designed and developed **domain-driven microservices** with Spring Boot & Spring Cloud  
- Implemented **API Gateway** (Spring Cloud Gateway) and **Service Discovery** (Eureka)  
- Secured services using **Spring Security + OAuth2/JWT**  
- Managed **distributed configurations** with Spring Cloud Config  
- Applied **circuit breakers & resilience patterns** (Resilience4j/Hystrix)  
- Built **event-driven architectures** with Kafka & RabbitMQ  
- Ensured **decentralized data management** using PostgreSQL, MongoDB, and Redis  
- Deployed microservices on **AWS & Azure** with Docker & Kubernetes  

---

## 🖼️ Microservices Architecture (Example)

```mermaid
flowchart TD
    Client[🌐 Client Apps] -->|HTTPS| Gateway[🔑 API Gateway]
    Gateway -->|Service Discovery| Eureka[(Eureka Server)]
    
    Gateway --> UserService[👤 User Service]
    Gateway --> OrderService[📦 Order Service]
    Gateway --> PaymentService[💳 Payment Service]
    
    UserService --> MySQL[(MySQL DB)]
    OrderService --> PostgreSQL[(PostgreSQL DB)]
    PaymentService --> MongoDB[(MongoDB DB)]
    
    OrderService -->|Events| Kafka[(Kafka Broker)]
    PaymentService -->|Events| Kafka


flowchart LR
    Dev[👨‍💻 Developer] -->|Push Code| GitHub[🐙 GitHub Repo]
    GitHub -->|Trigger| CI[⚙️ GitHub Actions/Jenkins]
    CI -->|Build| Docker[🐳 Docker Image]
    Docker -->|Deploy| K8s[☸️ Kubernetes Cluster]
    K8s -->|Cloud Deploy| AWS[(AWS)] & Azure[(Azure)]

## 🚀 GitHub Stats ![Shravan's GitHub stats](https://github-readme-stats.vercel.app/api?username=konda-shravan&show_icons=true&theme=tokyonight)
