# como operar futuros na OKX: guia prático para abrir posições, usar alavancagem e controlar o risco

Quem pesquisa **como operar futuros na OKX** normalmente quer resolver três dúvidas de uma vez: onde encontrar os contratos, como abrir uma posição comprada ou vendida e o que realmente pode fazer uma operação dar errado. A interface parece simples, mas futuros misturam margem, alavancagem, taxa de financiamento, tipos de ordem e liquidação. Ignorar qualquer uma dessas partes costuma sair caro.

A OKX oferece futuros perpétuos, futuros com vencimento e diferentes formas de margem. Neste guia, o foco principal será o funcionamento dos **futuros perpétuos com margem em USDT**, usando como referência o fluxo de negociação apresentado pela própria plataforma. Também veremos como escolher a alavancagem, calcular a margem, configurar stop loss e take profit, entender as taxas e fechar uma posição sem transformar uma operação pequena em um problema grande.

## O que são futuros na OKX?

Futuros são contratos derivativos que acompanham o preço de um ativo, como Bitcoin, Ethereum ou outra criptomoeda disponível na plataforma. Ao negociar o contrato, você não precisa necessariamente comprar o ativo à vista. O resultado da operação depende da variação do preço entre a abertura e o fechamento da posição.

Na prática, existem duas direções principais:

- **Posição comprada, ou long:** usada quando você espera uma alta no preço.
- **Posição vendida, ou short:** usada quando você espera uma queda no preço.

Nos contratos perpétuos, não existe uma data de vencimento fixa. A posição pode permanecer aberta enquanto houver margem suficiente, mas existe uma cobrança chamada **taxa de financiamento**. Esse mecanismo ajuda a manter o preço do contrato próximo do preço do mercado à vista.

A taxa de financiamento é trocada entre os participantes do mercado. Quando ela está positiva, as posições compradas normalmente pagam às posições vendidas. Quando está negativa, ocorre o contrário. A OKX não trata essa cobrança como uma taxa comum de abertura da operação: ela depende do contrato, do valor da posição e da direção definida no momento da liquidação.

## Antes de começar a operar futuros

Antes de abrir a primeira ordem, organize quatro pontos:

1. Crie e verifique a conta na OKX.
2. Deposite ou transfira os fundos para a conta correta.
3. Escolha o contrato que será negociado.
4. Defina quanto você aceita perder antes de pensar na alavancagem.

Na interface da OKX, os fundos podem estar na conta de financiamento enquanto a negociação de futuros exige que o saldo seja transferido para a conta de trading. No site, essa transferência fica disponível na área de ativos. No aplicativo, o caminho normalmente passa por **Ativos**, **Transferir** e a seleção da conta de destino.

A transferência não é uma ordem de compra ou venda. Ela apenas move o saldo entre áreas internas da conta. Esse detalhe parece banal, até você procurar o botão de abrir posição e descobrir que o dinheiro está na conta errada.

### Use apenas uma quantia separada para futuros

Futuros alavancados não são adequados para colocar todo o saldo disponível em uma única operação. O ideal é separar uma quantia destinada exclusivamente ao trading e manter o restante fora da posição.

A alavancagem amplia o tamanho da exposição em relação à margem. Isso pode aumentar o lucro potencial, mas também acelera as perdas e aproxima o preço de liquidação. A própria OKX alerta que o trading alavancado pode levar à perda total do capital usado na operação.

## Como encontrar o mercado de futuros na OKX

No site, abra o menu **Negociar** e procure a seção de futuros. No aplicativo, entre em **Negociar**, abra o menu de instrumentos e selecione **Perpétuo** ou outra modalidade disponível na sua conta.

Depois, você verá diferentes categorias de contratos. Entre as mais comuns estão:

- Futuros perpétuos com margem em USDT.
- Futuros perpétuos com margem em cripto.
- Contratos com vencimento.
- Contratos com margem em USDC, quando disponíveis.
- Outros produtos derivativos sujeitos à região e às regras da conta.

Para quem está começando, os contratos com margem em USDT costumam ser mais fáceis de acompanhar porque a margem, o valor da posição e o resultado aparecem em uma unidade estável. Isso não elimina o risco de variação do ativo, mas simplifica a leitura do resultado.

O contrato aparece com um nome semelhante a `BTCUSDT Perp`. Nesse exemplo, BTC é o ativo de referência e USDT é a moeda usada na liquidação. Cada contrato possui especificações próprias, como tamanho nominal, valor mínimo da ordem, alavancagem máxima e intervalo de financiamento. Essas informações devem ser conferidas no painel do contrato antes da abertura da posição.

