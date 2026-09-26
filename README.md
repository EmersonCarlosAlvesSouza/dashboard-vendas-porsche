# 🏎️ Dashboard de Vendas Porsche com Inteligência Artificial

Este repositório contém o projeto final desenvolvido na trilha de Excel e IA da plataforma DIO. O objetivo deste laboratório foi extrair dados sanitizados de uma planilha com 100 registros de vendas da Porsche e, utilizando Inteligência Artificial Generativa, construir uma aplicação web interativa (`index.html`) publicada em ambiente produtivo.

## 🔗 Endereço da Dashboard Publicada
Acesse o painel online e interativo aqui: 
👉 [https://github.io](https://github.io)

## 📊 Perguntas de Negócio Escolhidas
Para direcionar a construção dos gráficos e evitar um mero amontoado de dados sem contexto, definimos as seguintes perguntas estratégicas:
1. **Qual é o faturamento total acumulado e o preço médio por modelo?** (Essencial para entender a receita macro e quais modelos geram maior ticket).
2. **Como as vendas estão distribuídas geograficamente por Cidade/Estado?** (Identifica as praças com maior densidade de compradores de alta renda).
3. **Qual é a preferência dos clientes em relação aos Métodos de Pagamento?** (Auxilia o setor financeiro a otimizar taxas e fluxos de caixa).

## 🛠️ Tratamento da Base de Dados e Prompt Engenharia
- **Tratamento:** A base bruta passou por higienização para remoção de valores nulos e dados marcados como `INVALID`. Colunas de preço e ano foram devidamente convertidas em formatos numéricos puros.
- **Abordagem de IA:** Foi utilizado o ChatGPT estruturando prompts contextuais para codificar uma estrutura de arquivo único contendo HTML, CSS (Tailwind) e JavaScript (Chart.js), garantindo cartões de KPI superiores, gráficos de rosca e barras, além de segmentadores de filtros dinâmicos por modelo e cidade.
