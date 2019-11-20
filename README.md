# Coda2019
## Repositório do curso "Como revelar o que está escondido à vista de todos"


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
    pip install -r requirements.txt

Também

    Lembre que, se você usar MacOS e Linux, terá ao mesmo tempo Python2 e Python3. Então deverá instalar o pip3 e rodar o comando acima com pip3 install etc, etc.
    Para instalar o pip3 no Ubuntu ou Debian Linux sudo apt-get install python3-pip
    Para instalar no Fedora sudo yum install python3-pip


### Chromedriver
    O Chromedriver é o driver que vai permitir o selenium controlar o navegador Google Chrome
    Baixe a versão correspondente ao seu sistema operacional e a sua versão do Chrome
    Depois descompacte o arquivo chromedriver e salve numa pasta de sua escolha
    Anote o local que salvou este arquivo - você vai usar isso nos programas com selenium
Você pode baixar [aqui](https://chromedriver.chromium.org/downloads) 


### Local de instalação do Chrome
    Você também vai precisar saber onde está instalado seu navegador Chrome em sua máquina
    No Windows devem estar em (C:\Program Files (x86)\Google\Chrome\Application\) ou (C:\Users\UserName\AppData\Local\Google\Chrome\Application)
    No Mac deve estar em Users/<username>/Library/Application Support/Google/Chrome/Default
    No Linux basta digitar no Terminal para saber: whereis google-chrome


### Materiais de apoio
    Você também está recebendo na camaradagem:
A [apresentação](https://about:blank) da aula<br>
Um [guia jurídico rápido](https://about:blank)<br>
Material sobre [boas práticas de raspagem de dados](https://about:blank)<br>
Material sobre o uso do [Postman](https://about:blank) para entender o tráfego de um site<br>
Aprenda mais com [curso da Abraji](https://about:blank)


### No time Tolouse!
    Você já pode começar a estudar os códigos!
    No cmd ou terminal vá onde está o arquivo requirements.txt e digiter: jupyter lab
    Será aberto o Jupyter Lab, ambiente para você ver e executar scripts
    Abra ou crie os arquivos que desejar e namastê!
![Python](/Monty-Python-foot.jpg)    
