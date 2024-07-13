#Projeto Real de Análise de Dados 

🔎Objetivo Este projeto visa a análise e a migração dos modelos de dados de uma empresa, atualmente armazenados em planilhas do Excel, para um banco de dados MySQL utilizando técnicas de data warehouse dimensionais. O objetivo principal é centralizar e estruturar os dados de forma a facilitar consultas analíticas e relatórios.

🔎Motivação
Muitas empresas inicialmente utilizam planilhas do Excel para armazenar dados de diferentes áreas, como vendas, finanças, recursos humanos, entre outros. No entanto, conforme a empresa cresce, as limitações das planilhas tornam-se evidentes, dificultando a integração e a análise dos dados de forma eficiente. A migração para um banco de dados relacional como o MySQL, utilizando modelos de data warehouse dimensionais ou até mesmo transacionais, permite uma melhor organização dos dados, facilitando a consulta e extração de informações estratégicas e contribuindo para a segurança das informações da empresa.

🔎Metodologia
📌Levantamento de Requisitos: Entendimento detalhado dos tipos de dados, formatos e estruturas das planilhas existentes.
📌Modelagem Dimensional: Definição de um modelo dimensional que melhor represente os processos e entidades da empresa, utilizando conceitos como fatos (medidas) e dimensões (contexto).
Extração, Transformação e Carga (ETL):

📌Extração: Coleta dos dados das planilhas do Excel de acordo com as necessidades definidas.
Transformação: Limpeza, normalização e estruturação dos dados para o formato adequado ao modelo dimensional. Carga: Carregamento dos dados transformados no banco de dados MySQL.

📌Desenvolvimento da Infraestrutura:
Configuração do ambiente MySQL para receber os dados. Desenvolvimento de scripts SQL para criação de tabelas, índices e relacionamentos conforme o modelo dimensional definido. Validação e Testes: Verificação da integridade dos dados após a carga no MySQL, garantindo que todas as transformações foram aplicadas corretamente e que os dados estão consistentes.

📌Desenvolvimento de Relatórios: Implementação de consultas SQL para extração de informações estratégicas e desenvolvimento de relatórios utilizando ferramentas de visualização de dados como Power BI ou Tableau.
🔎Resultados Esperados
Centralização dos Dados: Todos os dados da empresa estarão centralizados em um único local, facilitando o acesso e a manutenção. Facilidade de Consulta: Consultas analíticas poderão ser realizadas de maneira mais eficiente e rápida. Melhoria na Tomada de Decisão: Informações estratégicas estarão mais acessíveis, auxiliando na tomada de decisões mais embasadas e precisas.

🔎Conclusão
A migração dos modelos de dados do Excel para o MySQL utilizando técnicas de data warehouse dimensionais representa um passo importante para a modernização da infraestrutura de dados da empresa. Este projeto não apenas melhora a eficiência operacional, mas também proporciona uma base sólida para análises mais profundas e estratégicas, alinhadas com os objetivos de negócio da organização.

💻 Tecnologias: DB.Schema para modelagem e datawarehouse;
                 MySQL para conectarmos a modelagem e tranformar e carregar os novos dados;
