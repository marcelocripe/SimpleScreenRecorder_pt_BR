Repositório oficial do programa "SimpleScreenRecorder"

https://github.com/MaartenBaert/ssr
e
https://github.com/MaartenBaert/ssr/blob/master/src/translations/simplescreenrecorder_pt_BR.ts


Traduções revisadas por marcelocripe:

https://github.com/marcelocripe/SimpleScreenRecorder_pt_BR/blob/main/simplescreenrecorder_pt_BR.ts

https://github.com/marcelocripe/SimpleScreenRecorder_pt_BR/blob/main/simplescreenrecorder.desktop

Para utilizar os arquivos "simplescreenrecorder_pt_BR.ts" e o "simplescreenrecorder.desktop", inicie o Emulador de Terminal na pasta onde estão os arquivos que foram baixados e execute os comandos.


"simplescreenrecorder_pt_BR.ts":

Comando para converter o arquivo editável da tradução com a extensão ".ts" para ".qm".

$ sudo apt update

$ sudo apt install qttools5-dev-tools

$ lrelease simplescreenrecorder_pt_BR.ts

Comando para copiar o arquivo da tradução com a extensão ".qm" para a pasta do idioma "pt_BR".

$ sudo cp simplescreenrecorder.qm /usr/share/????


"simplescreenrecorder.desktop":

Comando para copiar o arquivo com a extensão ".desktop" para a pasta /usr/share/application.

$ sudo cp simplescreenrecorder.desktop /usr/share/applications

Comando para escrever globalmente todas as entradas dos menus do antiX:

$ sudo desktop-menu --write-out-global