## Margem isolada ou margem cruzada?

A escolha do modo de margem é uma das decisões mais importantes ao aprender como operar futuros na OKX.

### Margem isolada

Na margem isolada, cada posição usa uma quantidade específica de margem. Se a operação for liquidada, o risco fica limitado à margem alocada naquela posição, considerando as regras e custos aplicáveis.

Esse modo costuma ser mais simples para controlar o risco porque você consegue definir quanto será exposto em uma operação. Se uma posição usa 100 USDT de margem, o restante do saldo não entra automaticamente como proteção daquela posição.

A margem isolada também permite adicionar margem a uma posição específica quando isso fizer sentido para a estratégia. Porém, adicionar dinheiro depois que a operação começou não transforma uma posição ruim em uma posição boa. Apenas aumenta o espaço antes da liquidação e, ao mesmo tempo, aumenta o capital exposto.

### Margem cruzada

Na margem cruzada, o saldo elegível da conta pode ser compartilhado entre posições. Isso pode dar mais espaço para uma operação suportar oscilações, mas também faz com que uma perda afete uma parcela maior do patrimônio disponível.

A forma exata como a margem cruzada funciona depende do modo da Conta Unificada. A OKX informa que existem modos como moeda única, multimoeda e portfólio. No modo de moeda única, o saldo da moeda correspondente pode ser usado como margem; em configurações multimoeda ou de portfólio, a avaliação pode considerar o valor dos ativos da conta.

Para uma primeira operação, a margem isolada costuma ser mais fácil de entender. A margem cruzada pode ser útil em estratégias mais complexas, mas exige clareza sobre o saldo total que está sujeito ao risco.

## Como funciona a alavancagem?

A alavancagem determina o tamanho da posição em relação à margem inicial. Em uma simplificação:

> Margem inicial aproximada = valor da posição ÷ alavancagem

Imagine uma posição de 1.000 USDT:

- Com alavancagem de 2x, a margem inicial aproximada seria de 500 USDT.
- Com alavancagem de 5x, seria de 200 USDT.
- Com alavancagem de 10x, seria de 100 USDT.

Esses valores são uma explicação simplificada. O cálculo real depende do contrato, do preço de referência, do tamanho do contrato, das taxas e de outras regras de margem. A OKX calcula requisitos diferentes para contratos com margem em cripto e contratos com margem em USDT.

O ponto que costuma confundir iniciantes é este: **a alavancagem não reduz o risco da posição; ela reduz a margem necessária para controlar uma posição maior**. Se você abre uma posição de 1.000 USDT com 10x, uma variação de 5% contra a posição representa cerca de 50 USDT de perda antes de considerar taxas e diferenças de execução. Isso representa 50% de uma margem de 100 USDT.

Por isso, não escolha a alavancagem máxima só porque ela aparece disponível na tela. A alavancagem deve ser consequência do tamanho de posição que você decidiu assumir, não o ponto de partida da operação.

## Como abrir uma posição comprada ou vendida

Depois de escolher o contrato, o modo de margem e a alavancagem, chega a parte operacional.

### 1. Escolha o tipo de ordem

Os tipos mais comuns são:

- **Ordem a mercado:** tenta executar imediatamente pelo melhor preço disponível no livro.
- **Ordem limitada:** só executa no preço definido ou em condição melhor.
- **Ordem stop:** ativa uma ordem quando o preço atinge determinado nível.
- **TP/SL:** permite configurar take profit e stop loss junto com a ordem ou depois da abertura.

A ordem a mercado é prática quando a prioridade é entrar ou sair rapidamente. Em contrapartida, o preço final pode variar em momentos de baixa liquidez ou alta volatilidade. A ordem limitada oferece mais controle de preço, mas pode não ser executada.

Uma ordem limitada também pode ser executada imediatamente se for colocada em uma faixa que cruza o livro de ordens. Nesse caso, ela pode ser classificada como taker, e não como maker. A classificação depende de como a ordem é executada, não apenas do botão escolhido na interface.

### 2. Defina preço e quantidade

Na tela de ordens, informe o preço, a quantidade ou o valor da posição. Observe se o campo está mostrando contratos, quantidade do ativo ou valor em USDT. Essa diferença importa.

O tamanho de cada contrato não é igual em todos os mercados. Em um exemplo de BTCUSDT usado pela OKX, 100 contratos podem representar 1 BTC quando o valor nominal de cada contrato é 0,01 BTC. Outros contratos possuem tamanhos diferentes, portanto não copie a quantidade de um mercado para outro sem conferir as especificações.

