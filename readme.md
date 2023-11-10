# Estacionamento Web App

Este é um aplicativo web simples de estacionamento desenvolvido em HTML, TypeScript e JavaScript. Desenvolvido com foco em treinar e aprimorar as habilidades em TypeScript, o aplicativo permite cadastrar veículos, registrar a entrada no estacionamento e remover veículos quando saem.

## Funcionalidades

- **Cadastro de Veículos:** Preencha os campos de nome e placa do veículo e clique no botão "Cadastrar" para adicionar um veículo ao estacionamento.

- **Lista de Veículos:** Visualize a lista de veículos cadastrados, incluindo nome, placa, hora de entrada e ações disponíveis.

- **Remoção de Veículos:** Ao clicar no botão "X" na lista de veículos, é possível remover um veículo do estacionamento.

## Como Executar

1. Baixe todos os arquivos do repositório.
2. Abra o arquivo `index.html` em seu navegador web.

## Desenvolvimento

O código-fonte está dividido em três partes principais:

- **HTML (index.html):** Define a estrutura da página web.

- **TypeScript (script.ts):** Contém a lógica do aplicativo, incluindo a manipulação do DOM, cálculos de tempo e interações com o armazenamento local.

- **JavaScript (script.js):** O código TypeScript é transpilado para JavaScript para execução no navegador.

## Armazenamento Local

Os dados dos veículos são armazenados localmente no navegador usando o `localStorage`. Isso permite que as informações persistam mesmo após a atualização da página.

