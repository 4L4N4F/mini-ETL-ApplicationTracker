This document describes the fields included in the sample dataset. All data has been anonymized from real job postings collected during the project.

|--------|------|----------|-------------|
| field             | type              | example                                          | description                                              |
| ----------------- | ----------------- | ------------------------------------------------ | -------------------------------------------------------- |
| timestamp         | datetime          | 2025-10-18                                       | date and time when the form was submitted                |
| empresa           | string            | google                                           | company name                                             |
| local_empresa     | string            | porto alegre                                     | city (and optionally state) where the company is located |
| cargo             | string            | analista de dados                                | job title applied for                                    |
| senioridade       | categorical       | pleno                                            | job level or seniority mentioned in the job posting      |
| plataforma        | categorical       | gupy                                             | recruitment platform                                     |
| contrato          | categorical       | clt                                              | type of employment contract                              |
| remuneracao_reais | numeric or string | 5000                                             | reported or estimated salary in brl                      |
| descricao         | text              | "estamos à procura de uma pessoa para..."        | short job description or summary                         |
| skills            | list              | sql, power bi, python                            | key skills or technologies required                      |
| data_post         | date              | 2025-10-10                                       | date when the job was posted                             |
| observacoes       | text              | "contacted recruiter on linkedin"                | personal notes or additional observations                |
| application       | date              | 2025-10-13                                       | date of application submission                           |
| responsabilidades | text              | "responsável por coleta e modelagem de dados..." | responsibilities listed                                  |

