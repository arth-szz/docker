# docker

# Introdução ao Docker: Site Estático com Nginx

Este repositório demonstra um site simples servido a partir de um container Docker usando o servidor web Nginx. O projeto foi criado com o objetivo de ilustrar os conceitos básicos de containerização.

## Benefícios do Docker

* **Portabilidade:** Containers rodam da mesma forma em qualquer ambiente compatível com Docker.
* **Isolamento:** Dependências e configurações não se misturam entre aplicações.
* **Desenvolvimento mais rápido:** Ambiente consistente entre a máquina do desenvolvedor e os servidores de produção.

## Estrutura do Projeto

O repositório contém o essencial para servir uma página estática:

* `Dockerfile`: Define a imagem base (`nginx`) e copia os arquivos locais para o diretório padrão do servidor.
* `index.html`: O conteúdo visual da página web.