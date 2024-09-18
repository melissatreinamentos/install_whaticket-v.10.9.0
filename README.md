# S.I. Whaticket SaaS

<p align="center">
  <a href="https://www.codefactor.io/repository/github/rtenorioh/press-ticket"><img src="https://www.codefactor.io/repository/github/rtenorioh/press-ticket/badge" alt="CodeFactor" /></a>

  <img alt="Swagger Validator" src="https://img.shields.io/swagger/valid/3.0?specUrl=https%3A%2F%2Fraw.githubusercontent.com%2Frtenorioh%2FPress-Ticket%2Fmain%2Fbackend%2Fsrc%2Fswagger.json">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/rtenorioh/Press-Ticket">

  <a href="https://github.com/rtenorioh/Press-Ticket/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/rtenorioh/Press-Ticket">
  </a>
      
   <a href="https://github.com/rtenorioh/Press-Ticket/stargazers">
    <img alt="Stargazers" src="https://img.shields.io/github/stars/rtenorioh/Press-Ticket">
  </a>

  <a href="https://github.com/rtenorioh/Press-Ticket/network">
    <img alt="GitHub forks" src="https://img.shields.io/github/forks/rtenorioh/Press-Ticket">
  </a>

  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/rtenorioh/Press-Ticket">

  <img alt="GitHub release (latest by date)" src="https://img.shields.io/github/v/release/rtenorioh/Press-Ticket">

  <img alt="GitHub Release Date" src="https://img.shields.io/github/release-date/rtenorioh/Press-Ticket">
</p>

## Sobre

Um sistema de tickets muito simples baseado em mensagens do WhatsApp, que permite multiusuários na mesma conta do WhatsApp.

## Requisitos

| --- | Mínimo | Recomendado |
| --- | --- | --- |
| Node JS | 20.x 
| Ubuntu | 18.x | 20.x |
| Memória RAM | 4Gb | 6Gb |  

## Referência

- O Sistema Whaticket foi desenvolvido com base no [Sistema Whaticket](https://github.com/canove/whaticket), desenvolvido por [Cassio Santos](https://github.com/canove).

## Instalação do Whaticket SaaS

- 1º passo: Digite o comando abaixo para atualizar a vps

sudo apt-get update && sudo apt-get upgrade -y

- 2º passo: digite o comando abaixo para reiniciar a vps:

reboot

- 3º passo: link do instalador.
  
sudo apt install -y git && git clone https://github.com/melissatreinamentos/install_whaticket.git && sudo chmod -R 777 instalador-whaticket-main && cd instalador-whaticket-main && sudo ./install_primaria
