# 🚀 Felipe Granvile
**`Mobile Developer & Data Analyst`**

[![Stars](https://custom-icon-badges.demolab.com/github/stars/8FTG8?color=F7721A&style=for-the-badge&labelColor=E75C00&logo=star&label=Stars)](https://github.com/8FTG8?tab=repositories&sort=stargazers) [![Followers](https://custom-icon-badges.demolab.com/github/followers/8FTG8?color=236ad3&labelColor=1155ba&style=for-the-badge&logo=github&label=Followers&logoColor=white)](https://github.com/8FTG8?tab=followers)

---

Formado em Análise e Desenvolvimento de Sistemas pela Fatec RP, construo produtos Flutter de ponta a ponta — do app ao backend serverless, passando por integrações de pagamento e mensageria que rodam em produção com clientes reais.

Meu foco atual é sair do "app que funciona" para o "sistema que sustenta um negócio": multi-tenancy, cobrança recorrente, segurança de dados e observabilidade. Na área de data science, aplico esse mesmo cuidado à coleta, ao processamento e à análise de dados — vejo as duas frentes como complementares, não paralelas.

Também sou entusiasta em blockchain, NFTs e nas demais tecnologias que estão pavimentando a nova era da Web3.

## 🛠️ Linguagens & Tecnologias

![Skills](https://skillicons.dev/icons?i=dart,flutter,python,nodejs,js,firebase,git)

**Também no dia a dia:** Riverpod & Provider (gerenciamento de estado) · GoRouter · Cloud Functions v2 · Cloud Firestore & Storage · Firestore/Storage Security Rules · SQFlite (offline-first) · Jest & Firebase Rules Unit Testing · integrações de API (ASAAS, Z-API/WhatsApp)

## 📌 Projetos relevantes

**StyleCaree** `(em produção)` — SaaS multi-tenant de agendamento para profissionais de beleza e bem-estar, rodando em [book.caree.com.br](https://book.caree.com.br) (clientes) e `style.caree.com.br` (profissionais) com estabelecimentos reais. Cada profissional tem página pública própria por slug, painel completo (agenda, financeiro, métricas, personalização) e assinatura paga via **ASAAS** (trial de 10 dias → cobrança recorrente → suspensão automática por inadimplência). Confirmações e lembretes de agendamento são enviados por **WhatsApp** via Z-API. Construído com Flutter Web (PWA) + Riverpod + GoRouter no front e Cloud Functions v2 (Node.js) + Firestore no back, com escritas críticas de agendamento protegidas por transações atômicas para evitar overbooking, regras de segurança por tipo de usuário e suíte de testes com Jest + Firebase Rules Unit Testing contra os emulators reais.

**[Aplicativo EggGo](https://github.com/8FTG8/EggGo)** `(em produção)` — App em Flutter para gerenciamento de clientes, produtos e vendas, criado sob medida para a empresa [EggGo](https://www.instagram.com/egg.go_ovos). Funciona **offline-first** (SQFlite), sincronizando automaticamente com o Firestore assim que a conexão volta, com exportação de comprovantes em PDF e dashboard de vendas filtrável por período. Arquitetura inspirada em MVC, com Provider para gerenciamento de estado.

**HealthCaree** `(em desenvolvimento)` — Software de gestão para clínicas médicas em Flutter + Firebase: agenda, cadastro de pacientes, controle financeiro e relatórios exportáveis em PDF, com interface desktop-first responsiva construída sobre Material Design 3 e um design system próprio (tokens de espaçamento, raio e sombra).

**[Vending Machine](https://github.com/8FTG8/VendingMachine)** — Meu primeiro desafio de desenvolvimento, ainda no 1º semestre da faculdade: simulação de máquina de vendas automática em C++, com listagem de produtos, compra e gerenciamento de estoque.