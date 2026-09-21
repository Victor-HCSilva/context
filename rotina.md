# Plano de Prioridades e Rotina — Ciclo de 6–8 Semanas



## 1. Objetivo do ciclo



Fortalecer a base profissional com **Go como principal linguagem de estudo**, mantendo Python como linguagem de trabalho já conhecida e ampliando gradualmente a capacidade de atuar em backend.



O objetivo não é dominar Go, mas chegar a um nível **básico → funcional/intermediário**, suficiente para compreender, desenvolver e manter aplicações backend.



---



## 2. Prioridades



### Prioridade principal — Go + Backend



Foco técnico principal do ciclo.



Conteúdos:



* Sintaxe e fundamentos de Go

* Estrutura de projetos

* Packages

* HTTP

* Rotas e handlers

* JSON

* CRUD

* Banco de dados

* Tratamento de erros

* Validação

* Testes

* Clientes HTTP

* Concorrência básica

* Docker



### Projeto principal



Desenvolver uma pequena **REST API em Go**, inicialmente um sistema de To-do.



Estrutura básica:



* ID

* Título

* Descrição

* Status/conclusão

* CRUD completo

* Persistência em banco

* Validação

* Tratamento de erros

* Testes

* Docker



A autenticação não será prioridade inicialmente. Ela poderá ser adicionada posteriormente, caso o projeto esteja consolidado.



---



## 3. Metodologia de estudo



A lógica será:



**Eu → documentação → tento implementar → travo → uso IA → entendo → implemento.**



A IA será utilizada principalmente como:



* Tutor

* Debugger

* Explicador de conceitos

* Auxílio para investigar erros



Evitar copiar código sem compreender o que está sendo feito.



O objetivo é que o código produzido continue sendo, de fato, resultado do aprendizado.



---



## 4. Python



Python continua como uma **linguagem de trabalho**, não como foco principal de estudo neste ciclo.



O conhecimento existente em:



* Python

* Django

* FastAPI

* Backend



será utilizado como base de comparação para compreender conceitos em Go.



Não será necessário interromper o aprendizado de Go para buscar domínio avançado de Python.



---



## 5. Oratória



A oratória será integrada ao estudo técnico.



Após estudar algum conceito, realizar eventualmente uma explicação de aproximadamente **5 minutos**, como se estivesse explicando para outra pessoa.



Exemplos:



* "O que é um handler?"

* "Como funciona uma requisição HTTP em Go?"

* "Por que usar uma interface?"

* "Como esse CRUD funciona?"



Isso transforma parte do estudo técnico em exercício de comunicação.



---



## 6. Inglês



Manutenção em baixo volume.



O objetivo neste ciclo é **não perder contato com o idioma**, sem permitir que ele concorra com a prioridade principal.



---



## 7. Exercício físico



Exercício como **rotina de manutenção**, e não como um projeto cognitivo adicional.



Meta:



**4 sessões por semana.**



Os treinos podem ser distribuídos conforme os horários realmente disponíveis e conforme recuperação/disposição.



Não é necessário fixar um horário específico para todos os dias. Quando houver uma janela livre adequada, o exercício pode ser realizado nela; quando aquele horário estiver ocupado ou não for adequado, o treino pode ser deslocado para outra janela disponível.



Distribuição de referência:



* Domingo

* Segunda

* Quarta

* Sexta



A prioridade é manter a frequência semanal sem fazer o exercício competir desnecessariamente com os blocos principais de estudo.



---



## 8. Cursos variados



Cursos secundários, como:



* Primeiros socorros

* Mini cursos

* Certificações complementares



ficam em uma **lista de espera**.



Eles podem ser realizados quando houver espaço, mas não devem competir com Go, faculdade, descanso e demais compromissos principais.



---



## 9. React Native / Expo



Fica como próxima expansão horizontal.



A ideia é futuramente aproveitar a base de backend para desenvolver capacidade de criação de aplicações mobile.



Não será prioridade durante a fase principal de Go.



---



## 10. Laboratório futuro de IA



Uma ideia futura é integrar IA ao sistema pessoal existente.



Possibilidades arquiteturais:



**Modelo → Function Calling → Go → Django → Banco**



ou:



**Modelo → MCP → Go → Django → Banco**



