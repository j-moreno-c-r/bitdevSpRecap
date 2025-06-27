# A seguir esta a lista de tópicos dividida entre os participantes do episodio especificado na nomeacao deste documento.

jaoleal:

## 1a. [ctv-csfs](https://ctv-csfs.com/)
* - links auxiliares
* - Resumo:
* - Pergunta 1 - Resposta para a pergunta 1

## 2a. [Garbled circuits and BitVM3](https://delvingbitcoin.org/t/garbled-circuits-and-bitvm3/1773)
* - [bitvm3.pdf](https://bitvm.org/bitvm3.pdf)
* - Resumo:
* - Pergunta 1 - Resposta para a pergunta 1

## 3a. [Channel rebalancing research](https://delvingbitcoin.org/t/research-update-a-geometric-approach-for-optimal-channel-rebalancing/1768)
* - links auxiliares
* - Resumo:
* - Pergunta 1 - Resposta para a pergunta 1

## 4a. [Latency and Privacy in Lightning](https://delvingbitcoin.org/t/latency-and-privacy-in-lightning/1723)
* - links auxiliares
* - Resumo:
* - Pergunta 1 - Resposta para a pergunta 1

## 5a. [Announcement: new Zerolink coinjoin coordinator](https://ashigaru.rs/news/announcement-whirlpool/)
* - links auxiliares
* - Resumo: baseado no whirlpool tentantando fazer de forma mais privada e descentralizada, forkando a versao deles tetar falar das blinds signatures.
* - Pergunta 1 - Resposta para a pergunta 1

j-moreno-r-c:

## 1b. [Witnessless sync for pruned nodes](https://delvingbitcoin.org/t/witnessless-sync-for-pruned-nodes/1742/1)
* - links auxiliares
* - Resumo: Aqui temos uma proposta para nodes prunados que diminuiria os recursos de banda, com um assume valid que assume que os witnesse sejam validos e não os verificam isso pode gerar alguns problemas de segurança e parece ser meio controverso.
* - quais os dois lados da discussão? - avalibiliadade do witness voce nao tem nem o witness...  

## 2b. [Phoenixd is now supported as official lightning backend on BTCPay](https://x.com/PhoenixWallet/status/1932132318514184481)
* - links auxiliares
* - Resumo: phoenixd wallet agora está conectada com a BTCPay para pagamentos lightning...
* - Noque isso efetivamente faz diferença a wallet? como isso muda a experiência dos osuarios? - btc pay serverta usando o btcpay server que tem uma logica de loja em c#, te mais suporte para sotore things....

## 3b. [The Scroll #4: Intersection Attacks on CoinJoin Anonymity](https://spiralbtc.substack.com/p/the/-scroll-4-intersection-attacks)
* - links auxiliares
* - Resumo: Um artigo sobre um atacke possivel a baixa entropia ou vazamentos em um processo de coinjoin de funcionamento semelhante ao jogo cara a cara que com uma soma de perguntas se consegue quebrar o anonimato de alguem, me parece um ataque de intersecção mas não entendi bem como funciona, pelo o que entendi você traqueia os endereços que se relacionam associando-os a uma entidade, de forma que os endereços podemser acompanhandos pelo gasto de fee.
* - Como isso funciona técnicamente? ele trackeia pela sobra do pagamento de fee? as junções de endereços? - 

## 4b. [Zeus v0.11.0](https://blog.zeusln.com/new-release-zeus-v0-11-0/)
* - links auxiliares
* - Resumo: Nova Beta realease da Zeus wallet, com suporte a cahu(ecash wallet), novos tipos de endereço: cashu(já mencionado), Zaplocker(autocustodial endereços lightning), NWC nostr walle connect que gera endereços remotamente diretamente para o seu node, além disso temos agora a Zeus pay+ que parece ser um serviço pago com algumas vantagens como(custome LNaddress, early access a serviços, e 20% off dos canais LSP services)
* - Como funciona esses zaplockers? - 



## webpage estatica bitdevs:
Stratum v2 STARK proof demo: comecou com cleanup de spec, declarou na speces os dois modos de declaracao de template sendo apenas a declaracao da coinbase ou a declaracao completa do templatet inteiro de transacoes, o problema disso e que diexa a poool vulneravel a alguns ataques sendo que este template pode ter taxas de transacoes que nunca existiram ou invalidas analogo ao problema de block with holding(vetor de ataque que acontece quando o minerador manda provade trabalho para pool com uma dificuldade do bloco e nao manda sendo que o minerador comeca a secar a pool sendo que se acha os blocos mas nao manda para a pool...) no coinbase only mode e parecido, sendo que ele ta trabalhando sem nunca achar um bloco, a ideia e mandar um stark que comprove que realmente ta tentando achar um bloco... com zkp de forma que  quando o minerador ta declarando esse traabalho jque prova que esse trabalho realmente tem as tacas de txs  isso mitigaria o vetor de ataque e deixaria esse modo de mineracao bem atrativo...


How Stratum V2 Increases Mining:um estudo de benchmark entre stratum v1 e stratum v2 comparando os numeros com duas s19 comparando os numeros coisas de latencia tempo para propagar bloco, uma das maiores descrepancias e que quando o minerador tive minerando o proprio bloco(solo mining) a latencia fica muito menor e o protocolo funciona um pouco melhor com relacao a taxa cerca de 0.75% send oque voce tem uma taxa mais otima. 

NLightning: Uma apresentacao do mantenedor da nlightning uma implementac ao clear room da lightning em .NET, de software de qualidade entereprise.


FREE SAMOURAI:fee baixa em imagens de taproot annex, da para fazer tamo fazendo.



Degent:Epic low fee fellas basic low iimgae com taproot annex


Electrum 4.6 features submarine swaps over Nostr:um swap da lightining para onchain usando nostr, usando trapolim...  htlc e tudo mais e a cordenacao e atravez de nostr sendo que em teoria qualquer um pode ser um player.



tx estao passanddo com menos de um sat p vb e isso e dahora....



Non-confiscatory transaction weight limit:


 