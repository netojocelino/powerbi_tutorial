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
 Primeiramente deve-se abrir o |[link](https://www.microsoft.com/pt-BR/download/details.aspx?id=58494) da página de downloads do PowerBI em Português do Brasil (PT-BR), logo após, desce até a tela onde têm o botão _Baixar_ (Imagem 1) e clica nele.
   
 | [![Imagem 1](/images/shots/baixar.png)] |
 | :--:|
 | **Imagem 1** - Escolhendo idioma para baixar |
 Após isso irá aparecer uma tela modal para selecionar a versão e clica na opção que pretende usar, dependendo da arquitetura do computador. A opção ***PBIDesktopSetup_x64.exe*** é para computadores de 64 _bits_ e a opção ***PBIDesktopSetup.exe*** para computadores de 32 _bits_.selecionar a versão clica em _Next_ e aguarda o arquivo ser baixando no computador. No exemplo instalei em um computador de 32 _bits_ (Imagem 2).
| [![Imagem 2](/images/shots/arquitetura.png)] |
| :--:|
| **Imagem 2** - Escolha de arquitetura para baixar |

Após o download concluído, basta abrir o arquivo de instalação e seguir o processo de ler as telas e partir para a próxima página, caso concorde com as informações.

Na primeira tela (Imagem 3) serve para escolha de idioma do **Power BI**, neste tutorial foi escolhido PT-BR. tem um link para abrir o navegador para ler os termos de politica e privacidade, caso concorde clique em *Avançar*.
 | [![Imagem 3] (/images/shots/termos.png)]|
 | :--:|
 | Imagem 3 - Iniciar instalação e termos |

## Minha primeira Dashboard
## Importantdo dados
## Analisando os dados
## Plotando gráficos
## Inserindo gráficos
## Personalizando gráficos
## Interação entre dados
## Filtrando dados
## Mágica


> The overriding design goal for Markdown's
> formatting syntax is to make it as readable
> as possible. The idea is that a
> Markdown-formatted document should be
> publishable as-is, as plain text, without
> looking like it's been marked up with tags
> or formatting instructions.

This text you see here is *actually* written in Markdown! To get a feel for Markdown's syntax, type some text into the left window and watch the results in the right.

### Tech

Dillinger uses a number of open source projects to work properly:

* [AngularJS] - HTML enhanced for web apps!
* [Ace Editor] - awesome web-based text editor
* [markdown-it] - Markdown parser done right. Fast and easy to extend.
* [Twitter Bootstrap] - great UI boilerplate for modern web apps
* [node.js] - evented I/O for the backend
* [Express] - fast node.js network app framework [@tjholowaychuk]
* [Gulp] - the streaming build system
* [Breakdance](https://breakdance.github.io/breakdance/) - HTML to Markdown converter
* [jQuery] - duh

And of course Dillinger itself is open source with a [public repository][dill]
 on GitHub.

### Installation

Dillinger requires [Node.js](https://nodejs.org/) v4+ to run.

Install the dependencies and devDependencies and start the server.

```sh
$ cd dillinger
$ npm install -d
$ node app
```

For production environments...

```sh
$ npm install --production
$ NODE_ENV=production node app
```

### Plugins

Dillinger is currently extended with the following plugins. Instructions on how to use them in your own application are linked below.

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |


### Development

Want to contribute? Great!

Dillinger uses Gulp + Webpack for fast developing.
Make a change in your file and instantaneously see your updates!

Open your favorite Terminal and run these commands.

First Tab:
```sh
$ node app
```

Second Tab:
```sh
$ gulp watch
```

(optional) Third:
```sh
$ karma test
```
#### Building for source
For production release:
```sh
$ gulp build --prod
```
Generating pre-built zip archives for distribution:
```sh
$ gulp build dist --prod
```
### Docker
Dillinger is very easy to install and deploy in a Docker container.

By default, the Docker will expose port 8080, so change this within the Dockerfile if necessary. When ready, simply use the Dockerfile to build the image.

```sh
cd dillinger
docker build -t joemccann/dillinger:${package.json.version} .
```
This will create the dillinger image and pull in the necessary dependencies. Be sure to swap out `${package.json.version}` with the actual version of Dillinger.

Once done, run the Docker image and map the port to whatever you wish on your host. In this example, we simply map port 8000 of the host to port 8080 of the Docker (or whatever port was exposed in the Dockerfile):

```sh
docker run -d -p 8000:8080 --restart="always" <youruser>/dillinger:${package.json.version}
```

Verify the deployment by navigating to your server address in your preferred browser.

```sh
127.0.0.1:8000
```

#### Kubernetes + Google Cloud

See [KUBERNETES.md](https://github.com/joemccann/dillinger/blob/master/KUBERNETES.md)


### Todos

 - Write MORE Tests
 - Add Night Mode

License
----

MIT


**Free Software, Hell Yeah!**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)


   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>
