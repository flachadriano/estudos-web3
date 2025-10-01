# Blockchain

Sugerido iniciar pelos 8 primeiros vídeos desta playlist: [Blockchain](https://www.youtube.com/playlist?list=PLsGmTzb4NxK0hRfnjfcg0f9rc0lleY28O)

Em seguida, focar em entender como funciona o Bitcoin, no [site oficial](https://bitcoin.org/en/)

Enquanto estuda os conceitos, implemente eles da melhor forma.

## Entendimento do [Whitepaper](./bitcoin-whitepaper.pdf)

Foi criado com a intenção de garantir uma transação não reversível.

Visto que um banco, em última instância, pode reverter uma transação por qualquer motivo externo, por exemplo: requisição judicial

A ideia é de garantir essas transações através da resolução computacional de um problema grande.

O que faria que para adulterar alguma transação, o atacante precisaria ter um poder de processamento maior um nó fiel da rede.

No whitepaper também é apresentada a solução para o gasto duplo da mesma moeda, através de peer-to-peer timestamp distribuída.

### Como prevenir gasto duplo

Poderia ser feito através de uma central, que processa toda transação, trocando o token recebido.

Porém isso faria com que esse modelo ficasse muito similar a um banco centralizador, tendo uma fonte para ataque.

Para resolver isso, cada transação deve ser processada e verificado todo o histórico de transações entre diferentes nós.

Todos os nós devem concordar que esse é o único caminho que essa moeda seguiu em seu histórico.

### Garantindo integridade

Para garantir que uma transação não tenha sido fraudada, é utilizado o proof-of-work.

O sistema utilizado de proof-of-work é similar ao do [hashcash](./hashcash-whitepaper.pdf)
