# script-debian-mauricio
Script para formatação do meu computador.
Este repositório é pessoal, mas pode servir como guia para qualquer um que queira scriptar a formatação e configuração do seu Debian, principalmente se o seu Ambiente de Desktop for o KDE :)

### Como funciona:

## ./configurar-kde

1 - Executa o arquivo repositoriosMauricio
2 - Insere usuário atual no sudo
3 - Muda o editor padrão do sudoedit para o VIM
4 - Instala e configura o bash-completion do Debian
5 - Ajusta o tempo do grub para 0
6 - Adiciona o repositório de backports do Debian

## ./repositorios-mauricio:

* Clona meu repositório com o instalador do vim, e minhas personalizações. Após a execução do script o repositório é apagado.
* Clona meu repositório com o instalador dos comandos especiais que criei para o terminal. Após a execução do script o repositório é apagado.

## ./custom-sources

* Adiciona automaticamente os seguintes repositórios para o Debian: Google chrome, Google music manager, Megasync, Virtualbox e Wine.

## ./limpar-kde

* Deleta as aplicações que não gosto do KDE, e as substitui por aplicações que acredito serem melhores.

## ./apps-apt

* Instala todos os aplicativos que uso. Necessita que o custom-sources seja executado antes!

## atalhos-teclado.kksrc

* É meu arquivos de atalhos do teclado, para ser importado pelo Global Keyboard Shortcuts - nas configurações do KDE.

## other_apps

* É uma pasta onde os arquivos que não são instalados da maneira convencional estão:
  * Instalador do docker
  * Instalador do container lamp (requer docker instalado e acesso ao meu repositório lamp, que também contém instalador).
  * Instalador do phpstorm
  * Instalador woeusb


A pasta Snippets contém snippets que ocasionalmente são precisos utilizar no Debian e podem dar pequeno trabalho para encontrar.
