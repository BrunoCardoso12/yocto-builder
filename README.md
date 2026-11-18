# Yocto Builder

**Simplificando a criação de imagens Linux embarcadas.**

O **Yocto Builder** é um projeto open source que busca simplificar e padronizar o processo de compilação de sistemas Linux embarcados utilizando o Yocto Project e Docker.

A proposta é disponibilizar um ambiente de compilação isolado, reutilizável e configurável, reduzindo a necessidade de preparar manualmente as dependências e ferramentas no sistema hospedeiro.

## Objetivos

- Criar um ambiente de compilação Yocto utilizando Docker.
- Simplificar a configuração do ambiente de desenvolvimento.
- Permitir a utilização de diferentes plataformas embarcadas.
- Facilitar a integração de repositórios e camadas Yocto.
- Reutilizar downloads e caches entre compilações.
- Centralizar os artefatos gerados.
- Tornar o processo de compilação mais reproduzível.

## Desenvolvimento atual

O projeto está em desenvolvimento e sua implementação inicial utiliza o **Yocto Project 6.0 (Wrynose)** e a **Raspberry Pi 3** como plataforma de referência.

Até o momento, foram preparados:

- Ambiente Docker com as dependências iniciais do Yocto.
- Usuário sem privilégios de root dentro do container.
- Volumes persistentes para workspace, downloads, cache e resultados.
- Configuração inicial das camadas OpenEmbedded e meta-raspberrypi.

A automação da configuração dos projetos e do processo de compilação está entre as próximas etapas.

## Tecnologias utilizadas

- Yocto Project
- OpenEmbedded
- BitBake
- Docker
- Linux
- Git

## Status do projeto

**Em desenvolvimento.**

Este projeto é uma iniciativa pessoal de aprendizado e desenvolvimento, com o objetivo de evoluir para uma ferramenta reutilizável pela comunidade de sistemas embarcados.# yocto-builder
