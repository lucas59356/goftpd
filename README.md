# Servidor ftp básico

Sabe aquela hora que você tá no lab de informática e precisa passar o ~~counter strike~~ trabalho para os colegas, mas a internet é tão lerda que não vale a pena e também você não quer emprestar seu pendrive por que não quer que as pessoas vejam os segredos obscuros nele? Então, acredito eu que este programinha vai te ajudar muito. 

Ele basicamente cria um servidor de arquivos que pode ser acessado pelo navegador, e por ser feito em go, acredito que performance não seja problema e sobre praticidade é só compilar (make build ou go build) e levar o binário pra qualquer lugar.

Por padrão ele expõe a pasta onde ele está, por exemplo, se eu colocar ele na home do pendrive e rodar ele, ele vai estar expondo seu pedrive inteiro.

Pra compilar esse carinha você precisa do compilador de go, o compilador vai gerar um binário (no caso do windows, um arquivo .exe) e este arquivo está pronto para usar.