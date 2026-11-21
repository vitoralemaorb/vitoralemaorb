<!-- ============ BANNER ============ -->
<img src="./assets/banner.svg" alt="Vítor Hugo: desenvolvedor back-end Java e Spring Boot" width="100%" />
<!-- ============ DIGITAÇÃO ============ -->
<div align="center">
  <a href="https://github.com/vitoralemaorb/openfinance-lab">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1000&color=EA5B0C&center=true&vCenter=true&random=false&width=600&lines=Welcome+to+my+profile!;Java+Developer+%E2%98%95;Building+projects+with+Spring+Boot+%F0%9F%8D%83;public+static+void+main(String%5B%5D+args)" alt="Typing SVG">
  </a>
</div>
<!-- ============ CONTATOS ============ -->
<div align="center">
  <a href="https://www.linkedin.com/in/vitoralemao" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-vitoralemao-0d1117?style=for-the-badge&logo=linkedin&logoColor=ea5b0c&labelColor=21262d" alt="LinkedIn" /></a>
  <a href="mailto:contato.vitoralemao@gmail.com"><img src="https://img.shields.io/badge/E--mail-contato.vitoralemao@gmail.com-0d1117?style=for-the-badge&logo=gmail&logoColor=ea5b0c&labelColor=21262d" alt="E-mail" /></a>
</div>
<br>
<div align="center">
  <img src="./assets/sobre-mim.svg" alt="SobreMim.java: Vítor Hugo, desenvolvedor back-end Java. Stack: Java, Spring Boot, Spring Data JPA, Spring Security (JWT), PostgreSQL, Docker e AWS. Cursa ADS na Anhanguera. Filosofia: se alguém construiu, quem sou eu para não aprender?" width="100%" />
</div>
 
## `Projeto em destaque`
 
> Ecossistema de Open Finance simulado: dois bancos fictícios, um servidor de autorização que controla o consentimento do cliente, um agregador financeiro e um assistente de IA que só acessa dados com consentimento válido e sob auditoria.
 
🔗 **[Ver repositório](https://github.com/vitoralemaorb/openfinance-lab)**
 
### `Arquitetura`
 
```mermaid
flowchart LR
    A([Agente de IA]) -->|MCP| G[ai-gateway]
    G -.->|checa consentimento| AS[auth-server]
    G -->|REST| H[finance-hub]
    H -->|OAuth 2.1| O[(banco-orion)]
    H -->|OAuth 2.1| V[(banco-vega)]
 
    classDef roxo fill:#4A2564,stroke:#EA5B0C,stroke-width:2px,color:#fff
    classDef laranja fill:#EA5B0C,stroke:#4A2564,stroke-width:2px,color:#fff
    class A,O,V laranja
    class G,AS,H roxo
```
 
<!-- ============ RODAPÉ ============ -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:ea5b0c,100:4A2564&height=120&section=footer" />
 
