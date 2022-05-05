[![English](https://img.shields.io/badge/see%20in-%F0%9F%87%BA%F0%9F%87%B8%20english-blue.svg?style=flat-square&logo=appveyor)](https://github.com/scorninpc/lambari-docker/blob/main/README-en.md)

[![GitHub license](https://img.shields.io/github/license/scorninpc/lambari-docker.svg?style=flat-square)](https://github.com/scorninpc/lambari-docker/blob/master/LICENSE)
[![Github all releases](https://img.shields.io/github/downloads/scorninpc/lambari-docker/total.svg?style=flat-square)](https://GitHub.com/scorninpc/lambari-docker/releases/)
[![GitHub issues](https://img.shields.io/github/issues/scorninpc/lambari-docker.svg?style=flat-square)](https://GitHub.com/scorninpc/lambari-docker/issues/)
[![GitHub forks](https://badgen.net/github/forks/scorninpc/lambari-docker/?style=flat-square)](https://GitHub.com/scorninpc/lambari-docker/network/)
[![GitHub stars](https://badgen.net/github/stars/scorninpc/lambari-docker/?style=flat-square)](https://GitHub.com/scorninpc/lambari-docker/stargazers/)
[![GitHub watchers](https://badgen.net/github/watchers/scorninpc/lambari-docker/?style=flat-square)](https://GitHub.com/scorninpc/lambari-docker/watchers/)

# Lambari Docker Compose

Lambari Docker Compose é um frontend desenvolvido em PHP-GTK 3 para iniciar e parar containers com Docker Compose

![App Screenshot](https://user-images.githubusercontent.com/2607849/166913575-2203dfad-74ee-479f-b615-2bafb1db90e1.png)

## Instalação

Para executar esse script, primeiro você precisa ter o [php-gtk 3](https://github.com/scorninpc/php-gtk3/). Siga as instruções para instalação, e basta executar

```bash
:$ php-gtk lambariDocker.php
```

ou você pode ajustar o run.sh conforme precisar, e iniciar somente com

```bash
:$ ./run.sh
```


## Como usar

Para usar o Lambari Docker Compose, inicie a aplicação. Após isso, clique em adicionar novo, localize o arquivo docker-compose.yml que deseja gerenciar.

Quando você escolher o arquivo do compose, os serviços irão aparecer na lista, onde você pode gerencia-los dando 2 cliques, para iniciar ou parar o container

## Autores

- [@scorninpc](https://www.github.com/scorninpc)

