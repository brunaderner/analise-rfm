# Segmentação de Clientes via RFM – O Mercado

O objetivo deste projeto é segmentar a base de clientes da loja "O Mercado" utilizando a metodologia RFM (Recência, Frequência e Valor Monetário), com o intuito de melhorar a compreensão sobre o comportamento dos clientes e apoiar estratégias de marketing e fidelização. A análise foi realizada a partir de dados de transações históricas e informações cadastrais dos clientes, buscando gerar insights acionáveis para a retenção e o aumento do valor de vida dos clientes.

## Objetivo

Realizar uma segmentação da base de clientes da loja "O Mercado" utilizando a metodologia RFM, com a finalidade de apoiar a criação de campanhas de marketing, programas de fidelização e ações de retenção focadas nos perfis mais estratégicos.

## Tecnologias e Ambiente de Desenvolvimento

- **Plataformas:** Google Sheets, Looker Studio, Google Slides
- **Ferramentas:** 
  - Fórmulas avançadas no Google Sheets (IMPORTRANGE, QUERY, PROCV, FILTER, CORRESP)
  - Visualizações dinâmicas no Looker Studio
  - Apresentação de resultados no Google Apresentações
- **Ambiente de Desenvolvimento:** Google Workspace

## Estrutura

- **dados-primarios/**: Planilhas originais utilizadas para análise
- **dataset/**: Compilação e transformação dos dados em planilhas integradas
- **dashboard/**: Dashboard interativo desenvolvido no Looker Studio
- **presentation/**: Apresentação final com principais resultados
- **ficha-tecnica/**: Documento técnico com a descrição detalhada do projeto

## Arquivos do Projeto

- Link para a planilha de dados: [Google Sheets](https://docs.google.com/spreadsheets/d/1_E2wwfR9YxtgV2mbxb2xPde1LLlZ5F9Zm2hjZDqQlSQ/edit?usp=sharing)
- Link para o dashboard interativo: [Looker Studio](https://lookerstudio.google.com/reporting/ff9d9626-041a-447c-a0ff-dbbe6034c224)
- Link para a apresentação final: [Google Slides](bruna-derner.pdf)

## Ficha Técnica
- Acesse a documentação [Google Documentos](ficha-tecnica-bruna-derner.pdf)
### Metodologia

- **Integração:** 
  - Os dados foram importados diretamente das planilhas originais utilizando a função `IMPORTRANGE`.
  - As tabelas de clientes, transações e resumo de compras foram unificadas utilizando `FILTER`, `CORRESP` e `PROCV`, mantendo apenas id_clientes comum entre tabelas.

- **Limpeza e Tratamento:** 
  - Remoção de valores nulos e outliers.
  - Remoção de registros duplicados na base de resumo de compras.
  - Análise exploratória para validação da qualidade dos dados.

- **Criação de Variáveis:** 
  - Variáveis derivadas como idade, faixa etária, faixa salarial, filhos, período de compra, total gasto, frequência de compras e ticket médio.

- **Segmentação RFM:**
  - Definição dos quartis para classificação de Recência, Frequência e Valor Monetário.
  - Atribuição de scores de 1 a 5 para cada dimensão.
  - Criação de segmentos estratégicos como Clientes Fiéis, Clientes em Risco, Grandes Gastadores, entre outros.

- **Visualização dos Dados:** 
  - Desenvolvimento de dashboard no Google Sheets e no Looker Studio, integrando todas as informações em gráficos, scorecards e tabelas dinâmicas.

## Principais Resultados

- **Clientes de Alto Valor:**  
  - 56% da base está concentrada em três segmentos principais (Fiéis, Fiéis em Potencial e Em Risco), representando mais de 86% da receita.

- **Perfil dos Clientes:**  
  - Maioria com ensino superior completo ou pós-graduação.
  - Faixa etária predominante entre 45 e 54 anos.
  - Renda média entre R$30k e R$90k anuais.

- **Comportamento de Compra:**  
  - Forte preferência por compras presenciais na loja.
  - Vinho representa o principal produto consumido.

As análises permitem que a loja “O Mercado” direcione suas estratégias de marketing para públicos mais rentáveis e implemente programas de fidelização e retenção mais eficazes.

## Vídeo de Apresentação

Assista à apresentação completa no Loom:

▶️ [Assistir vídeo](https://www.loom.com/share/19a970bcbc9146f3aca84aa4c87f0a0d?sid=7a580ea5-8a83-47fb-a3ba-42cd74f21c3e)

## Autora

**Bruna Derner**  
Analista de Dados
[Linkedin](https://www.linkedin.com/in/bruna-derner/)
