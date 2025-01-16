# Jogo do Número Secreto

Este é um jogo simples implementado em JavaScript, HTML e CSS, onde o objetivo é adivinhar um número secreto gerado aleatoriamente entre 1 e 10. O projeto utiliza a API `responsiveVoice` para tornar o jogo mais interativo com feedback por voz.

## Funcionalidades

- **Número Aleatório**: Um número secreto é gerado automaticamente ao iniciar o jogo.
- **Feedback Interativo**: O jogo fornece feedback em texto e por voz.
- **Contagem de Tentativas**: Mostra o número de tentativas necessárias para adivinhar corretamente.
- **Controle de Erros**: Mensagens de erro personalizadas indicam se o chute foi maior ou menor que o número secreto.
- **Reinício do Jogo**: Botão para reiniciar o jogo com um novo número secreto.

## Como Jogar

1. Ao abrir o jogo, será exibida uma mensagem inicial com as instruções.
2. Digite um número entre 1 e 10 no campo de entrada e clique no botão de enviar.
3. O jogo informará se o número digitado é maior, menor ou igual ao número secreto.
4. Continue tentando até acertar o número.
5. Ao acertar, o jogo mostrará o número de tentativas e habilitará o botão de reinício para jogar novamente.

## Tecnologias Utilizadas

- **HTML**: Estrutura básica do jogo.
- **CSS**: Estilização visual (não incluído no código fornecido, mas pode ser incorporado).
- **JavaScript**: Lógica do jogo e manipulação de DOM.
- **API `responsiveVoice`**: Fornece feedback por voz ao jogador.

## Código Principal

O arquivo `app.js` contém a lógica principal do jogo, incluindo:

- Funções de exibição de mensagens.
- Geração de número aleatório sem repetição.
- Verificação do chute do jogador.
- Controles de reinício e limpeza do campo de entrada.

### Principais Funções

- `exibirTextoNaTela(tag, texto)`: Atualiza o texto de um elemento HTML e fornece feedback por voz.
- `exibirMensagemInicial()`: Exibe as instruções iniciais do jogo.
- `verificarChute()`: Verifica se o chute do jogador está correto, maior ou menor que o número secreto.
- `gerarNumeroAleatorio()`: Gera um número secreto entre 1 e 10, garantindo que não seja repetido até que todos os números tenham sido usados.
- `limparCampo()`: Limpa o campo de entrada após cada tentativa.
- `reiniciarJogo()`: Reinicia o jogo com um novo número secreto.

## Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
