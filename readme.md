# Hello Full Cycle utilizando Golang e Docker

Informações do desafio
O primeiro desafio dessa maratona consiste em criar um "Hello Full Cycle" utilizando a linguagem Golang.
Basicamente quando o arquivo compilado for executado, deverá ser exibido: Hello Full Cycle.
Se tudo estiver funcionando de forma adequada, gere uma imagem docker que quando executada deva rodar o programa criado em Golang.

Faça o push da imagem no Docker Hub e informe a url da imagem na área de entrega do desafio abaixo.

OBS: Caso você não tenha experiência com Docker ou com Golang, recomendamos os vídeos abaixo:
- Iniciando com Docker
- Go Lang: A linguagem simples e rápida que todo desenvolvedor Full Cycle deveria saber

Não se esqueça que também temos um canal na comunidade criada no Discord para debater exatamente esse desafio.

## Como executar?
```
go run main.go
```

## Docker
```
docker build -t jailtonjunior/maratona-fullcycle-desafio01:latest .
```
```
docker run jailtonjunior/maratona-fullcycle-desafio01:latest
```
```
docker push jailtonjunior/maratona-fullcycle-desafio01:latest
```