# Projeto de Automação com PyAutoGUI / Python

Este projeto utiliza a biblioteca PyAutoGUI para automatizar a interação com um sistema web. A seguir, descrevo o passo a passo das principais funcionalidades implementadas:

## 1. Entrar no Sistema

O código realiza a automação do processo de login em um sistema web específico. Ele abre o navegador Chrome, acessa o link fornecido, e preenche automaticamente as credenciais de usuário e senha.

## 2. Fazer Login

Após abrir o navegador, o script digita o nome de usuário e a senha nos campos correspondentes e pressiona a tecla "Enter" para efetuar o login.

## 3. Importar Base de Dados

O projeto inclui a capacidade de importar uma base de dados a partir de um arquivo CSV chamado "produtos.csv". Utiliza a biblioteca pandas para carregar os dados e exibi-los no console.

## 4. Cadastrar Produtos

O código percorre cada linha da base de dados e realiza o cadastro de produtos no sistema. Para cada linha, o script preenche diferentes campos, como código, marca, tipo, categoria, preço unitário, custo e observações. Após preencher os campos, pressiona a tecla "Enter" para confirmar o cadastro.

## 5. Repetir o Processo

O script repete o processo de cadastro de produtos para cada linha da base de dados, garantindo que todos os itens sejam registrados no sistema.
