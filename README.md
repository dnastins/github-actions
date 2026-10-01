# Atividade GitHub Actions

## Descrição

Este projeto demonstra a criação de um workflow utilizando o GitHub Actions.

O workflow é executado automaticamente sempre que ocorre um `push` no repositório.

## Workflow

O arquivo do workflow está localizado em:

`.github/workflows/primeiro-workflow.yml`

## Actions utilizadas

- `actions/checkout@v4`: baixa o conteúdo do repositório para o ambiente do GitHub Actions.
- `actions/setup-python@v7`: configura o ambiente Python utilizado durante a execução.

## Etapas executadas

O workflow realiza as seguintes etapas:

1. Baixa o conteúdo do repositório.
2. Configura o Python.
3. Exibe a versão do Python.
4. Lista os arquivos do projeto.
5. Exibe a mensagem:

`Pipeline executada com sucesso!`

## Execução

O workflow é acionado automaticamente sempre que um `push` é realizado no repositório.

A execução pode ser acompanhada pela aba **Actions** do GitHub.