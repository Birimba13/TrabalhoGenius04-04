# Jogo Gênios - React Native

Este é um jogo estilo "Gênios" (também conhecido como "Simon" ou "Genius") desenvolvido em React Native. O objetivo do jogo é memorizar e repetir uma sequência de luzes que piscam em uma grade 3x3.

## Funcionalidades

- Grade 3x3 com 9 quadrados coloridos
- Três níveis de dificuldade (Fácil, Médio, Difícil)
- Sequências aleatórias que aumentam progressivamente
- Efeitos sonoros para cada quadrado
- Sistema de pontuação e recorde
- Interface visual simples e intuitiva

## Como Jogar

1. Selecione o nível de dificuldade desejado na tela inicial
2. Toque no botão "Iniciar Jogo"
3. Observe atentamente a sequência de quadrados que piscam
4. Quando for sua vez, toque nos quadrados na mesma ordem que eles piscaram
5. Se você acertar, um novo quadrado será adicionado à sequência
6. Se você errar, o jogo exibirá uma mensagem de erro e reiniciará o nível

## Níveis de Dificuldade

- **Fácil**: Sequência inicial com 2 passos, velocidade mais lenta
- **Médio**: Sequência inicial com 3 passos, velocidade média
- **Difícil**: Sequência inicial com 4 passos, velocidade mais rápida

## Tecnologias Utilizadas

- React Native
- Expo
- React Hooks (useState, useEffect, useRef)
- Expo Audio para efeitos sonoros

## Estrutura do Projeto

- `App.tsx`: Componente principal que gerencia o estado do jogo
- `components/Square.tsx`: Componente para os quadrados do jogo
- `components/DifficultySelector.tsx`: Componente para selecionar o nível de dificuldade
- `assets/sounds/`: Pasta contendo os arquivos de áudio

## Como Executar

1. Certifique-se de ter o Node.js e o Expo CLI instalados
2. Clone este repositório
3. Execute `npm install` para instalar as dependências
4. Execute `expo start` para iniciar o aplicativo
5. Use o aplicativo Expo Go no seu dispositivo móvel para escanear o QR code ou execute em um emulador

## Melhorias Futuras

- Adicionar mais efeitos visuais
- Implementar um sistema de níveis progressivos
- Adicionar um modo de jogo com tempo limitado
- Salvar recordes localmente
- Adicionar suporte para diferentes temas visuais

