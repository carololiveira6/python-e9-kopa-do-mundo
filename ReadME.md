## **Table of Contents**
- [E9 - Kopa do mundo](https://npepa32v9l.execute-api.us-east-1.amazonaws.com/v2/?project_id=19989138&filename=python/outubro-20/3a_e_01_kopa_do_mundo.html&ref=master#mcetoc_1evd883pc0)
- [Entrega](https://npepa32v9l.execute-api.us-east-1.amazonaws.com/v2/?project_id=19989138&filename=python/outubro-20/3a_e_01_kopa_do_mundo.html&ref=master#mcetoc_1esj4slvm0)
- [Tabela kopas](https://npepa32v9l.execute-api.us-east-1.amazonaws.com/v2/?project_id=19989138&filename=python/outubro-20/3a_e_01_kopa_do_mundo.html&ref=master#mcetoc_1evd883pc0)
- [Tabela estadios](https://npepa32v9l.execute-api.us-east-1.amazonaws.com/v2/?project_id=19989138&filename=python/outubro-20/3a_e_01_kopa_do_mundo.html&ref=master#mcetoc_1evd883pc0)
- [Entregáveis](https://npepa32v9l.execute-api.us-east-1.amazonaws.com/v2/?project_id=19989138&filename=python/outubro-20/3a_e_01_kopa_do_mundo.html&ref=master#mcetoc_1egvoav555j) 
  - [Repositório](https://npepa32v9l.execute-api.us-east-1.amazonaws.com/v2/?project_id=19989138&filename=python/outubro-20/3a_e_01_kopa_do_mundo.html&ref=master#mcetoc_1egvrpv6k1l4)
- [Critérios de aceitação](https://npepa32v9l.execute-api.us-east-1.amazonaws.com/v2/?project_id=19989138&filename=python/outubro-20/3a_e_01_kopa_do_mundo.html&ref=master#mcetoc_1esj6ecle3)
# **E9 - Kopa do mundo**
# **Entrega**
- Esta é uma entrega que você treinará a utilização básica de uma linguagem de banco de dados relacional (SQL), tanto quanto seu reflexo no banco de dados (Postgres). Siga este [snippet](https://gitlab.com/-/snippets/2123773) para fazer a atividade.
-----
# **Tabela kopas**
#### **Parte 1**
- Crie um banco de dados chamado kopa\_db
- Conecte seu banco de dados ao seu SGBD de preferência
- Abra o editor SQL para criarmos as queries
- Crie uma tabela chamada kopas com os seguintes valores: 
  - **id** -> Deve ser uma identificação única (serial)
  - **selecao** -> Deve ter no máximo 128 caracteres e ser único no banco de dados
  - **qnt\_copas** -> deve ser um número inteiro
- Agora iremos inserir alguns dados na nossa tabela, utilize esse [snippet](https://gitlab.com/-/snippets/2123773) para popular seu banco de dados
- Faremos uma seleção dos campos selecao e qnt\_copas da nossa tabela kopas
- Se você tem um conhecimento mínimo sobre copas do mundo, irá reparar que temos dois erros nesses dados, o primeiro deles é que a Alemanha não possui 5 copas do mundo (ainda não são penta, somente o Brasil) e o Japão também não possui nenhuma copa do mundo, portanto, vamos fazer as devidas alterações: 
  - Atualize a coluna qnt\_copas da Alemanha para 4
  - Delete o Japão da tabela
- Faremos uma nova seleção, mas agora selecionaremos todos os dados da tabela kopas. (Note se suas atualizações foram realizadas)


#### **Parte 2**
- Agora vamos adicionar uma coluna na nossa tabela que irá representar a **pontuação total** entre partidas jogadas em todas copas do mundo pela determinada seleção: 
  - Vamos adicionar uma coluna chamada pts que será um número inteiro na nossa tabela kopas
  - Nos basearemos na parte 2 do nosso snippet para fazer as inserções de acordo com o nome das seleções
  - Faça uma nova seleção para capturar todos os dados da tabela kopas.
# **Tabela estadios**
- Crie uma tabela estadios com as seguintes colunas: 
  - **id** -> Precisa ser um serial único
  - **edicao** -> Texto sem limitação de carácteres
  - **ano** -> Texto com no máximo 4 carácteres
  - **estadio** -> Texto sem limitação de carácteres
  - **local** -> Texto com no máximo 128 carácteres
  - **publico\_pagante** -> Número inteiro
- Acesse a parte 1 do snippet logo abaixo da divisão para estadios e popule o banco de dados com as informações disponíveis no snippet.
- Iremos criar algumas seleções agora: 
  - Selecione todas as colunas da tabela estadios 
  - Selecione todas as colunas da tabela estadios onde o público pagante for **maior** que 100.000
  - Selecione todas as colunas da tabela estadios onde o público pagante for **maior** que 50.000 e **menor** que 100.000
  - Selecione todas as colunas da tabela estadios onde a **última letra** do estádio seja "**y**"
- Colocamos os anos como tipo de dado de texto, vamos alterar a coluna ano da nossa tabela para um tipo de dado inteiro, e vamos transformar todos os valores anteriores em números inteiros.
- Faça novamente uma seleção de todas as colunas da tabela estadios
- **Para realizar a entrega da atividade, copie todas as suas queries e cole em um arquivo chamado queries.sql e suba ele para o gitlab**
## -----
# **Entregáveis**
## **Repositório**
- Link do **repositório** do **GitLab**
- **Código fonte:** 
  - arquivos com a mesma estrutura apresentada no inicio do projeto.
- **Privacidade** 
  - Incluir **ka-br-out-2020-correcoes** como reporter.
-----
# **Critérios de aceitação**

|5|Arquivo queries.sql|Feito a conferência de queries|**Todas devem estar de acordo com o solicitado**|
| :-: | :-: | :-: | :-: |


**Boa diversão, devs 🦄**






