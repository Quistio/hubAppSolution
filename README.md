# hubAppSolution
Pagina inicial com link de todas as aplicações do DEV

## Onde colocar estes arquivos?
Os arquivos devem ser colocados na pasta "ROOT" das webapps do tomcat (C:\Program Files\Apache Software Foundation\Tomcat 9.0\webapps\ROOT), antes deve ser excluído os arquivos que já existem nesta pasta.

## Como adicionar o link?
Para cada aplicação será necessario adicionar um trecho do código a baixo no "index.html", deve ser alterado o link e o nome da aplicação:
```html
<div class="row-app">
    <!-- Ex.: -->
    <!-- <a href="http://localhost:8081/Estavel16Java/servlet/erpsolution.ambiente.secloginerpsolution"> -->
    <a href="#link_app#">
        <div class="app-title">#nome_app#</div>
        <div class="app-link"><i class="fa-solid fa-up-right-from-square"></i>
        </div>
    </a>
</div>
```