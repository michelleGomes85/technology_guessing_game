# Technology Guessing Game

Este é um jogo de adivinhação de palavras secretas relacionadas à tecnologia. O jogador recebe uma dica e deve adivinhar qual é a palavra secreta. O projeto foi desenvolvido durante o Intensivão de Python da Alura.

## 📋 Funcionalidades

**Palavra secreta:** O jogo escolhe uma palavra aleatória relacionada à tecnologia de um arquivo JSON.
**Dica:** Uma dica é fornecida ao jogador para ajudá-lo a adivinhar a palavra.
**Verificação:** O jogo verifica se o palpite do jogador está correto e informa o resultado.

## 🛠️ Tecnologias Utilizadas

**Python:** Linguagem utilizada para o desenvolvimento
**Biblioteca requests:** Utilizada para fazer solicitações HTTP e obter as palavras secretas de um arquivo JSON online.
**Biblioteca random:** Utilizada para selecionar aleatoriamente uma palavra secreta da lista.

## 🔗 Fonte de Dados

O jogo obtém as palavras secretas de um arquivo JSON hospedado em:

```bash
https://raw.githubusercontent.com/guilhermeonrails/api-imersao-ia/main/words.json
```

## 🎮 Como Jogar
1. O jogo irá exibir quantas letras a palavra secreta possui e fornecer uma dica.
2. Insira seu palpite na linha de comando.
3. O jogo informará se você acertou ou errou o palpite.
   
## 📚 Aprendizados

Este projeto foi desenvolvido durante o Intensivão de Python da Alura, onde aprendemos a:
1. Trabalhar com requisições HTTP usando a biblioteca requests.
2. Manipular arquivos JSON.
3. Criar um fluxo interativo simples com o usuário.
4. Utilizar a biblioteca random para gerar seleções aleatórias.

## 📄 Licença

Este projeto não possui uma licença específica. Sinta-se à vontade para clonar, modificar e melhorar.
