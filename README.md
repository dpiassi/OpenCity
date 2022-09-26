# OpenCity

## Introdução
Somos o squad 12, LEPoli, composto pelo Daniel Piassi, Guilherme Piffer, Luis Silva e o Marcio Junior. Nosso case é a **Gamificação do Open Finance: Desenvolva sua cidade no Metaverso para conquistar seus sonhos na vida real!** Propusemos o desenvolvimento de um game mobile 3D do gênero simulação totalmente integrado aos eventos da jornada do usuário no Open Finance.

Como Games e Metaverso são temas cada vez mais presentes na vida dos brasileiros, especialmente dos mais jovens, concluímos que gamificar toda a **jornada do cliente no Open Finance** pode ajudar o BTG e o próprio ecossistema a atingir públicos mais leigos em relação à revolução do Open Finance. Criamos, então, uma cidade que reage às movimentações financeiras do cliente.

## Funcionalidades
As funcionalidades implementadas durante o Hackathon foram:

1. Ao adicionar um banco ao **Open Finance**, o usuário ganha aquele mesmo banco dentro de sua cidade no metaverso.
2. Uma vez que o banco está disponível, ele poderá fazer transações via pix e outras transferências (mockup).
3. No banco do BTG o usuário poderia fazer transações via pix e ted, além de poder investir em RF, ações e FIIs (mockup).
4. Indicadores importantes dentro da cidade são afetados pela saúde financeira do usuário na vida real, como: nível da felicidade da população, tamanho da população,  e 5. quantidade de moedas que são recebidas por hora.
6. Existe um dividend yield que incide em cima do valor da conta bancária real e recompensa o valor em moedas dentro do jogo. Ou seja, quanto maior for a poupança dos usuários, maior será sua remuneração em moedas digitais.
7. O nível de felicidade da cidade é influenciado positivamente por investimentos, financiamentos e empréstimos do BTG e negativamente quando se passa o limite do cartão de crédito que foi acordado pelo banco e o cheque especial da conta corrente. Para isso, há o indicador de “felicidade” da cidade, variando de 0 até 100%.

## Tecnologias
Para implementar todas essas soluções, nós utilizamos:
1. **AWS RDS** para armazenar o banco de dados relacional.
2. **AWS Lambda** para implementar as funções serverless.
3. **AWS API Gateway**, para unificar as funções serveless em uma única API.
4. Game engine **Unity 3D** para produção da front-end.
5. Bucket no **AWS S3** para armazenar o mock de usuários.
6. Todas as funções foram construídas com NodeJS.

A propósito, esta foi a primeira experiência do time com AWS. A curva de aprendizado foi gigantesca, contamos com o apoio de diversos colaboradores, em especial do Thyago Paresque, e do nosso Capitão BTG, Thiago Pereira.

## Monetização e Futuro do Projeto
De forma geral, a OpenCity pode ser monetizada via: in-app purchases, anúncios direcionados (impulsionamento), e como marketplace de produtos financeiros. Este projeto abre a possibilidade para, por exemplo, uma corretora de seguros vender seu produto através da OpenCity e pagar um fee por isso. Estas são algumas sugestões de melhorias futuras:

1. Gastos básicos de luz, água e internet podem ser refletidos na plataforma, incentivando um controle de gastos maior para o usuário.
2. Opção de chamar amigos para passear por sua cidade. Isso ajuda a divulgar ainda mais a plataforma e trazer mais clientes ao BTG.
3. Ações de empresas em sua carteira geram empreendimentos virtuais na cidade (por exemplo, posto de gasolina da Petrobras).
4. Possibilidade de compartilhar com amigos a abertura de conta em outros bancos e corretoras. Com isso, além de proporcionar “provas sociais” sobre a qualidade de cada instituição, ainda estimula o “desapego” às instituições financeiras.
5. Desenvolver um sistema de missões e conquistas para incentivar ainda mais o usuário a utilizar a plataforma do BTG enquanto se entretêm e aprendem melhor sobre gerenciamento do seu patrimônio.
6. Conexão com wearables para obtenção e conexão de dados de saúde. Por exemplo, o seu desempenho na prática de atividades físicas e condições cardíacas afeta parâmetros do Game. As entradas, neste caso, seriam devices como Apple Watch e Mi Band.
7. Possibilidade de comercializar ativos digitais como edifícios, casas, ornamentações da cidade, dentre outros, permitindo que uma taxa da venda desses ativos vá para o BTG.
8. Dependendo do perfil do investidor (suitability): ele(a) consegue ver a reação de sua cidade se alterar com base no seu perfil de risco e situação atual de sua carteira de ativos.

Resumidamente, a nossa proposta agrega valor ao BTG como uma ponte entre o público leigo e desinteressado sobre finanças e o Open Finance. Ou seja, **não** se trata de uma solução que busca a intercessão entre o Open Finance e o mercado de Games, mas sim **uma solução que abrirá as portas dos consumidores de games mobile (3.5 bilhões da população mundial) para o Open Finance**.

## Links úteis
- [Pitch Inicial](https://docs.google.com/presentation/d/1nKYlO588n5BFxUayJCHv0Heqg_4Yy5C3w3-Vfi6ETyk/)
- [Metaverso: tudo sobre o mundo virtual tendência entre os investidores | InfoMoney](https://www.infomoney.com.br/guias/metaverso/)
- [Metaverse Market size worth $ 824.53 Billion, Globally, by 2030 at 39.1% CAGR: Verified Market Research®](https://www.fortunebusinessinsights.com/metaverse-market-106574)
- [Metaverse Market Size & Share Forecast [2022-2029] (fortunebusinessinsights.com)](https://www.fortunebusinessinsights.com/metaverse-market-106574)
- [Brasileiros acreditam mais no metaverso que média mundial, diz pesquisa do Ipsos - Época Negócios | Tecnologia (globo.com)](https://epocanegocios.globo.com/Tecnologia/noticia/2022/06/brasileiros-acreditam-mais-no-metaverso-que-media-mundial-diz-pesquisa-do-ipsos.html)
