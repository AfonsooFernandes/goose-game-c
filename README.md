# 🎲 Jogo do Ganso (Implementação em C)

## 📌 Objetivo
Este projeto tem como objetivo analisar e implementar, em linguagem C, uma adaptação do clássico "Jogo do Ganso".

## 📖 Descrição do Jogo
O jogo possui três opções de tabuleiro:
- **S**: Pequeno (20 casas)
- **M**: Médio (30 casas)
- **L**: Grande (50 casas)

Cada casa possui uma pergunta associada, e conforme a resposta, o jogador avança ou recua um determinado número de casas.

Tipos de perguntas incluídas:
- Escolha múltipla (1 correta entre 4 opções)
- Verdadeiro/Falso (resposta V ou F)
- Resposta direta (respostas curtas como nome de cidade, número, etc.)

Vence quem chegar primeiro ao final do tabuleiro e responder corretamente à última pergunta.

## 🛠️ Estrutura do Projeto
O projeto divide-se em três partes principais:
1. **Preparação do Tabuleiro:** Definir ações para cada casa (array).
2. **Gestão das Perguntas:** Implementação usando listas ligadas e armazenamento em ficheiros binários.
3. **Implementação do Jogo:** Lógica principal do jogo e interação com utilizadores.

## 👥 Tipos de Utilizadores
Existem dois tipos principais de utilizadores:
- **Administrador:** cria e edita tabuleiros e perguntas.
- **Jogador:** participa no jogo, com obrigatoriedade de registo e autenticação.

## ⚙️ Funcionalidades Implementadas
- Gestão de utilizadores com autenticação (armazenados em ficheiro)
- Criação e edição dinâmica de tabuleiros
- Gestão completa das perguntas (adicionar, editar e remover)
- Persistência das perguntas em ficheiro binário
- Registo detalhado de jogadores (nome, idade, nacionalidade, data do último jogo)
- Histórico dos últimos 30 jogos
- Listagem de jogadores por ordem alfabética e idade
- Evitar repetição imediata das perguntas entre jogos

## 🚀 Como Executar o Programa
Compile e execute usando:
```sh
gcc -o jogo_do_ganso jogo_do_ganso.c
./jogo_do_ganso
```

## 📋 Requisitos Técnicos
- Linguagem C
- Utilização de arrays e listas ligadas
- Manipulação de ficheiros (texto e binários)

## 📅 Ano Letivo
- 2022/2023

## 📝 Autor
- **Afonso Fernandes**