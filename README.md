<p align="center">
  <a href="https://github.com/caoveio/pelikan">
    <img src=".github/pelikan.jpg" alt="Café com Testes">
  </a>
</p>

## **Parte 1 - Configuração do Servidor** 

A sua tarefa consiste em configurar um servidor baseado na nuvem e instalar e configurar alguns componentes básicos.

1. Configurar um servidor AWS (recomenda-se o freetier) executando uma versão Ubuntu LTS.
2. Instalar e configurar qualquer software que você recomendaria em uma configuração de servidor padrão sob as perspectivas de segurança, desempenho, backup e monitorização.
3. Instalar e configurar o nginx para servir uma página web HTML estática.
4. Utilizar ferramentas de automatização como Ansible, Terraform ou AWS Cloudformation.

## **Part 2 – Scripting**

Utilizando uma linguagem de script à sua escolha, construa um projeto (servido através do nginx) que possa relatar estatísticas operacionais básicas sob a forma de um objeto JSON.

As estatísticas devem incluir (como mínimo):


1. Carga actual da CPU, tempo de espera e utilização de memória (opcionalmente reportado como slab, cache, RSS, etc.)
2. Se existem actualizações pendentes (opcionalmente, reportando actualizações de segurança independentemente)
3. Utilização actual do disco e desempenho de leitura/escrita

O resultado final pode incluir quaisquer outras estatísticas que considere importantes para efeitos de monitorização do servidor. Você pode considerar a possibilidade de construir o script em cima do projeto [dstat](https://github.com/dagwieers/dstat).

**obs:** O seu código deve ser entregue a um repositório Git que demonstram uma compreensão de conceitos tais como ramificação de branchs e merges requests.


## Readme do Repositório

- Deve conter o título do projeto
- Uma descrição sobre o projeto em frase
- Deve conter uma lista com linguagem, framework e/ou tecnologias usadas
- Como instalar e usar o projeto (instruções)
- Não esqueça o [.gitignore](https://www.toptal.com/developers/gitignore)

