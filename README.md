# Jogo JokenPo

Este é um aplicativo simples de JokenPo (Pedra, Papel, Tesoura) desenvolvido usando o framework Flutter. O aplicativo permite que o usuário jogue contra o computador, que escolhe uma opção aleatória. O resultado do jogo é exibido na interface de forma clara e direta.

## Funcionalidades
- O usuário pode escolher entre as opções: Pedra, Papel ou Tesoura.
- O aplicativo gera uma escolha aleatória para o computador.
- O resultado do jogo é exibido em uma mensagem, informando se o usuário venceu, perdeu ou empatou.
- Imagens das escolhas feitas pelo usuário e pelo computador são exibidas.

## Como Jogar
1. Ao abrir o aplicativo, o usuário verá a opção "Escolha uma opção abaixo".
2. O usuário pode clicar nas imagens de Pedra, Papel ou Tesoura para fazer sua escolha.
3. O aplicativo irá gerar uma escolha aleatória para o computador e mostrar o resultado do jogo (você venceu, você perdeu ou empatou).

## Tecnologias Utilizadas
- **Flutter**: Framework de desenvolvimento para aplicativos móveis.
- **Dart**: Linguagem de programação utilizada no Flutter.
- **Random**: Pacote utilizado para gerar a escolha aleatória do computador.

## Estrutura do Código
O código é composto por um StatefulWidget chamado **Jogo**, onde o estado das escolhas do usuário e do computador é mantido e atualizado com base nas interações.

Principais funções:
- `_jogar(String escolhaUsuario)`: Recebe a escolha do usuário, gera a escolha aleatória do computador, compara as opções e atualiza o resultado.
- `build()`: Método de construção da interface gráfica, exibindo as imagens de escolha e o resultado.

## Imagens Utilizadas
As imagens correspondentes às opções Pedra, Papel e Tesoura são usadas para representar as escolhas feitas pelo usuário e pelo computador. Estas imagens devem estar na pasta `images` no diretório do projeto.




## Como Executar
1. **Instalar o Flutter**: Siga as instruções no [guia oficial de instalação do Flutter](https://flutter.dev/docs/get-started/install).
2. **Clonar o Repositório**: Clone o repositório com o seguinte comando:
   ```bash
   git clone https://github.com/FelipePucci-afk/Jogo-JokenPo.git

3. **Instalar Dependências**:
   ```bash
   cd app-jokenpo
   
   flutter pub get

4. **Executar o Aplicativo**:
   ```bash
   flutter run

  ##Vídeo de Demonstração: 
  

https://github.com/user-attachments/assets/ddf286dc-60a3-4f0d-90ed-155594a45d2c





