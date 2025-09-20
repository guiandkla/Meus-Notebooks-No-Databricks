🚀  **Projetos ETL com PySpark no Databricks**:
----

Este repositório reúne notebooks desenvolvidos no Databricks com foco em processos ETL (Extract, Transform, Load), demonstrando minha experiência prática em Engenharia e Análise de Dados.
Utilizo principalmente PySpark para manipulação e processamento em larga escala, além de SQL para consultas otimizadas e análises exploratórias.

📊 O objetivo é evidenciar minha capacidade de transformar dados crus em informações úteis, aplicando técnicas de limpeza, padronização e enriquecimento de dados:

🛠️ **Habilidades & Ferramentas**:

**PySpark** → Transformações complexas (filtros, agregações, criação de colunas, regras de negócio).

**SQL** → Consultas para ETL, análise exploratória e otimização de pipelines.

**Databricks** → Ambiente colaborativo para desenvolvimento, versionamento e execução escalável.

**Manipulação de Dados** → Limpeza, padronização, tratamento de acentuação, remoção de espaços e conversão de textos.

**Regras de Negócio & Lógica Condicional** → Criação de colunas calculadas e categorização de registros (ex.: classificação de produtos, estratégias de estoque).

📌 **Exemplos**:

![1](https://github.com/user-attachments/assets/a70eb696-3c55-4b1e-b32f-a18a1c765502)
![2](https://github.com/user-attachments/assets/12992259-e675-4bce-bdac-e643117e29df)
Esse código no Databricks está limpando e padronizando os dados de um DataFrame do PySpark. Ele faz basicamente três coisas:

Cria a coluna "Opinião" → classifica os produtos como "O produto está caro" (≥ 300), "O produto está barato" (< 300) ou "Não avaliado" (quando o valor é nulo).

Renomeia colunas → muda os nomes técnicos (ex: order_id) para nomes mais legíveis em português (ex: Id, Produto_Id, Preço, etc.).

Cria a coluna "Estoque" → marca como "Reposição URGENTE" quando a quantidade é menor que 2, e "Estoque Normal" quando é maior ou igual a 2.

👉 Em resumo: ele classifica preços, padroniza nomes de colunas e adiciona uma regra para identificar urgência de estoque.

----

**Outro exemplo** em que está sendo resolvido o "problema" de acentuação que pode ocasionar erros em consultas:

![3](https://github.com/user-attachments/assets/e8951c95-ebbc-4ef4-8d22-338266ea710e)
![4](https://github.com/user-attachments/assets/6efdbafa-d75c-41a0-abaf-f118f813d9e9)
----

🤝 Contato:

💼 LinkedIn: [Guiandkla](https://www.linkedin.com/in/guiandkla)

📢 Obrigado por visitar meu repositório!
