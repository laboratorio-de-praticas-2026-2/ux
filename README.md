# Portal Contábil — Grupo Bortone | Projeto de UX

> Projeto de design de experiência do usuário para o **Portal Contábil do Grupo Bortone**, desenvolvido na disciplina **Laboratório de Práticas — UX**.

![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)
![Figma](https://img.shields.io/badge/design-Figma-F24E1E?logo=figma&logoColor=white)
![Licença](https://img.shields.io/badge/licença-MIT-blue)

---

## 📌 Sumário

- [Sobre o projeto](#-sobre-o-projeto)
- [Protótipo no Figma](#-protótipo-no-figma)
- [Contexto e problema](#-contexto-e-problema)
- [Objetivos](#-objetivos)
- [Público-alvo e personas](#-público-alvo-e-personas)
- [Processo de design](#-processo-de-design)
- [Funcionalidades do portal](#-funcionalidades-do-portal)
- [Arquitetura de informação](#-arquitetura-de-informação)
- [Design System](#-design-system)
- [Acessibilidade e usabilidade](#-acessibilidade-e-usabilidade)
- [Estrutura do repositório](#-estrutura-do-repositório)
- [Ferramentas utilizadas](#-ferramentas-utilizadas)
- [Equipe](#-equipe)
- [Próximos passos](#-próximos-passos)
- [Licença](#-licença)

---

## 📖 Sobre o projeto

Este repositório documenta o processo e os resultados do projeto de UX/UI do **Portal Contábil do Grupo Bortone**, uma plataforma pensada para centralizar o relacionamento entre o escritório contábil e seus clientes, com foco em clareza, agilidade e autonomia no acesso a informações e serviços contábeis.

`[PREENCHER: resumo de 2 a 3 linhas sobre o escopo real do projeto]`

## 🎨 Protótipo no Figma

| Item | Link |
|------|------|
| Arquivo de design (Laboratório de Práticas — UX) | [Abrir no Figma](https://www.figma.com/design/h22dHpAlf32B7UjBpVEU3Z/Laborat%C3%B3rio-de-Pr%C3%A1ticas---UX?node-id=1-2&t=o0O729wiPBq2d7XL-1) |

> **Nota:** verifique se o arquivo está com permissão de visualização para quem tiver o link.

## 🧩 Contexto e problema

O **Grupo Bortone** atua na área contábil `[PREENCHER: segmentos/serviços]` e atende clientes que precisam acessar documentos, guias, obrigações e comunicados de forma prática.

**Problemas identificados:**

- `[PREENCHER: ex.: dificuldade para encontrar documentos e guias]`
- `[PREENCHER: ex.: comunicação dispersa entre e-mail, WhatsApp e telefone]`
- `[PREENCHER: ex.: falta de visibilidade sobre prazos e pendências]`

## 🎯 Objetivos

**Objetivo geral**
Projetar uma experiência de portal contábil intuitiva, acessível e eficiente para clientes e equipe do Grupo Bortone.

**Objetivos específicos**

- [ ] Centralizar documentos, guias e obrigações em um único ambiente
- [ ] Reduzir o tempo para encontrar informações e realizar tarefas
- [ ] Melhorar a comunicação entre cliente e escritório
- [ ] Garantir consistência visual por meio de um design system
- [ ] `[PREENCHER: outros objetivos]`

## 👥 Público-alvo e personas

| Persona | Perfil | Principais necessidades |
|---------|--------|-------------------------|
| `[Nome da persona 1]` | `[ex.: empresário, MEI, pequena empresa]` | `[PREENCHER]` |
| `[Nome da persona 2]` | `[ex.: gestor financeiro]` | `[PREENCHER]` |
| `[Nome da persona 3]` | `[ex.: colaborador interno do escritório]` | `[PREENCHER]` |

## 🔄 Processo de design

O projeto seguiu uma abordagem centrada no usuário:

1. **Descoberta** — pesquisa com usuários, entrevistas, análise de concorrentes e benchmarking
2. **Definição** — personas, jornadas do usuário, mapa de empatia e definição do problema
3. **Ideação** — brainstorming, fluxos de navegação e arquitetura de informação
4. **Prototipação** — wireframes de baixa fidelidade e protótipo de alta fidelidade
5. **Validação** — testes de usabilidade e iteração com base no feedback

> Ajuste as etapas conforme o que foi realmente executado no projeto.

## ⚙️ Funcionalidades do portal

- 🔐 Login e recuperação de acesso
- 🏠 Dashboard com resumo de pendências e prazos
- 📄 Central de documentos (envio, consulta e download)
- 💸 Guias e impostos a pagar
- 📅 Calendário de obrigações fiscais
- 💬 Canal de comunicação / solicitações
- 🔔 Notificações e comunicados
- 👤 Perfil e configurações da conta

`[PREENCHER: confirmar e ajustar conforme as telas do Figma]`

## 🗺️ Arquitetura de informação

```text
Portal Contábil
├── Login
├── Dashboard
├── Documentos
│   ├── Enviar
│   └── Consultar
├── Financeiro
│   ├── Guias e impostos
│   └── Histórico
├── Obrigações e prazos
├── Solicitações / Atendimento
├── Notificações
└── Perfil
```

`[PREENCHER: substituir pela estrutura real de navegação]`

## 🎛️ Design System

| Elemento | Definição |
|----------|-----------|
| **Cores primárias** | `[PREENCHER: hex]` |
| **Cores secundárias** | `[PREENCHER: hex]` |
| **Tipografia** | `[PREENCHER: fonte e escala]` |
| **Grid / espaçamento** | `[PREENCHER: ex.: grid de 12 colunas, base 8px]` |
| **Componentes** | Botões, campos de formulário, cards, tabelas, modais, alertas, navegação |
| **Ícones** | `[PREENCHER: biblioteca utilizada]` |

## ♿ Acessibilidade e usabilidade

O projeto considera:

- Contraste adequado entre texto e fundo (WCAG 2.1 — nível AA)
- Hierarquia visual clara e tipografia legível
- Áreas de toque e clique adequadas
- Feedback visual para ações, erros e estados do sistema
- As 10 heurísticas de usabilidade de Nielsen

## 📁 Estrutura do repositório

```text
.
├── README.md
├── docs/
│   ├── pesquisa/            # Entrevistas, benchmarking, insights
│   ├── personas/            # Personas e jornadas
│   ├── fluxos/              # Fluxos de usuário e arquitetura de informação
│   └── testes-usabilidade/  # Roteiros e resultados
├── assets/
│   ├── telas/               # Exports das telas do protótipo
│   └── design-system/       # Cores, tipografia e componentes
└── LICENSE
```

## 🛠️ Ferramentas utilizadas

- [Figma](https://www.figma.com/) — design e prototipação
- `[PREENCHER: FigJam, Miro, Notion, Maze, etc.]`
- GitHub — documentação e versionamento

## 👨‍💻 Equipe

| Nome | Função | Contato |
|------|--------|---------|
| `[Nome]` | `[ex.: UX Researcher]` | `[LinkedIn / GitHub]` |
| `[Nome]` | `[ex.: UI Designer]` | `[LinkedIn / GitHub]` |
| `[Nome]` | `[ex.: Product Designer]` | `[LinkedIn / GitHub]` |

**Orientação / Instituição:** `[PREENCHER: professor(a), curso e instituição]`

## 🚀 Próximos passos

- [ ] Realizar nova rodada de testes de usabilidade
- [ ] Refinar o protótipo com base no feedback
- [ ] Documentar o design system completo
- [ ] Preparar o handoff para desenvolvimento
- [ ] `[PREENCHER]`

## 📄 Licença

Este projeto é de caráter acadêmico e está sob a licença [MIT](LICENSE). Marcas, logotipos e identidade visual do **Grupo Bortone** pertencem aos seus respectivos proprietários.

---

<p align="center">Desenvolvido como parte do <strong>Laboratório de Práticas — UX</strong> 💙</p>
