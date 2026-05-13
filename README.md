# Sistema de Gestão das Olimpíadas (SGO) 🏅

Este README.md documenta o projeto de modelagem UML do Sistema de Gestão das Olimpíadas (SGO), desenvolvido como trabalho acadêmico da disciplina de Projeto de Software.

<table>
  <tr>
    <th>Projeto</th>
    <td>Sistema de Gestão das Olimpíadas (SGO)</td>
  </tr>
  <tr>
    <th>Disciplina</th>
    <td>Projeto de Software</td>
  </tr>
  <tr>
    <th>Instituição</th>
    <td>PUC Minas</td>
  </tr>
  <tr>
    <th>Professor</th>
    <td>Prof. Dr. João Paulo Aramuni</td>
  </tr>
</table>

---

## 📌 Sobre o Projeto

O Sistema de Gestão das Olimpíadas (SGO) é uma aplicação desenvolvida para apoiar a organização e o gerenciamento completo de jogos olímpicos. O sistema centraliza o controle de competições, inscrições de atletas, alocação de locais de provas e registro de resultados. O SGO foi modelado com base em princípios de engenharia de software, utilizando UML para representar seus requisitos funcionais, arquitetura e estrutura interna.

---

## 📖 Histórias de Usuário

| ID | História |
|----|----------|
| **US01** | Como um Administrador, eu quero cadastrar modalidades esportivas para que estejam disponíveis nas competições. |
| **US02** | Como um Administrador, eu quero cadastrar países para que atletas possam ser associados a eles. |
| **US03** | Como um Administrador, eu quero cadastrar locais de provas para que seja possível alocá-los sem conflitos de horário. |
| **US04** | Como um Administrador, eu quero cadastrar competições para que o calendário olímpico seja organizado. |
| **US05** | Como um Delegado, eu quero cadastrar atletas da minha delegação para que sejam inscritos nas competições. |
| **US06** | Como um Delegado, eu quero inscrever um atleta em uma competição para que ele participe oficialmente da prova. |
| **US07** | Como um Delegado, eu quero que o sistema impeça um atleta de representar mais de um país na mesma modalidade para que as regras olímpicas sejam respeitadas. |
| **US08** | Como um Administrador, eu quero alocar um local para uma competição para que as provas tenham um espaço físico definido. |
| **US09** | Como um Administrador, eu quero que o sistema valide conflitos de horário para que dois eventos não ocorram no mesmo local ao mesmo tempo. |
| **US10** | Como um Administrador, eu quero registrar resultados de uma competição para que o desempenho seja documentado. |
| **US11** | Como um Administrador, eu quero determinar o 1º, 2º e 3º lugares (Ouro, Prata e Bronze) para que o quadro de medalhas seja atualizado. |
| **US12** | Como um Comitê Olímpico, eu quero gerar relatórios de medalhas por país para que o desempenho seja acompanhado. |
| **US13** | Como um Comitê Olímpico, eu quero visualizar o quadro geral de medalhas para que a classificação oficial seja pública. |
| **US14** | Como um Atleta, eu quero consultar minhas inscrições e cronograma para que eu possa me preparar para as provas. |
| **US15** | Como um Administrador, eu quero consultar a disponibilidade de locais para que o planejamento seja eficiente. |

---

## 🛠️ Tecnologias Utilizadas

- **PlantUML** — Ferramenta de modelagem UML utilizada para criação de todos os diagramas do projeto.
- **Visual Studio Code** — Editor de código utilizado para edição dos arquivos `.puml` e do `README.md`.
- **Markdown** — Linguagem de marcação utilizada para documentação do projeto.

---

## 🏗️ Arquitetura (Diagramas UML)

<h3>Diagrama de Caso de Uso</h3>
<img width="800px" src="https://github.com/Dolabelaa/sistema-gestao-olimpiadas/blob/main/imagens/Diagrama-casos-de-uso.png"/>

<h3>Diagrama de Classes</h3>
<img width="800px" src="https://github.com/Dolabelaa/sistema-gestao-olimpiadas/blob/main/imagens/Diagrama-de-classes.png"/>

<h3>Diagrama de Pacotes</h3>
<img width="800px" src="https://github.com/Dolabelaa/sistema-gestao-olimpiadas/blob/main/imagens/Diagrama-de-pacotes.png"/>

<h3>Diagrama de Componentes</h3>
<img width="800px" src="https://github.com/Dolabelaa/sistema-gestao-olimpiadas/blob/main/imagens/Diagrama-de-componentes.png"/>

<h3>Diagrama de Implantação</h3>
<img width="800px" src="https://github.com/Dolabelaa/sistema-gestao-olimpiadas/blob/main/imagens/Diagrama-de-implementacao.png"/>

---

## 📁 Estrutura de Pastas

```
PROJETO-DE-SOFTWARE/
│
├── README.md
│
├── imagens/
│   ├── Diagrama-casos-de-uso.png
│   ├── Diagrama-de-classes.png
│   ├── Diagrama-de-componentes.png
│   ├── Diagrama-de-implementacao.png
│   └── Diagrama-de-pacotes.png
│
└── codigos/
    ├── diagrama-de-caso-de-uso.puml
    ├── diagrama-de-classes.puml
    ├── diagrama-de-componentes.puml
    ├── diagrama-de-implantacao.puml
    └── diagrama-de-pacotes.puml
```

---

## 👥 Autores

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/Dolabelaa">
        <img src="https://github.com/Dolabelaa.png" width="100px;" alt="Lucas Dolabela"/><br />
        <sub><b>Lucas Dolabela</b></sub>
      </a><br />
      <a href="https://www.linkedin.com/in/lucas-dolabela/">LinkedIn</a>
    </td>
    <td align="center">
      <a href="https://github.com/ZegarraV">
        <img src="https://github.com/ZegarraV.png" width="100px;" alt="Vinicius Zegarra"/><br />
        <sub><b>Vinicius Zegarra</b></sub>
      </a><br />
      <a href="https://www.linkedin.com/in/vinicius-zegarra-palhares/">LinkedIn</a>
    </td>
  </tr>
</table>

---

## 🙏 Agradecimentos

Gostaria de agradecer aos seguintes canais e pessoas que foram fundamentais para o desenvolvimento deste projeto:

**Engenharia de Software PUC Minas** - Pelo apoio institucional, estrutura acadêmica e fomento à inovação.

**Prof. Dr. João Paulo Aramuni** - Pelos valiosos ensinamentos sobre Arquitetura de Software e Padrões de Projeto.
