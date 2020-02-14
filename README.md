# Power BI
| [![Microsoft - Public domain](/powerbi_logo.png)](https://commons.wikimedia.org/wiki/File:Power_bi_logo_black.svg) |
| :---: |
| **Power BI** |

PowerBI é um serviço de análise de negócios da Microsoft. Ela permite a visualização interativa e a construção com uma interface simples para usuários criarem as próprias telas


### Sumário
  - Instação
  - Minha primeira Dashboard
    - Importantdo dados
      - Analisando os dados
    - Plotando gráficos
      - Inserindo gráficos
      - Personalizando gráficos
      - Interação entre dados
      - Filtrando dados
  - Mágica



## Instação

O processo de instalação é super simples, bsatando seguir o seguinte caminho de grãos de café:
 Primeiramente deve-se abrir o [link](https://www.microsoft.com/pt-BR/download/details.aspx?id=58494) da página de downloads do PowerBI em Português do Brasil (PT-BR), logo após, desce até a tela onde têm o botão _Baixar_, como na Imagem 1 e clica nele.
   
 | [![Imagem 1](./images/shots/baixar.png)] |
 |:--:|
 | **Imagem 1** - Escolhendo idioma para baixar |
 Após isso irá aparecer uma tela modal para selecionar a versão e clica na opção que pretende usar, dependendo da arquitetura do computador. A opção ***PBIDesktopSetup_x64.exe*** é para computadores de 64 _bits_ e a opção ***PBIDesktopSetup.exe*** para computadores de 32 _bits_.selecionar a versão clica em _Next_ e aguarda o arquivo ser baixando no computador. No exemplo instalei em um computador de 32 _bits_, que pode ser acompanhada na Imagem 2.
| [![Imagem 2](./images/shots/arquitetura.png)] |
|:--:|
| **Imagem 2** - Escolha de arquitetura para baixar |

Após o download concluído, basta abrir o arquivo de instalação e seguir o processo de ler as telas e partir para a próxima página, caso concorde com as informações.

Na primeira tela da Imagem 3 serve para escolha de idioma do **Power BI**, neste tutorial foi escolhido PT-BR. 
 | [![Imagem 3] (./images/shots/termos.png)]|
 |:--:|
 | Imagem 3 - Iniciar instalação e escolha de idioma |
 
Na tela seguinte, tem um link para abrir o navegador para ler os termos de coleta de dados, caso concorde clique em *Avançar*. Logo em seguida, há a tela de termos de licença, como pode ser visualizada na Imagem 4, caso concorde com os termos, clique em _Aceito os termos do Contrato de Linceça_ e logo em seguida, clicar em _Avançar_.
| [![Imagem 4] (./images/shots/termos_condicao.png)]|
 |:--:|
 | Imagem 4 - Termos de licença |
 
Próximo passo é escolher onde deve ser instalado, podendo clicar em _Avançar_, e na tela seguinte escolher se quer instalar e inserir atalho na área de trabalho e pode _Instalar_ ou voltar e alterar uma informação anterior. Logo em seguida só esperar instalar, quando instalar podemos ver a Imagem 5.

| [![Imagem 5] (./images/shots/terminar_instalar.png)]|
 |:--:|
 | Imagem 5 - Finalizar instalação e iniciar Power BI |
 
Iniciando o Power BI.

| [![Imagem 5] (./images/shots/terminar_instalar.png)]|
 |:--:|
 | Imagem 5 - Finalizar instalação e iniciar Power BI |


## Minha primeira Dashboard
 >> Um painel é um tipo de interface gráfica do usuário que geralmente fornece
 >> visualizações rápidas dos principais indicadores de desempenho relevantes 
 >> para um objetivo ou processo de negócios específico. Em outro uso, "painel"
 >> é outro nome para "relatório de progresso" ou "relatório".
 > Fonte: Wikipédia

  | O resultado deste projeto pode ser aberto em ```sample/hello_world.pbix```.
 
Na nossa primeira Dashboard, iremos criar uma Dashboard que avalia informações relativos à solicitações registradas na Anatel de Sergipe. Esta informação pode ser acessada pelo link do [Portal Brasileiro de Dados Abertos](http://www.dados.gov.br/). O arquivo que iremos utilizar pode ser baixado em [Página do arquivo](http://www.dados.gov.br/dataset/solicitacoesregistradasnaanatel) ou pelo [link direto](www.anatel.gov.br/dadosabertos/PDA/Focus/Solicitacoes.zip). Na Imagem 6 é possível escolher os dados clicando em _Obter dados_.

| [![Imagem 6] (./images/shots/inicio.png)]|
 |:--:|
 | Imagem 6 - tela inicial de apresentação  |

### Importantdo dados

Na tela da Imagem 7, será escolhido o formato de arquivo que será utilizado para a análise e construção de gráficos.
Neste caso utilizaremos _Texto/CSV_ e logo em seguida _Conectar_.

| [![Imagem 7] (./images/shots/obter_dados.png)]|
 |:--:|
 | Imagem 7 - Tela de escolha de tipo de base de dados |
 
Na tela seguinte, Imagem 8, devemos escolher os dados que iremos utilizar, que neste caso utilizaremos o arquivo _Solicitações Registradas na Anatel (2007-SE).csv_ que está na pasta ```./files``` do projeto ou pode ser acessada pelo link do inicio desta seção. Quando selecionar o arquivo, clicar em _Abrir_ 
 
 | [![Imagem 8] (./images/shots/abrir_dados.png)]|
 |:--:|
 | Imagem 8 - Tela de escolha de base de dados |
 
 
#### Analisando os dados


Após carregar o arquivo, deve ser feito o tratamento de dados clicando em _Tratameno de Dados_ ou podendo escolher _Carregar_. neste tutorial vamos apenas focar em gerar gráficos simples.
 
 | [![Imagem 9] (./images/shots/analisar_dados.png)]|
 |:--:|
 | Imagem 9 - Tela de escolha de base de dados |


## Plotando gráficos

Plotar gráficos é uma atividade bastante simples utilizando o Power BI, nesta seção iremos ver como gerar gráficos simples para analisar dados de solicitações registradas na Anatel em Sergipe.

Quando os dados são carregados nos deparamos com a tela da Imagem 10, que temos uma aba para _Filtros_ para filtrar os dados já em tela, _Visualizaççoes que gera os gráficos e _Campos_ que seleciona os campos que devem ser utilizados para gerar os gráficos.

 | [![Imagem 10] (/images/shots/tela_graficos.png)]|
 |:--:|
 | Imagem 10 - Tela de criação de Dashboards |


### Inserindo gráficos

Na Imagem 11 podemos visualizar como inserir um gráfico do tipo Rosca, que será usado nesta primeira seleção. Logo após, selecionamos os dados que devem ser gerados, neste caso utilizaremos _Ano_ e _CanalEntrada_, que gerará o Gráfico 1


 | [![Imagem 11] (./images/shots/escolher_grafico.png)]|
 |:--:|
 | Imagem 11 - Tela de criação de gráfico tipo rosca |
 
 | [![Imagem 12] (./images/shots/grafico1.png)]|
 |:--:|
 | Imagem 12 - Tela com gráfico tipo rosca |


Também iremos utilizar uma tabela como vista na Imagem 12, que irá utilizar os campos de dados _CanalEntrada_ e _Tipo_.


 | [![Imagem 13] (./images/shots/escolher_tabela.png)]|
 |:--:|
 | Imagem 13 - Tela de criação de tabela com tipos de registros |


Obtendo o o que temos na Imagem 13.

| [![Imagem 14] (./images/shots/resultado1.png)]|
 |:--:|
 | Imagem 14 - Tela com gráfico rosca e tabela |
 

Por último, vamos inserir um gráfico do tipo _Faixa de opções_, na imagem 14 e escolhendo as opções _Mes_ e _Tipo_.

| [![Imagem 15] (./images/shots/escolher_grafico2.png)]|
 |:--:|
 | Imagem 15 - Tela com gráfico tipo faixa de opções |


### Personalizando gráficos

Após os passos anteriores obtemos o que temos na Imagem 15, e vamos mudar a cor de cada barra no gráfico _Mes por Tipo_. Primeiro, clicamos no gráfico, e clicamos na aba com o desenho de um rolo de pintura com propriedades de _Formato_ e seleciona _Mostrar tudo_, como pode ser visto em Imagem 16.

| [![Imagem 16] (./images/shots/resultado2.png)]|
 |:--:|
 | Imagem 16 - Tela com todos os gráficos |
 
 | [![Imagem 17] (./images/shots/formatos.png)]|
 |:--:|
 | Imagem 17 - Alterar cores do gráfico |


Após isso, basta mudar a cor de cada campo para a cor que desejar.

### Interação entre dados ou Filtra dados
Para interagir os dados basta clicar na informação e todos os campos irão se adaptar à esse dado. Como pode ser visto na Imagem 
 
 | [![Imagem 18] (./images/shots/filtros.png)]|
 |:--:|
 | Imagem 18 - Filtros entre campos relacionados |


## Mágica

Ao final deste tutorial, tu já estará apto à criar Dashboards para analisar informações diversas.
Assim, podemos salvar o arquivo para análise futura em ```Arquivo > Salvar Como```, escolher o diretório e escolher o nome.



Espero que tenha aproveitado esta jornada.


**Sistema de Apoio à Decisão, Hell Yeah!**
