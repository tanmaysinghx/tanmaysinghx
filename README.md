<h1 align="center">Hi, I'm <span style="color:#0078ff">Tanmay Singh</span> 👋</h1>

<p align="center">
  <strong>Software Engineer | Specialized in Scalable Distributed Systems & Full-Stack Development</strong>
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=20&pause=1000&color=0078FF&center=true&vCenter=true&width=600&lines=Java+25+%2B+Spring+Boot+4.x;Rust+%7C+Axum+%7C+Tauri;OAuth+2.1+%2F+OIDC+Identity;Angular+21%2B+%28Signals+%2F+RxJS%29;Jenkins+%7C+Docker+%7C+Grafana" alt="Typing Animation" />
</p>

---

<img align="right" alt="Coding" width="380" src="https://cdn.dribbble.com/users/1162077/screenshots/3848914/programmer.gif">

### 🧠 Profile Overview

* 🚀 **System Design:** Building **Modular Monoliths** and **Microservices** with a focus on domain-driven design.
* ☕ **Modern Java:** Leveraging **Java 25 Virtual Threads** and **Spring Boot 4** for high-throughput backends.
* ⚙️ **API Development:** Designing robust RESTful APIs and asynchronous event-driven architectures.
* 🦀 **Rust:** Shipping single-binary services and apps with **Axum**, **SQLx** and **Tauri** (secrets vault, blog API, VPN clients).
* 🔐 **Identity & Security:** Building a self-hosted **OAuth 2.1 / OIDC** provider with PKCE, MFA, audit logs and envelope encryption.
* 🅰️ **Frontend Engineering:** Crafting reactive UIs using **Angular**, **Signals**, **RxJS**, **SingleSPA**, and **Webpack**.
* ☁️ **Cloud Infrastructure:** Architecting scalable environments on **AWS** including EC2, S3, RDS, CloudWatch, and EKS.
* 🛠️ **Ops:** Running my own platform with **Jenkins** pipelines, **Docker**, encrypted per-environment config, and **Prometheus / Loki / Grafana** monitoring.
* 📦 **Open Source:** Contributing to Rust projects like [notecraft](https://github.com/AlienTechSoftware/notecraft) and maintaining [npm packages](https://www.npmjs.com/~tanmaysinghx99).

---

### 🏛️ Architectural Expertise

* **Modular Monoliths:** Designing encapsulated modules to ensure easy transitions to Microservices when needed.
* **Microservices:** Orchestrating services with **Spring Cloud**, **Kafka** for events, and **Redis** for state.
* **Event-Driven Architecture:** Implementing asynchronous communication, background processing, and robust messaging pipelines.
* **DevOps:** Automating deployments via **Jenkins**, **Docker**, and **GitHub Actions**: build → push → promote from DEV to QA, with secrets decrypted only while a pipeline runs.
* **Observability:** Logs and metrics with **Prometheus**, **Loki**, **Promtail** and **Grafana**, plus my own single-JAR telemetry platform.

---

### 🛠️ Tech Stack & Infrastructure

| Layer              | Technologies                                                                                  |
| :----------------- | :-------------------------------------------------------------------------------------------- |
| **Core Backend**   | **Java 25**, **Spring Boot 4.x**, Hibernate, Spring Security, JDBC, Lombok, Spring Validation |
| **Systems**        | **Rust**, Axum, SQLx, Tauri, Tokio                                                            |
| **Identity**       | **OAuth 2.1**, **OpenID Connect**, PKCE, TOTP MFA, AES-256-GCM                                |
| **Core Frontend**  | **Angular 21**, TypeScript, RxJS, React, SCSS, Tailwind                                       |
| **Cloud (AWS)**    | **EC2**, **S3**, **RDS**, **EKS**, Lambda, IAM                                                |
| **Messaging/Data** | **Apache Kafka**, **Redis**, MySQL, PostgreSQL, Oracle, H2, FFmpeg                            |
| **DevOps / Ops**   | **Jenkins**, **Docker**, GitHub Actions, Prometheus, Loki, Grafana, WireGuard                 |

---

### 🚀 Featured Projects

What I'm building right now. Most of it is one self-hosted suite that signs in through Portal SSO.

| Project | What it is | Stack |
| :------ | :--------- | :---- |
| 🔐 [**Portal SSO**](https://github.com/GetAppCraft-Inc/portal-sso) | Self-hosted OAuth 2.1 / OpenID Connect identity provider with an admin console, MFA, magic links and a client SDK. One jar. | Java 25, Spring Boot 4.1, Angular 21 |
| 🗝️ [**Keystone Vault**](https://github.com/tanmaysinghx/keystone-vault) | Encrypted secrets and config store for the Portal suite: versioned keys and whole `.properties` files, Spring Cloud Config compatible, two-person approvals. | **Rust**, Angular 21, AES-256-GCM |
| 🛡️ [**Hidenseek VPN**](https://github.com/tanmaysinghx/hidenseek-vpn) | Self-hosted WireGuard VPN across many VPS locations, with Portal SSO sign-in, an admin console and apps for Windows, Linux and Android. | Java, **Rust / Tauri**, React, Go |
| 🥚 [**Eggless Observability**](https://github.com/tanmaysinghx/eggless-observability) | Free log and telemetry platform in a single JAR, with live tail over WebSockets and H2, PostgreSQL or MySQL storage. | Java 25, Spring Boot 4.1, Angular 21 |
| ♻️ [**Zynqo**](https://github.com/tanmaysinghx/zynqo-spring-boot-starter) | Spring Boot starter for distributed idempotency: add `@Zynqo` and repeated requests replay the stored response. | Java, Spring Boot 4.1, Redis |
| ⚙️ [**ts-infra-devops**](https://github.com/tanmaysinghx/ts-infra-devops-5005) | Jenkins pipelines, encrypted per-environment config and the monitoring stack that build and run my whole platform. | Jenkins, Groovy, Docker, Grafana |
| 🌐 [**tanmaysinghx.com**](https://github.com/tanmaysinghx/selfie-portfolio) | My portfolio and blog. Angular on Vercel, with a **Rust** API for views, likes and comments. | Angular 21, **Rust (Axum + SQLx)**, MySQL |

---

### 🌍 Open Source Contributions

Recent pull requests to projects I don't own:

#### 🦀 [AlienTechSoftware/notecraft](https://github.com/AlienTechSoftware/notecraft): open-source note-taking app in pure Rust
* 🟡 [feat(boxes): remove a blank box once the caret leaves it](https://github.com/AlienTechSoftware/notecraft/pull/48) (*open, Nov 2026*)
* ✅ [fix: stop a click beside an object from deadlocking the window](https://github.com/AlienTechSoftware/notecraft/pull/16) (*merged, Oct 2026*)
* ✅ [fix(rtl): lay a line out in the page's direction, not its first letter](https://github.com/AlienTechSoftware/notecraft/pull/13) (*merged, Oct 2026*)

#### 🎫 [Peppermint-Lab/peppermint](https://github.com/Peppermint-Lab/peppermint) : open-source help desk & issue tracker (⭐ 3k+)
* ✅ [Modified random digit generator](https://github.com/Peppermint-Lab/peppermint/pull/370) (*merged, Sep 2024*)

👉 [See all my pull requests](https://github.com/pulls?q=is%3Apr+author%3Atanmaysinghx+-user%3Atanmaysinghx)

---

### 🏆 Certifications

| Certification                                                                                                                                                                            | Issuer    | Credential ID                      | Expiry    |
| :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :-------- | :--------------------------------- | :-------- |
| [![GitHub Copilot](https://img.shields.io/badge/Microsoft-GitHub_Copilot-181717?style=flat-square\&logo=github)](YOUR_VERIFICATION_LINK_HERE)                                            | Microsoft | `B94AF1A881AD1347`                 | Jun 2028  |
| [![Azure Fundamentals](https://img.shields.io/badge/Microsoft_Certified-Azure_Fundamentals-0089D6?style=flat-square\&logo=microsoftazure\&logoColor=white)](YOUR_VERIFICATION_LINK_HERE) | Microsoft | `94C369F93FF70A31`                 | No Expiry |
| [![AWS Developer Associate](https://img.shields.io/badge/AWS_Certified-Developer_Associate-FF9900?style=flat-square\&logo=amazonaws\&logoColor=white)](YOUR_VERIFICATION_LINK_HERE)      | AWS       | `e6e9e3a34d224dc29a36ccdf1336cb32` | Aug 2028  |
| [![AWS Solutions Architect](https://img.shields.io/badge/AWS_Certified-Solutions_Architect-FF9900?style=flat-square\&logo=amazonaws\&logoColor=white)](YOUR_VERIFICATION_LINK_HERE)      | AWS       | `553056fb23f04e4abe367a7a1dbd1684` | Jul 2028  |
| [![AWS Cloud Practitioner](https://img.shields.io/badge/AWS_Certified-Cloud_Practitioner-FF9900?style=flat-square\&logo=amazonaws\&logoColor=white)](YOUR_VERIFICATION_LINK_HERE)        | AWS       | `2126d0468c3646a590f09012a4ec8c95` | Jun 2028  |

---

### 📊 GitHub Stats & Impact

<p align="center">
  <img
    src="./profile/stats.svg"
    alt="GitHub Stats"
    height="180"
  />
  <img
    src="./profile/top-langs.svg"
    alt="Top Languages"
    height="180"
  />
</p>

> **Note:** `stats.svg` and `top-langs.svg` need to exist in your profile repository. These are separate from the DSA section.

---

### 🧠 DSA Journey

> Tracking my journey through Data Structures & Algorithms by solving
> LeetCode problems and documenting every solution.

<table>
  <tr>
    <td align="center">
      <strong>🔥 Problems Solved</strong><br>
      <h2>45+</h2>
    </td>
    <td align="center">
      <strong>🟢 Easy</strong><br>
      <h2>41</h2>
    </td>
    <td align="center">
      <strong>🟡 Medium</strong><br>
      <h2>3</h2>
    </td>
    <td align="center">
      <strong>🔴 Hard</strong><br>
      <h2>1</h2>
    </td>
  </tr>
</table>

---

### 🤝 Connect & Collaborate

<p align="left">
  <a href="https://www.linkedin.com/in/tanmaysinghx">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:tanmaysinghx@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" />
  </a>
  <a href="https://tanmaysinghx.com">
    <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" />
  </a>
</p>

---

### 📈 Profile Views

*Counting of visitors to this page started from June 12, 2022.*

<p align="left">
  <img
    src="https://komarev.com/ghpvc/?username=tanmaysinghx&label=Profile+Views&color=0078ff&style=flat-square"
    alt="Profile views"
  />
</p>

---
