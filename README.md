<!-- ===================== HEADER: animated typing banner ===================== -->
<div align="center">

  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=800&color=36BCF7&center=true&vCenter=true&width=650&lines=Hi+%F0%9F%91%8B+I'm+Hrithik+Kumar;Java+Backend+Engineer;Spring+Boot+%7C+PostgreSQL+%7C+Kafka;I+build+systems+that+scale+%E2%9A%A1;Always+learning%2C+always+shipping+%F0%9F%9A%80" alt="Typing SVG" />
  </a>

  <br/>

  <!-- Visitor counter -->
  <img src="https://komarev.com/ghpvc/?username=ihrithiksonar&label=Profile%20views&color=36BCF7&style=flat" alt="profile views" />

  <!-- Social badges -->
  <a href="https://www.linkedin.com/in/YOUR-LINKEDIN/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:YOUR-EMAIL@example.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://leetcode.com/YOUR-HANDLE/">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=flat&logo=leetcode&logoColor=white" alt="LeetCode"/>
  </a>

</div>

---

## 🧑‍💻 About Me

```java
public class Hrithik extends Engineer {

    @Override
    public Focus currentFocus() {
        return Focus.builder()
            .role("Java Backend Engineer")
            .building("Scalable, secure REST & event-driven services")
            .learning(List.of("Distributed Systems", "Kafka", "Agentic AI"))
            .solving("DSA daily — one pattern at a time")
            .motto("Make it correct, then make it fast.")
            .build();
    }
}
```

- 🔭 I work with **Spring Boot**, **PostgreSQL**, **Kafka**, and **AWS Lambda**.
- 🌱 Currently going deep on **concurrency, locking, and system scaling**.
- 🧩 Sharpening **Data Structures & Algorithms** — sliding window, recursion, bit manipulation.
- 🤖 Exploring **Agentic AI** and the **Model Context Protocol (MCP)**.
- 💬 Ask me about **transactions, JPA mappings, or why you should never store money in a `double`.**

---

## 🛠️ Tech Stack

<div align="center">

### Languages
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

### Frameworks & Tools
![Spring](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)

### Data & Messaging
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

### Cloud & DevOps
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

---

## 📊 GitHub in Numbers

<div align="center">

  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=ihrithiksonar&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true" alt="stats" />
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ihrithiksonar&layout=compact&theme=tokyonight&langs_count=8" alt="top langs" />

  <br/>

  <img src="https://github-readme-streak-stats.herokuapp.com/?user=ihrithiksonar&theme=tokyonight&hide_border=false" alt="streak" />

  <br/>

  <img src="https://github-profile-trophy.vercel.app/?username=ihrithiksonar&theme=tokyonight&no-frame=true&column=7&margin-w=8" alt="trophies" />

</div>

---

## 🐍 Contribution Activity

<!--
  This needs a GitHub Action to generate the snake animation.
  See setup instructions in the collapsible section below.
-->
<div align="center">
  <img src="https://raw.githubusercontent.com/ihrithiksonar/ihrithiksonar/output/github-contribution-grid-snake-dark.svg" alt="snake animation" />
</div>

<details>
  <summary>⚙️ How to enable the snake animation</summary>

  Create `.github/workflows/snake.yml` in your profile repo:

  ```yaml
  name: Generate Snake

  on:
    schedule:
      - cron: "0 0 * * *"   # daily
    workflow_dispatch:

  jobs:
    generate:
      runs-on: ubuntu-latest
      steps:
        - uses: Platane/snk/svg-only@v3
          with:
            github_user_name: ${{ github.repository_owner }}
            outputs: |
              dist/github-contribution-grid-snake-dark.svg?palette=github-dark
        - uses: crazy-max/ghaction-github-pages@v4
          with:
            target_branch: output
            build_dir: dist
          env:
            GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
  ```
</details>

---

## 🚀 What I'm Building

<details open>
  <summary><b>🏦 ATM Banking Service</b> — concurrency done right</summary>

  Spring Boot + PostgreSQL. Deposit/withdraw APIs with **pessimistic row locking**
  (`SELECT ... FOR UPDATE`), optimistic `@Version` backstop, idempotency keys, and a
  transaction ledger. Proof that two withdrawals can't overdraft the same account.
</details>

<details>
  <summary><b>🎟️ TicketHub</b> — booking under load</summary>

  Event/seat booking platform exploring every JPA mapping, seat-hold expiry,
  caching, JWT security, and Kafka-driven notifications.
</details>

<details>
  <summary><b>🤖 Agentic AI in Java</b> — tools, LLMs & MCP</summary>

  A from-scratch agent loop with a tool registry, plus a Spring AI MCP server.
</details>

---

## 🧠 Currently Learning

```mermaid
mindmap
  root((Hrithik))
    Backend
      Spring Boot
      Transactions & Locking
      REST + Event-Driven
    Data
      PostgreSQL
      Kafka
      Redis
    Foundations
      DSA
      System Design
    AI
      Agentic AI
      MCP
```

---

<div align="center">

  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" alt="quote" />

  <br/><br/>

  <i>“First, solve the problem. Then, write the code.” — John Johnson</i>

  <br/><br/>

  ⭐️ From [ihrithiksonar](https://github.com/ihrithiksonar)

</div>

