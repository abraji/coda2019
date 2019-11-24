# [Coda2019](https://coda.escoladedados.org/)
## Repositório do curso "Como revelar o que está escondido à vista de todos"

A Associação Brasileira de Jornalismo Investigativo (Abraji) vai lançar no começo de 2020 a fase 2 do [Publique-se](http://publique-se.org.br). O banco de dados para pesquisas de processos judiciais nos quais políticos brasileiros aparecem como partes vai passar a incluir tribunais de todos os Estados brasileiros, incluindo os de primeira instância. Com base nessa experiência, será oferecido um workshop introdutório sobre a raspagem de dados no Judiciário brasileiro, com o uso de Python 3.

Vamos mostrar as limitações e possibilidades para automatizar pesquisas em tribunais e a coleta de informações processuais. Iremos também usar bibliotecas e módulos como requests, beautifulsoup, soupsieve e selenium webdriver para acessar a busca processual nos tribunais e a posterior geração de CSV com os resultados estruturados.


## O que é necessário instalar primeiro?
### Python!

![Python](/Monty-Python-foot.jpg)

*Atenção: existe Python 2 e Python 3, usamos a versão 3 mais recente*<br>
*Mas no Windows 10 descobri que a versão 3.7.5 é mais estável com selenium e instala as bibliotecas sem erro, recomendo esta versão no Windows*

[Link de Instalação do Python3](https://www.python.org/downloads/)

##### Lembre do PATH

     Ao instalar o Python sempre lembre de marcar a opção PATH: algo como, "Add Python 3 to PATH"
     
##### Repositório da aula

     O mais indicado depois a fazer é clicar no botão "Clone or download" e fazer o "Download ZIP" de todo material da aula
     Você pode descompactar o zip em uma pasta de sua preferência
     Abra o cmd ou terminal e entre nesta pasta, onde está o arquivo requirements.txt
     
### Demais bibliotecas a serem utilizadas:
  
    No cmd ou terminal digite
    pip3 install -U -r requirements.txt

Também lembre

    Lembre que, se você usar MacOS e Linux, terá ao mesmo tempo Python2 e Python3. Então deverá instalar com o pip3
    Para instalar o pip3 no Ubuntu ou Debian Linux sudo apt-get install python3-pip
    Para instalar no Fedora sudo yum install python3-pip


### Chromedriver
    O Chromedriver é o driver que vai permitir o selenium controlar o navegador Google Chrome
    Baixe a versão correspondente ao seu sistema operacional e a sua versão do Chrome
    Depois descompacte o arquivo chromedriver e salve numa pasta de sua escolha
    Anote o local que salvou este arquivo - você vai usar isso nos programas com selenium
Você pode baixar [aqui](https://chromedriver.chromium.org/downloads) 

### Geckodriver
    O geckodriver é o driver que vai permitir o selenium controlar o navegador Mozilla
    Baixe a versão correspondente ao seu sistema operacional e a sua versão do Mozilla
    Depois descompacte o arquivo geckodriver.exe e salve numa pasta de sua escolha
    Anote o local que salvou este arquivo - você vai usar isso nos programas com selenium
    O selenium funciona melhor em algumas ocasiões com o geckodriver
Você pode baixar [aqui](https://github.com/mozilla/geckodriver/releases) 

### Local de instalação do Chrome
    Você também vai precisar saber onde está instalado seu navegador Chrome em sua máquina
    No Windows devem estar em (C:\Program Files (x86)\Google\Chrome\Application\) ou (C:\Users\UserName\AppData\Local\Google\Chrome\Application)
    No Mac deve estar em Users/<username>/Library/Application Support/Google/Chrome/Default
    No Linux basta digitar no Terminal para saber: whereis google-chrome


### Materiais de apoio
    Você também está recebendo na camaradagem:
A [apresentação](https://docs.google.com/presentation/d/156d254C7lSuXeUoTOoVTw5A9RpX_kf7z5JYRuvYyPSY/edit?usp=sharing) da aula<br>
Um [guia jurídico rápido](https://docs.google.com/document/d/1vvxweuRXnHH-Rxt82PYL-KSSp0bMt0m9cC7YomjJX5g/edit?usp=sharing)<br>
Material sobre [boas práticas de raspagem de dados](https://docs.google.com/document/d/1fv6G6Gu0KaJ44RNCCLgZv3M-cIiqF6IwAXhb_WnUKLk/edit?usp=sharing)<br>
Material sobre o uso do [Postman](https://docs.google.com/document/d/1hgoVMDFLXwqJdtBp2HAewcTFJsoISRvTwfWx2Hf2-P4/edit?usp=sharing) para entender o tráfego de um site<br>
Aprenda mais com [curso da Abraji](https://github.com/abraji/cursos_congresso_2019)

### Avisos importantes
    Situação em novembro de 2019: o raspador do STJ ainda está em melhorias, os dados precisam ser bem checados antes de publicar (como tudo no jornalismo...)
    
    Situação em novembro de 2019: e o raspador do TJ-SP parou de funcionar porque o tribunal colocou um Recaptcha V3 - fica mais para didatismo esse exemplo

Mas antes disso a Abraji conseguiu atualizar a base do Ctrl+x para o TJ-SP. [Veja mais](https://abraji.org.br/ctrl-x-atualiza-processos-de-retirada-de-conteudo-apresentados-no-tj-sp)


### No time Toulouse!
    Você já pode começar a estudar os códigos!
    No cmd ou terminal vá onde está o arquivo requirements.txt e digiter: jupyter lab
    Será aberto o Jupyter Lab, ambiente para você ver e executar scripts
    Abra ou crie os arquivos que desejar e namastê!
![Python](/D2HXHPZXQAAvXcI.jpg)    

### Dúvidas de raspagem?
    Escreva no Fórum brasileiro de jornalismo de dados - ambiente para troca de informações da comunidade brasileira
Acesse [aqui](https://forum.jornalismodedados.org/) 
