<!-- ============ BANNER ============ -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:4A2564,100:ea5b0c&height=180&section=header&text=Vitor&fontSize=60&fontColor=ffffff&fontAlignY=35&desc=Java%20%7C%20Spring%20Boot%20Developer&descAlignY=58&descSize=18&animation=fadeIn" />

<!-- ============ DIGITAÇÃO ============ -->
<div align="center">
  <a href="https://github.com/vittoralemao">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1000&color=EA5B0C&center=true&vCenter=true&random=false&width=600&lines=Welcome+to+my+profile!;Java+Developer+%E2%98%95;Building+projects+with+Spring+Boot+%F0%9F%8D%83;public+static+void+main(String%5B%5D+args)" alt="Typing SVG">
  </a>
</div>

<!-- ============ CONTATOS ============ -->
<div align="center">
  <a href="https://www.linkedin.com/in/vitoralemao" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:contato.vitoralemao@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <img src="https://komarev.com/ghpvc/?username=vittoralemao&style=for-the-badge&color=EA5B0C&label=VISITAS" />
</div>

<br>

## `SobreMim.java`

```java
public class SobreMim {

    private final String nome        = "Vitor Hugo";
    private final String cargo       = "Desenvolvedor Back-end Java";
    private final String[] stack     = {"Java", "Spring Boot", "Spring Data JPA", "PostgreSQL", "Docker"};
    private final String aprendendo  = "Spring Security (JWT) e Spring Cloud / AWS";
    private final String idiomas     = "Português 🇧🇷 | English (learning) 🇺🇸";

    public String filosofia() {
        return "Se alguém teve o esforço de construir, eu consigo ter o esforço de aprender.";
    }
}
```

## `Stack`

<div align="center">

**Linguagem & Frameworks**

<img src="https://skillicons.dev/icons?i=java,spring,hibernate,maven&theme=dark" />

**Banco de Dados & Infra**

<img src="https://skillicons.dev/icons?i=postgres,mysql,docker,aws&theme=dark" />

**Ferramentas**

<img src="https://skillicons.dev/icons?i=idea,git,github,postman,notion&theme=dark" />

</div>

## `Projeto em destaque`

> API RESTful de gerenciamento de biblioteca, construída camada por camada para dominar o ecossistema Spring de ponta a ponta: da persistência à segurança e ao deploy na nuvem.

🔗 **[Ver repositório](https://github.com/vittoralemao/biblioteca)**

### `Arquitetura`

```mermaid
flowchart LR
    C([Cliente]) -->|Requisição JSON| CT[Controller]
    CT -->|DTO de entrada| S[Service]
    S -->|Entity| R[Repository]
    R -->|JPA / Hibernate| DB[(PostgreSQL)]
    S -.->|DTO de saída| CT
    CT -.->|Resposta JSON| C

    classDef roxo fill:#4A2564,stroke:#EA5B0C,stroke-width:2px,color:#fff
    classDef laranja fill:#EA5B0C,stroke:#4A2564,stroke-width:2px,color:#fff
    class C,DB laranja
    class CT,S,R roxo
```

<!-- ============ RODAPÉ ============ -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:ea5b0c,100:4A2564&height=120&section=footer" />
