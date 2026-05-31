# Projeto: Caderno Temático - Domínio da Organização Financeira

## Contexto e Objetivos
Este projeto foi desenvolvido com o intuito de estruturar um guia prático e eficiente sobre **Organização Financeira Pessoal**. Utilizando o **NotebookLM** como ferramenta central de curadoria e síntese, o objetivo é transformar conhecimentos dispersos em um sistema lógico de gestão de recursos.

**Objetivos de estudo:**
* Compreender os pilares da educação financeira (orçamento, reserva de emergência e investimentos).
* Identificar métodos práticos para o controle de gastos diários.
* Estabelecer uma metodologia de revisão financeira recorrente.

---

## Curadoria de Fontes
Para alimentar o NotebookLM, selecionei fontes que abrangem desde a base teórica até a aplicação prática:

1. **Guia de Educação Financeira (Banco Central do Brasil):** [Link para o PDF do BCB](https://www.bcb.gov.br/cidadaniafinanceira/educacaofinanceira)
2. **Artigo sobre a Regra 50-30-20 (Investopedia):** [Link do artigo](https://www.investopedia.com/ask/answers/022916/what-50-30-20-budget-rule.asp)
3. **Princípios Básicos de Economia Doméstica:** [link do artigo](https://conteudos.xpi.com.br/aprenda-a-investir/relatorios/economia-domestica/)

---

## Engenharia de Prompts e "Cicatrizes"
*O processo de extração de conhecimento não foi linear. Abaixo, documento o raciocínio e o refinamento dos prompts.*

### 1. Tentativa Inicial (Prompt Genérico)
* **Prompt:** "Como organizar minhas finanças?"
* **Resultado:** Respostas superficiais e genéricas.

### 2. Refinamento (Prompt Estruturado - "O Pulo do Gato")
* **Prompt:** "Com base nos documentos carregados, crie um plano de ação para alguém que deseja sair das dívidas e começar a investir. Considere a Regra 50-30-20 como base. Organize em passos semanais."
* **Resultado:** Resposta muito mais assertiva, criando um cronograma aplicável.

### 3. Troubleshooting (Cicatrizes)
* **Problema:** A IA tendia a misturar conceitos de finanças empresariais com finanças pessoais.
* **Solução:** Adicionei a restrição nos prompts: *"Limite as sugestões estritamente ao contexto de economia doméstica, ignorando termos técnicos de contabilidade corporativa."*

---

## Miniguia de Estudo (Entrega Final)

### 1. Resumos Estruturados
* **Fundamento 50-30-20:** 50% necessidades básicas, 30% desejos pessoais, 20% investimentos/dívidas.
* **Reserva de Emergência:** Deve cobrir de 6 a 12 meses do custo de vida.
* **Controle:** O uso de ferramentas (planilhas ou apps) é menos importante do que a *frequência* de registro.

### 2. Glossário de Conceitos
* **Ativos:** Bens ou direitos que geram renda.
* **Passivos:** Obrigações financeiras ou dívidas que consomem recursos.
* **Inflação:** A perda do poder de compra ao longo do tempo; deve ser considerada em investimentos de longo prazo.

### 3. Prompts Reutilizáveis
> "Atue como um mentor financeiro. Com base no meu resumo atual, analise se o meu método de alocação de verbas está seguindo a regra 50-30-20 e sugira 3 ajustes para otimizar minha poupança mensal."

> "Crie um checklist de revisão financeira mensal para garantir que não estou ultrapassando meu orçamento em categorias de gastos variáveis."

---
*Projeto desenvolvido como parte do desafio da DIO para a formação de especialistas em IAs Generativas.*