Possíveis ferramentas:



* `criar_anotacao`

* `criar_evento`



Esse laboratório pode posteriormente envolver:



* Function Calling

* MCP

* Ollama/modelos locais

* API em Go

* Integração com Django

* Autenticação

* Rate limiting



Porém, **não faz parte do escopo atual**.



---



# 11. Ciclo técnico semanal



### Segunda — Aprender



**08:30–11:00**



Estudo de conceitos novos de Go.



Exemplo:



* HTTP

* Structs

* Interfaces

* Packages

* Banco de dados



---



### Quarta — Praticar



**08:30–11:00**



Transformar o conteúdo estudado em código.



Exemplo:



* Implementar endpoint

* Criar handler

* Fazer conexão com banco

* Implementar alguma parte do CRUD



---



### Sexta — Produzir



**08:30–11:00**



Aplicar o conhecimento diretamente no projeto.



Objetivo: fazer o projeto avançar.



---



### Domingo — Consolidar



**09:00–12:00**



Revisar, corrigir e consolidar o que foi aprendido durante a semana.



Principalmente:



* Projeto

* Revisão dos conceitos

* Resolução de pendências

* Organização da próxima semana



Também pode ser utilizado como principal bloco de desenvolvimento do projeto.



---



## 12. Demais compromissos



### Terça



**16:50–18:10**



Inglês.



Após **20:00**, faculdade/obrigações.



### Quinta



Após **20:00**, faculdade/obrigações.



Se houver energia, apenas revisão leve.



### Sexta



Após **20:00**, faculdade/obrigações.



### Sábado



Curso técnico online.



---



# 13. Regra para semanas ruins



Quando a semana estiver comprometida por faculdade, provas, obrigações, cansaço ou problemas pessoais:



1. Faculdade/obrigações e sono vêm primeiro.

2. Manter pelo menos **um bloco técnico** quando possível.

3. Inglês, oratória e exercício entram em modo de manutenção.

4. Cursos secundários podem ser completamente ignorados.

5. Não criar uma "dívida" para compensar depois.



Uma semana ruim não deve gerar uma segunda semana ruim por excesso de compensação.



---



# 14. Ordem inicial do projeto em Go



### Etapa 1 — Ambiente



* Instalação

* `go mod`

* Estrutura básica

* Executar aplicação



### Etapa 2 — HTTP



* Servidor

* Rotas

* Handlers

* Request/Response

* JSON



### Etapa 3 — CRUD em memória



* Criar

* Listar

* Buscar

* Atualizar

* Excluir



### Etapa 4 — Banco de dados



* Conexão

* Modelagem

* Queries

* Persistência



### Etapa 5 — Qualidade



* Validação

* Erros

* Testes

* Organização do código



### Etapa 6 — Docker



* Dockerfile

* Containerização

* Execução da API



Depois disso, outras funcionalidades podem ser adicionadas conforme necessidade.



---



# 15. Resultado esperado ao final do ciclo



Ao final das 6–8 semanas, o objetivo é ter:



**Go básico → Go funcional para backend**



e não domínio completo da linguagem.



Além disso:



* Uma API REST funcional em Go

* Persistência em banco

* Testes básicos

* Docker

* Maior familiaridade com a arquitetura backend em Go

* Capacidade de explicar tecnicamente aquilo que foi desenvolvido

* Python preservado como competência de trabalho

* Exercício mantido como rotina

* Inglês mantido em contato regular



---



# 16. Visão geral das prioridades



| Área                            | Papel no ciclo                      |

| ------------------------------- | ----------------------------------- |

| **Go + Backend**                | Principal foco                      |

| **Projeto REST API**            | Aplicação prática principal         |

| **Oratória**                    | Integrada ao estudo técnico         |

| **Python**                      | Manutenção / linguagem de trabalho  |

| **Inglês**                      | Manutenção                          |

| **Exercício**                   | Rotina, 4x/semana, horário flexível |

| **Cursos variados**             | Lista de espera                     |

| **React Native / Expo**         | Próxima expansão                    |

| **IA / Function Calling / MCP** | Laboratório futuro                  |



**Regra central:** construir profundidade em backend sem tentar desenvolver todas as áreas simultaneamente.
