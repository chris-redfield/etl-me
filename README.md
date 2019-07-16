# Análise ferramentas ETL

busca por uma solução ideal para gestão dos fluxos de dados no Ministério da Economia.

## Critérios de seleção

Obrigatórios
* Agendamento de jobs
* Visualização de estado dos jobs e estatísticas de sucesso
* Versionamento dos jobs
* Fácil manutenção
* Fácil configuração execução de jobs de maneira distribuída e remota
* Trabalhar com qualquer formato de acesso e dados (ex: SFTP, mqeue etc)

Desejáveis
* Não necessitar licença para utilização / manutenção da ferramenta
* Visualização dos pipeline de dados com ordem de execução
* Solução amplamente utilizada na comunidade

## Soluções pesquisadas:

1. SQL Server Integration Services
2. Informatica PowerCenter
3. Pentaho Data Integration
4. Apache Airflow
5. Talend Open Studio

### Sobre os critérios de seleção

-   Agendamento de jobs: A ferramenta possui feature nativa, ou fácil de instalar de agendamento de jobs ?

 - Solução amplamente utilizada na comunidade: baseado em uma pesquisa no google trends em 15/07/2019.

![google-trends](https://raw.githubusercontent.com/chris-redfield/etl-me/master/img/google-trends-etl.PNG)

## Resultados

|                                                           | SQL Server Integration Services | Informatica PowerCenter | Pentaho Data Integration | Apache Airflow | Talend Open Studio |
|-----------------------------------------------------------|---------------------------------|-------------------------|--------------------------|----------------|--------------------|
| Agendamento de jobs                                       | 1                               | 1                       | 1                        | 1              | 1                  |
| Visualização de estado dos jobs e estatísticas de sucesso | 1                               | 1                       | 1                        | 1              | 1                  |
| Fácil versionamento do código dos jobs / nativo           | 0                               | 1                       | 1                        | 1              | 1                  |
| Fácil manutenção                                          | 0                               | 0                       | 0                        | 0              | 0                  |
| Fácil execução de jobs de forma distribuída               | 0                               | 0                       | 1                        | 1              | 0,5                |
| Qualquer formato de acesso e dados                        | 1                               | 1                       | 1                        | 1              | 1                  |
| Não necessitar licença                                    | 0                               | 0                       | 0,25                     | 0,5            | 0,25               |
| Visualização dos pipelines de dados com ordem de execução | 0,5                             | 0,5                     | 0,5                      | 0,5            | 0,5                |
| Comunidade Grande                                         | 0,5                             | 0                       | 0,5                      | 0,5            | 0                  |
| Total                                                     | 4,00                            | 4,50                    | 6,25                     | 6,50           | 5,25               |
|                                                           |                                 |                         |                          |                |                    |



> Written with [StackEdit](https://stackedit.io/).
