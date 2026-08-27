# Rubens Duarte Conceicao

Senior Data Analyst, com foco em Power BI, SQL, Python e automacao de dados.

Mais de 10 anos em TI, os ultimos 5 focados em BI, engenharia de dados e automacao. Trabalho na construcao de dashboards, pipelines de dados e produtos digitais, sempre tentando unir a parte tecnica a uma leitura clara pra quem vai consumir a informacao no dia a dia.

Contato e demais informacoes no perfil do GitHub.

---

## Projetos

### AlugaPerto: marketplace de aluguel de equipamentos

App de aluguel de equipamentos entre pessoas, ja em producao na Google Play. Construido com React Native/Expo Router no front, Firebase (Auth, Firestore, Storage, Functions) e um backend Node.js rodando na Railway.

Entre as partes que desenvolvi: um wizard de cadastro de equipamento em tres etapas, sistema de avaliacao entre as duas pontas do aluguel, chat em tempo real e notificacoes push. No pagamento, integrei um modelo de pre-autorizacao (caucao) com as regras de seguranca do banco. Tambem cuidei da parte juridica do produto: termos de uso, politica de privacidade, contrato eletronico e o registro da marca.

### Dashboards de BI para operacao industrial

Desenvolvo e mantenho os dashboards de Power BI usados nas operacoes de moagem de cana-de-acucar em tres unidades. O trabalho passa por medidas DAX mais complexas (ajuste de fuso horario, logica de metas proporcionais, indicadores de status por cor), modelagem em Power Query, analise de views SQL no Oracle, modelos dbt (staging e marts) e scripts de ETL em PySpark.

Alguns dos entregaveis: o boletim de moagem com uma pagina de recordes historicos, um relatorio de performance de colhedoras e um painel de frota e equipamentos.

### Sistema de gestao para igreja

App de gestao para uma igreja de cerca de 200 membros, divididos em 7 Grupos de Crescimento. Antes de fechar o escopo, fiz uma pesquisa de validacao de mercado com um framework de seis etapas, junto com o cliente.

A primeira fase ficou focada em controle financeiro (dizimos, ofertas, despesas) e registro de atas de culto. O escopo completo prevê cadastro de membros, gestao dos grupos, mural de avisos, aniversariantes, um modulo infantil e um dashboard gerencial.

### Validacao de SaaS para gestao de eventos e parceiros

Pesquisa de mercado para uma ideia de SaaS voltada a organizacao de eventos, com foco em como o organizador controla os pagamentos de parceiros e expositores. O levantamento mostrou pouca concorrencia direta nesse nicho especifico.

A partir disso, desenhei a estrategia de validacao, separando dor real de hipotese, e a decisao de lancar fechado antes de abrir ao publico. A arquitetura do banco ja foi pensada como multi-tenant desde o inicio.

### App de consulta de pedagios free flow

Planejamento de um app para consultar, pela placa do veiculo, se ha cobrancas pendentes em pedagios free flow no Brasil. A arquitetura definida usa React Native/Expo no front e Node.js na Railway no backend, integrando com uma API agregadora de concessionarias (autenticacao HMAC-SHA256, webhooks).

Um diferencial pensado para o produto: notificacoes push avisando quando surge uma cobranca pendente na placa do usuario.

---

## Stack tecnica

Power BI, DAX, Power Query, SQL (Oracle), Python, PySpark, dbt, React Native, Firebase, Node.js
