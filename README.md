# Criando um Relatório de Vendas com Power BI


![Captura de tela 2023-10-11 190530](https://github.com/sympathetic-s/Desafio-DIO/assets/104389913/4333b09e-26ef-45a9-bb15-aa63948abf0c)

![Captura de tela 2023-10-11 190602](https://github.com/sympathetic-s/Desafio-DIO/assets/104389913/ed7c532b-cf01-4c63-92ad-893f7bd61208)

# Processando e Tratando dados abertos com MySQL desafio DIO com Power BI

![image](https://github.com/Tiagoconect/Meus_Relatorias_Com_Power_BI/assets/109769812/9a971f9d-ceec-4b68-bd86-a6fd9009ab69)

![image](https://github.com/Tiagoconect/Meus_Relatorias_Com_Power_BI/assets/109769812/450427cf-d0e1-4acd-a6cf-7b9ad99213ab)

## Descrições e Etapas do Desafio dio de Projeto Prático

Descrição do desafio módulo 3 – Processamento de Dados Simplificado com Power BI

1. Criação de uma instância na Azure para MySQL

2. Criar o Banco de dados com base disponível no github

3. Integração do Power BI com MySQL no Azure

4. Verificar problemas na base a fim de realizar a transformação dos dados

Diretrizes para transformação dos dados

1. Verifique os cabeçalhos e tipos de dados

2. Modifique os valores monetários para o tipo double preciso

3. Verifique a existência dos nulos e analise a remoção

4. Os employees com nulos em Super_ssn podem ser os gerentes. Verifique se há algum colaborador sem gerente

5. Verifique se há algum departamento sem gerente

6. Se houver departamento sem gerente, suponha que você possui os dados e preencha as lacunas

7. Verifique o número de horas dos projetos

8. Separar colunas complexas

9. Mesclar consultas employee e departament para criar uma tabela employee com o nome dos departamentos associados aos colaboradores. A mescla terá como base a tabela employee. Fique atento, essa informação influencia no tipo de junção

10. Neste processo elimine as colunas desnecessárias.

11. Realize a junção dos colaboradores e respectivos nomes dos gerentes . Isso pode ser feito com consulta SQL ou pela mescla de tabelas com Power BI. Caso utilize SQL, especifique no README a query utilizada no processo.

12. Mescle as colunas de Nome e Sobrenome para ter apenas uma coluna definindo os nomes dos colaboradores

13. Mescle os nomes de departamentos e localização. Isso fará que cada combinação departamento-local seja único. Isso irá auxiliar na criação do modelo estrela em um módulo futuro.





