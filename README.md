# Site NajaTec com Hugo e Docsy.

Nesse projeto foram utilizadas as ferramentas Hugo e Docsy.  
Hugo é um gerador de sites estáticos desenvolvidos em Go, otimizados para velocidade em Hot Reload e responsivo.  
Ele possui sistemas de templates (Themes).

## Instalações:

+  Entrar no site oficial [Hugo](https://gohugo.io).  
 Necessário já ter o [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) instalado.     
 Acessar o [Repositório do GitHub](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) e selecionar a ultima versão do Hugo Extend para Windows.
 >  
Quando selecionar, vai instalar um arquivo zipado.
> 
Após a instalação onde vai ser trabalhado crie uma nova pasta chamada "Hugo" e dentro dela outra pasta chamada "bin".  
Extraia o arquivo dentro desta ultima pasta .

## Configuração do Hugo.
* Após a instalação abra o Prompt de comando e digite "hugo version" irá dizer que não está instalado.
* Após isso digite "cd (Caminho até a pasta bin)" e digite novamente "hugo version".
* ### Para resolver:
> Aperte a tecla Windows + R e digite "SystemPropertiesAdvanced" e selecione "Variaveis de Ambiente".  
> Então selecione o "Path" e clique em "Editar".  
> Então  clique em "Novo" e digite ou cole todo o caminho do sistema até a pasta "bin". Um exemplo "C:\user\Hugo\bin".  
> Pode fechar tudo e testar novamente.  

* Abra a IDE e crie um novo terminal e digite "cd (caminho para a pasta bin)" e crie um site.
> Para criar um site digite  no terminal "hugo new site (nome do site)".  

## Utilizando o Docsy.
* Entre no site oficial do [Hugo themes](https://themes.gohugo.io/) e busque por Docsy ou entre direto no [Repositório no GitHub](https://github.com/google/docsy) e selecione "Usar este repositório" no canto superior direito
* Dê um nome ao seu novo repositório e depois vá em "Settings" e clique em "Pages"
* Onde estiver escrito "Debug and Deployment" e depois "Source", em baixo altere de "Debug and Deployment" para "GitHub Actions"
* Após isso tudo entre na IDE e selecione para copiar diretório do GitHub
* Verifique se o [Node.js](https://nodejs.org/en) está atualizado ou instalado
* Instale o PostCSS:
> npm install postcss postcss-cli --save-dev  
* Instale os plugins do PostCSS:  
> npm install autoprefixer --save-dev  
npm install cssnano --save-dev  

## Configurações gerais e visualização.
* Abra o arquivo hugo.toml 
* Digite "theme = "nome do repositório Docy"".
* Agora no terminal com o caminho até o pasta do site digite "hugo server".
* Se não abrir automático vá até sua ferramenta de pesquisa (Google) e busque por "localhost:1313"