### 3. Escolha Comprar ou Vender

Para abrir uma posição comprada, selecione **Comprar** ou **Abrir long**.

Para abrir uma posição vendida, selecione **Vender** ou **Abrir short**.

A nomenclatura pode variar entre o aplicativo e a versão web. O que importa é conferir a indicação da posição antes de confirmar a ordem. Uma compra pode reduzir uma posição vendida existente em vez de abrir uma nova posição, dependendo do modo de posição e das ordens já abertas.

### 4. Confirme os dados antes de enviar

Antes de clicar em confirmar, revise:

- Contrato selecionado.
- Margem isolada ou cruzada.
- Alavancagem.
- Direção da operação.
- Tipo de ordem.
- Preço.
- Quantidade.
- Preço estimado de liquidação.
- Stop loss e take profit.
- Taxa de financiamento atual.
- Taxas de trading estimadas.

A OKX mostra informações de margem e risco no painel. Use esses dados para ajustar a operação antes de enviá-la, quando ainda é barato mudar de ideia.

## Como configurar stop loss e take profit

O **stop loss** encerra a posição quando o preço atinge um nível definido para limitar a perda. O **take profit** encerra a posição quando o preço chega ao alvo estabelecido.

Nenhum dos dois garante uma execução perfeita em qualquer cenário. Em movimentos muito rápidos, o preço efetivo pode ser diferente do gatilho. Ainda assim, operar sem qualquer plano de saída deixa a decisão para o momento de maior pressão, que geralmente é quando o trader está menos racional.

Uma forma prática de planejar a posição é definir primeiro quanto você aceita perder. Depois, escolha o nível do stop e calcule a quantidade de contratos que cabe nesse limite. Fazer o contrário, escolhendo uma grande posição e colocando o stop apenas depois, costuma produzir uma perda maior do que a planejada.

Também é importante diferenciar:

- **Preço de entrada:** onde a posição foi executada.
- **Preço de marcação:** usado para avaliar a posição e ajudar nas regras de liquidação.
- **Preço de liquidação:** nível aproximado em que a margem deixa de ser suficiente.
- **Preço de stop:** gatilho definido por você.
- **Preço de execução:** preço efetivo da ordem depois que ela é acionada.

Esses preços podem não ser iguais. A posição pode ser liquidada antes de um stop ser executado se a margem atingir o limite de risco da plataforma.

## Como fechar uma posição

Para fechar uma posição comprada, você precisa vender a quantidade correspondente. Para fechar uma posição vendida, precisa comprar a quantidade correspondente.

Na aba de posições, a OKX normalmente oferece opções como:

- Fechar a mercado.
- Fechar com ordem limitada.
- Fechar parte da posição.
- Fechar a posição inteira.
- Usar TP/SL.

Se você precisa sair imediatamente, fechar a mercado tende a ser mais previsível em termos de execução, mas pode resultar em uma taxa de taker e em slippage. Se o mercado estiver tranquilo e o preço for importante, uma ordem limitada pode reduzir o custo, embora exista o risco de ela não ser preenchida. A própria OKX observa que ordens a mercado podem envolver a taxa de tomador mais alta, enquanto ordens limitadas podem ser mais baratas quando permanecem no livro.

Depois do fechamento, verifique o resultado realizado e não apenas o lucro ou prejuízo flutuante mostrado enquanto a posição estava aberta. O resultado final pode incluir taxas de abertura, taxas de fechamento e financiamento.

## Taxas de futuros na OKX

As taxas de futuros são cobradas quando a ordem é executada. Elas não são calculadas simplesmente sobre o valor da margem. A base é o valor da posição executada, levando em conta o número de contratos, o multiplicador, o tamanho nominal, o preço de execução e a taxa aplicável à conta.

A OKX usa uma estrutura de níveis. A taxa depende do perfil do usuário, dos ativos elegíveis e do volume negociado em 30 dias. A tabela abaixo resume as taxas de futuros exibidas na página brasileira de taxas consultada, mas a taxa efetivamente aplicável deve ser conferida dentro da conta antes da operação.

