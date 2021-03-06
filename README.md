![image](https://scontent.fudi1-1.fna.fbcdn.net/v/t1.6435-9/159228906_3690079687713312_5035028843487831689_n.png?_nc_cat=103&ccb=1-3&_nc_sid=e3f864&_nc_eui2=AeGxu7tQmrCVud2XV6HZGYLSRkoGovk4dmVGSgai-Th2ZXD5wS-ueGqt9aNhGL9Et1o&_nc_ohc=iD7uFTi5lIYAX8Iohin&_nc_ht=scontent.fudi1-1.fna&oh=f23b72635179e9c304be0b3999930447&oe=60EC6AC5)

# Projeto Final de Spark

O projeto foi dividido em dois níveis, básico e avançado.

Recomendo fortemente fazer primeiro o básico e se sobrar tempo, pode aventurar no avançado.

Os exercícios podem ser feitos em qualquer linguagem e todas as questões são bem abertas, tendo várias formas de serem realizadas e interpretadas, pois a idéia é não termos projetos iguais.

O projeto deve estar no github.com, a forma de organizar o conteúdo é por sua conta, caso nunca tenha usado, este já é seu primeiro desafio.

Ao final do projeto você precisa preencher o formulário com o seu nome completo, email utilizado no treinamento e o link do github do seu projeto.

<br>
<br>
<br>

# Notebooks

- [Nivel Basico](./Notebook/nivel_basico.ipynb)
- Nivel Avançado

<br>
<br>
<br>

# Campanha Nacional de Vacinação contra Covid-19

## **Nível Básico**:
Dados: [PAINEL COVID](https://mobileapps.saude.gov.br/esusvepi/files/unAFkcaNDeXajurGB7LChj8SgQYS2ptm/04bd3419b22b9cc5c6efac2c6528100d_HIST_PAINEL_COVIDBR_06jul2021.rar)

### Referência das Visualizações:

#### Site: https://covid.saude.gov.br/

#### Guia do Site: Painel Geral

## **Etapas**
1. Enviar os dados para o hdfs
2. Otimizar todos os dados do hdfs para uma tabela Hive particionada por município.
3. Criar as 3 vizualizações pelo Spark com os dados enviados para o HDFS
4. Salvar a primeira visualização como tabela Hive
5. Salvar a segunda visualização com formato parquet e compressão snappy
6. Salvar a terceira visualização em um tópico no Kafka
7. Criar a visualização pelo Spark com os dados enviados para o HDFS:

# Nível Avançado:

Replicar as visualizações do site “https://covid.saude.gov.br/”, porém acessando diretamente a API de Elastic.

Link oficial para todas as informações: https://opendatasus.saude.gov.br/dataset/covid-19-vacinacao

### Informações para se conectar ao cluster: 

• URL https://imunizacao-es.saude.gov.br/desc-imunizacao

• Nome do índice: desc-imunizacao

• Credenciais de acesso

    o Usuário: xxxx
    o Senha: xxxxx

## Links utéis para a resolução do problema:

• Consumo do API: https://opendatasus.saude.gov.br/dataset/b772ee55-07cd-44d8-958fb12edd004e0b/resource/5916b3a4-81e7-4ad5-adb6-b884ff198dc1/download/manual_api_vacina_covid-19.pdf

## Conexão do Spark com Elastic:

- https://www.elastic.co/guide/en/elasticsearch/hadoop/current/spark.html
- https://docs.databricks.com/data/data-sources/elasticsearch.html#elasticsearchnotebook
- https://github.com/elastic/elasticsearch-hadoop
- https://www.elastic.co/guide/en/elasticsearch/hadoop/current/configuration.html

## Instalar Dependências:
- https://www.elastic.co/guide/en/elasticsearch/hadoop/current/install.html
