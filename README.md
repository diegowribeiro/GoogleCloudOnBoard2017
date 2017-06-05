# Google CloudOn Board 2017 - ***Construcao...

Participei do evento #CloudOnboard do Google que aconteceu dia 02/06/2017 na Alianz Parque e o objetivo deste evento foi trazer as novidades, apresentar os recursos e os ponto fortes da Nuvem do Google.

O evento foi incrivel, teve algumas falhas no credenciamento e organizacao para as refeicoes porem nada disso ofuscou o quao grandioso foi o evento e principalmente a forma que se deu. Os palestrante conduziram o evento de forma incrivel, souberam manter a dinamica, a didadica funcionou e apesar de estar ali um dia todo sentado, nao foi nem um pouco cansativo ou chato.

As novidades que a Google apresentou eu particularmente fiquei impressionado, a intencao nao e comparar o Google Cloud com AWS ou AZURE e sim comentar sobre os destaques.

O Evento iniciou com os novos data center que serao entregues ainda esse ano 2017, serao pelo menos 9 espalhados pelo mundo inclusive um no Brasil, mais precisamente em Sao Paulo. So nesse inicio ja deu para ter a ideia do que vem pela frente, com certeza a Google vem muito forte para o mercado de Cloud nos proximos anos.

![regioes](https://cloud.githubusercontent.com/assets/24530268/26766563/b3ba9eb0-496a-11e7-9239-d1383be63330.png)


Outra grande inovacao esta no sistema de precificacao, a bilhetagem ocorre por minuto de utiilizacao e nao por hora cheia ou seja algumas situacoes ou necessidades que o servico nao precisa estar sempre ativo a economia que pode gerar a longo prazo e muito grande. Existe um sistema de desconto que quanto mais voce utiliza, mais desconto se obtem de forma automatica e pode ser visto atraves do painel ou seja voce nao precisa reservar uma Vm por exemplo de 1 a 3 anos e pagar antecipadamente para obter desconto.

As configuracoes de VM's sao customizaveis, sabe aqueles casos quandoo precisa criar um servidor porem ao escolher o tipo de configuracao "medium" pode nao suportar e a "large" vai acabar sobrando muito recurso e por consequencia ira pagar mais por isso? entao com esse modelo voce pode personalizar todas as configuracoes de sua VM conforme necessidade.

Com essas inovacoes de precificacao e configuracao de VM, e possivel obter descontos interessantes. A seguir os destaques de recursos e funcionalidades.

Projetos 
Um recurso muito interessante e a possibilidade de criar projetos dentro da conta, desta forma fica muito facil gerenciar os projetos em andamento a bilhetagem separada de acordo com o projeto e tambem os acessos e possivel chegar uma granularidade interessante.

![projetos](https://cloud.githubusercontent.com/assets/24530268/26782416/ed7e0556-49c9-11e7-877a-8814367ad6c2.png)

APP Engine
E uma Plataforma como servico(Paas) para criar aplicativos web escalaveis e back-end moveis, com runtimes "gerenciados" suporte as principais linguagens de programacao(Java, Python, GO e etc) muito pratica e simples de utilizar e em alguns minutos e possivel subir sua aplicacao sem provisionar VM's ou algo do tipo. O dimensionamento da aplicacao ocorre de forma automatica de acordo com a demanda e utilizacao, a cobranca ocorre conforme a utilizacao.

![appengine](https://cloud.githubusercontent.com/assets/24530268/26786162/04c5bde6-49dc-11e7-9dbf-1d3b072f35c8.png)

Cloud Spanner
E um servico de banco de dados, reacional, consistente, escalavel horizontalemnte e global. Banco de dados dados SQL e consistente porem muito complicado de escalar horizontalmente devido a complexidade dos dados, ja no NOSQL e muito mais facil escalar horizontamente porem nao tem a mesma consistencia de dados do SQL. Diante deste cenario o Google uniu as melhores caracteristicas dos dois bancos e criou o Cloud Spanner e promete um banco de dados muito robusto.

![cloudspanner](https://cloud.githubusercontent.com/assets/24530268/26782105/3a0b691a-49c8-11e7-8c90-a363f2a698cb.png)

Google Container Engine
Trata-se de um sistem de conteiners na nuvem em cluster, totalmente gerenciado e baseado no Kubernetes. E possivel definir a configuracao desejada para aplicativos e o Container Engine realiza a implantacao e gerenciamento, isso e nativo e facilita muito o dia a dia e o gerenciamento dos containers.

Com certeza o Google esta apostando muito em "Big Data" e "Machine Learning", tem funcionalidades bacana para estes fins.

Google Cloud Big Data Platform
Foi criado uma plataforma focada em Big Data com diversas funcionalidades, algumas delas:
- Big Query: Trata-se de um Data warehouse para analise interativa de grandes quantidades de dados em uma velocidade INCRIVEL! sem precisar provisionar e administrar ambientes uma ferramenta poderosa.
- Cloud Dataproc: Um jeito muito simples de genrenciar e executar Hadoop, Spark/Hive/Pig. Integracao com diversas nuvens e permite a criacao de clusters 90 segundos ou menos.
O grande destaque esta no processamento, sendo possivel realizar uma requery em mais de 4TB e obter os resultados em segundos.

Google Cloud Machine Learning Platform
Assim como Big data, existe uma plataforma para machine learning com funcionalidades incriveis para criar e executar modelos de redes neurais:
- Cloud Vision API: E possivel analisar imagens, deteccao de rostos, logotipos, textos e muito mais. 
- Processamento de Linguagem Natural: Usa modelos de Machine Learning para revelar a estrutura e o significado do texto extrai informações sobre pessoas, lugares, eventos mencionados em documentos, notícias e posts em blogs Analisa textos carregados sob demanda ou se integra ao Cloud Storage
- Cloud Translation API: Traduz strings arbitrárias entre diversos idiomas e detecta o idioma de documentos.

![machine](https://cloud.githubusercontent.com/assets/24530268/26789414/9d5d3afc-49e6-11e7-804b-a34a7a338685.png)

Eu particulamente gostei muito do evento e das opcoes que o Google oferece, o grande destaque fica por conta do alto poder de processamento e a velocidade que ocorre, isso e possivel pois a rede que interliga todos datacenter, toda infraestrutura ssao da propria google

Referencia:
Apresentacao oficial do #CloudOnboard

Link do envento na integra:
https://www.youtube.com/watch?v=UIJVwPPhk84