| Nível | Critério de volume de futuros em 30 dias | Taxa maker | Taxa taker | Acesso |
| --- | ---: | ---: | ---: | --- |
| Usuário regular | Menos de 5.000.000 USD | 0,0200% | 0,0500% | [ Abrir conta e consultar taxas](https://okx.com/join/CASH20) |
| VIP 1 | A partir de 5.000.000 USD | 0,0160% | 0,0450% | [ Ver condições da conta](https://okx.com/join/CASH20) |
| VIP 2 | A partir de 10.000.000 USD | 0,0150% | 0,0360% | [ Consultar elegibilidade VIP](https://okx.com/join/CASH20) |
| VIP 3 | A partir de 50.000.000 USD | 0,0100% | 0,0280% | [ Conferir condições para traders de maior volume](https://okx.com/join/CASH20) |
| VIP 4 | A partir de 250.000.000 USD | 0,0080% | 0,0270% | [ Acessar a OKX](https://okx.com/join/CASH20) |
| VIP 5 | A partir de 750.000.000 USD | 0,0050% | 0,0260% | [ Consultar níveis de taxa](https://okx.com/join/CASH20) |
| VIP 6 | A partir de 1.250.000.000 USD | 0,0000% | 0,0250% | [ Ver detalhes da conta](https://okx.com/join/CASH20) |
| VIP 7 | A partir de 1.500.000.000 USD | -0,0010% | 0,0230% | [ Consultar o programa VIP](https://okx.com/join/CASH20) |
| VIP 8 | A partir de 2.500.000.000 USD | -0,0025% | 0,0200% | [ Conferir regras atualizadas](https://okx.com/join/CASH20) |
| VIP 9 | A partir de 25.000.000.000 USD | -0,0050% | 0,0150% | [ Abrir a plataforma](https://okx.com/join/CASH20) |

Os critérios também podem considerar ativos sob gestão, e a própria página de taxas informa que os níveis são atualizados diariamente. Além disso, pares diferentes podem ter regras específicas. Por isso, use essa tabela como referência geral e confira o campo **Taxas** no painel do contrato escolhido.

### Maker e taker: qual é a diferença?

Uma ordem **maker** adiciona liquidez ao livro, normalmente permanecendo aberta até que outro participante aceite o preço. Uma ordem **taker** remove liquidez ao executar imediatamente contra ordens existentes.

No nível regular apresentado pela OKX para futuros, a taxa maker é de 0,0200% e a taker é de 0,0500%. Em uma posição com valor executado de 10.000 USDT, isso corresponderia, de forma simplificada, a 2 USDT de taxa maker ou 5 USDT de taxa taker por execução. Como uma operação costuma ter abertura e fechamento, o custo potencial aparece nas duas pontas.

O valor final depende da execução real e da taxa da conta. A calculadora simples não inclui necessariamente financiamento, slippage, liquidação ou eventuais particularidades do contrato.

## O que é a taxa de financiamento?

A taxa de financiamento existe principalmente nos contratos perpétuos. Ela é calculada sobre o valor da posição e pode ser paga ou recebida dependendo da taxa vigente e da direção da operação.

Os intervalos não são iguais para todos os contratos. A OKX informa que alguns mercados liquidam o financiamento a cada 8 horas, enquanto outros podem usar intervalos de 1, 2 ou 4 horas. O período específico aparece no painel do contrato. O BTCUSDT Perp, por exemplo, é apresentado no guia da plataforma com intervalo de 8 horas.

Você só paga ou recebe o financiamento se mantiver a posição no momento da liquidação correspondente. Fechar antes desse horário pode evitar aquela cobrança específica, mas não deve ser usado como justificativa para manter uma operação que já deixou de fazer sentido.

Para consultar a taxa atual, abra o contrato e selecione **Taxa de financiamento** ou **Taxa de financiamento/Contagem regressiva**. O painel costuma mostrar:

- Taxa atual.
- Taxa anualizada.
- Direção do pagamento.
- Próximo horário de liquidação.
- Limite superior e inferior.
- Histórico das taxas.

Taxa anualizada é uma projeção matemática, não uma promessa de custo ou retorno. Em períodos de forte desequilíbrio entre comprados e vendidos, o financiamento pode ficar mais alto.

## Como evitar a liquidação

A liquidação acontece quando a margem disponível deixa de ser suficiente para sustentar a posição de acordo com as regras do contrato. Ela não é simplesmente o momento em que o preço toca um número fixo calculado pelo trader.

Para reduzir esse risco:

- Use uma alavancagem menor.
- Diminua o tamanho da posição.
- Prefira margem isolada quando quiser limitar o capital exposto.
- Mantenha margem livre suficiente.
- Evite abrir várias posições correlacionadas.
- Observe o preço de liquidação e o nível de margem.
- Configure uma saída antes de entrar.
- Não aumente a posição apenas para “recuperar” uma perda.
- Confira a taxa de financiamento em operações que podem durar várias horas ou dias.

A margem de manutenção é a margem mínima necessária para manter a posição. Quando o nível de margem se aproxima do limite de risco, a plataforma pode reduzir ou liquidar a posição conforme o mecanismo aplicável. A OKX diferencia os cálculos de margem cruzada e isolada e usa elementos como saldo, P/L, margem de manutenção e taxas de liquidação.

A pior hora para aprender como funciona a liquidação é depois que ela acontece. Antes de enviar a ordem, abra os detalhes da posição e veja o preço estimado de liquidação, a margem inicial e a margem de manutenção.

## Um exemplo simples de operação

Suponha que um trader queira negociar BTCUSDT Perp com estas condições:

- Valor da posição: 500 USDT.
- Alavancagem: 5x.
- Margem aproximada: 100 USDT.
- Direção: comprada.
- Stop loss: definido antes da entrada.
- Take profit: definido em um nível diferente do stop.

O resultado da posição acompanha a variação do valor de 500 USDT, não apenas dos 100 USDT usados como margem. Uma alta de 2% representa aproximadamente 10 USDT de ganho bruto. Uma queda de 2% representa aproximadamente 10 USDT de perda bruta, antes de taxas e financiamento.

Nesse exemplo, a perda corresponde a cerca de 10% da margem inicial. Se a alavancagem fosse 20x mantendo o mesmo valor de posição, a margem aproximada cairia para 25 USDT, mas a mesma variação de 2% representaria cerca de 40% dessa margem. A exposição econômica seria a mesma; o espaço para absorver a perda seria menor.

Esse é o motivo pelo qual “usar pouca margem” não significa automaticamente correr pouco risco.

## O código CASH20 oferece 20% de retorno?

O link de convite fornecido para esta publicação utiliza o código **CASH20** e informa uma condição de **20% de retorno em comissões**. Como campanhas de indicação podem depender de região, elegibilidade, período, produto e regras da conta, confira os termos exibidos durante o cadastro e no painel de recompensas antes de considerar o benefício como garantido.

O retorno de uma campanha de indicação também não altera a mecânica de risco dos futuros. Ele não protege contra liquidação, não cobre automaticamente perdas de mercado e não substitui a conferência das taxas aplicáveis ao seu nível.

[👉 Criar uma conta na OKX com o código CASH20](https://okx.com/join/CASH20)

## Vale a pena começar pelos futuros perpétuos?

Para quem está aprendendo como operar futuros na OKX, os perpétuos com margem em USDT podem ser uma porta de entrada mais fácil de entender porque não possuem vencimento e usam USDT como referência de liquidação. Ainda assim, são produtos complexos e alavancados.

Uma sequência mais prudente seria:

1. Familiarizar-se com a interface sem enviar ordens.
2. Conferir as especificações do contrato.
3. Entender a diferença entre margem isolada e cruzada.
4. Simular o tamanho da posição e a perda máxima.
5. Começar com uma posição pequena.
6. Usar stop loss desde o início.
7. Registrar taxas e resultados.
8. Aumentar o tamanho apenas depois de compreender o comportamento da estratégia.

Não existe uma configuração de alavancagem que elimine o risco. O que muda é a relação entre tamanho da posição, margem, distância até a liquidação e capacidade de suportar uma oscilação desfavorável.

## Checklist antes de clicar em “Abrir”

Use esta lista para revisar uma operação:

- [ ] O contrato escolhido é realmente o que você queria negociar?
- [ ] A moeda de liquidação está correta?
- [ ] O modo de margem é isolado ou cruzado?
- [ ] A alavancagem está adequada ao tamanho da posição?
- [ ] Você sabe quanto pode perder nessa operação?
- [ ] O tipo de ordem é mercado ou limitada?
- [ ] O preço e a quantidade estão corretos?
- [ ] O preço de liquidação está distante o suficiente?
- [ ] O stop loss foi definido?
- [ ] O take profit faz sentido para a relação entre risco e retorno?
- [ ] A taxa de financiamento foi conferida?
- [ ] Você verificou as taxas maker e taker da sua conta?
- [ ] O saldo transferido está na conta de trading correta?

Se uma dessas respostas estiver indefinida, ainda falta uma etapa antes de abrir a posição. Em futuros, apertar o botão é a parte mais rápida. O trabalho importante acontece antes.
