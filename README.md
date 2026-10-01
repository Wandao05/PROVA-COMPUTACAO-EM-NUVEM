# Prova 1 de Computação em Nuvem

Nome: Wanderley G Junior

RA: 52831101840

## O que fiz

Criei um contêiner Docker chamado `reservas`.

Executei uma página web em um contêiner utilizando a imagem `nginx:alpine`.

A página foi disponibilizada na porta 8086 do ambiente.
A diferença principal é esta:
Imagem: é um modelo pronto usado para criar containers. Ela contém os arquivos, programas e configurações necessários. No seu caso, nginx:alpine é a imagem.
Container: é uma instância em execução criada a partir da imagem. No seu caso, loja é o container que está executando o Nginx.

Uma comparação simples: a imagem é como uma receita, enquanto o container é o prato preparado a partir dessa receita.

No seu exemplo, a imagem nginx:alpine serviu de base para criar o container loja. Dentro dele, o Nginx está rodando e entregando o index.html.

