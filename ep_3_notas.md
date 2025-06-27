# Tópicos do Episódio - Formatados

## jaoleal:

### 1a. [Remove arbitrary limits on OP_Return (datacarrier) outputs](https://github.com/bitcoin/bitcoin/pull/32359)
**Links adicionais:**
- https://antoinep.com/posts/relay_policy_drama/
- https://bitcoin.stackexchange.com/questions/126208/why-would-anyone-use-op-return-over-inscriptions-aside-from-fees
- https://www.twitch.tv/videos/2451181919
-TX-Pingeon(https://github.com/stutxo/tx-pigeon) vs garbageman(https://github.com/chrisguida/bitcoin/tree/garbageman)
**Resumo:**
- "Pergunta 1" - "Resposta para a pergunta 1"

### 2a. [Withdrawing OP_VAULT (BIP-345)](https://delvingbitcoin.org/t/withdrawing-op-vault-bip-345/1670)
**Links adicionais:**
- Nenhum

**Resumo:**
- "Pergunta 1" - "Resposta para a pergunta 1"

### 4a. [Another explanation of how Ark works](https://nehanarula.org/2025/05/20/ark)
**Links adicionais:**
- Nenhum

**Resumo:**
- "Pergunta 1" - "Resposta para a pergunta 1"

### 5a. [Liquidity requirements for Lightning payments: Ark servers and LSPs compared](https://blog.second.tech/ark-liquidity-research-01)
**Links adicionais:**
- Nenhum

**Resumo:**
- "Pergunta 1" - "Resposta para a pergunta 1"

### 6a. [Tangerine Upgrade: BitVM Activation on Clementine & Core Protocol Upgrades](https://www.blog.citrea.xyz/tangerine-upgrade-bitvm-activation-on-clementine/)
**Links adicionais:**
- https://citrea.xyz/clementine_whitepaper.pdf

**Resumo:**
- "Pergunta 1" - "Resposta para a pergunta 1"

### 6a. [Arkade, a Bitcoin-native virtual execution layer](https://xcancel.com/tierotiero/status/1927724597266571282)
**Links adicionais:**
- https://citrea.xyz/clementine_whitepaper.pdf

**Resumo:**
- "Pergunta 1" - "Resposta para a pergunta 1"

## j-moreno-r-c:

### 1b. [First mainnet use of the Taproot Annex](https://xcancel.com/mononautical/status/1921180666831499737)✅✅
**Links adicionais:**
- https://xcancel.com/mononautical/status/1921557253368295733

**Resumo:Alguém botou um dickbutt e um maguinho em um taproot annex...**
- "Como isso funciona, Como um OP_PUSHDATA? a imagem tem tantos bytes?" - "Um bloco de dados que voce pode colocar depois do control block de forma opcional  mesmo custo de witness e é completamente opcional pós varint, não fica na mempool então prescisa ser mandado diretamente para o minerador atravez de slipstream... o anexo prescisa começar por 51... foi um png ou jpeg encodado para hexadecimal ou bytes..."

### 2b. [Dust Expiry: Clean the UTXO set from spam](https://delvingbitcoin.org/t/dust-expiry-clean-the-utxo-set-from-spam/1707/1)✅✅
**Links adicionais:**
- Nenhum
**Resumo:Devido ao aumento exponencial do UTXOset e da possivel desconfiaça de isso ser um spam pois a maioria tem menos de 1000 sats temos uma discussão sobre oque fazer com esses supostos spammers de UTXO, a proposta seria negalos...**
- "os utxos seriam invalidados mas o que aconteceria com as moedas,deixariam de fazer parte da rede?" - "Robbin linus fez uma proposta de limpar o utxo set partindo de idade e dust, o overhead iria ser um pouco grande... é dificil de se argumentar pois satoshis podem ser valiosos no futuro... ultrexo talvez possa ser uma solução..."

### 2b. [Remove the legacy wallet and BDB dependency](https://github.com/bitcoin/bitcoin/pull/28710)✅✅
**Links adicionais:**
- Nenhum    
**Resumo:Um banco de dados antigo e a antiga forma de legacy que hoje em dia eram dead codes foram removidos da nova versão do bitcoin, legacy vai poder ser gasto com um overhead descriptor esquisito do jeito novo.**
- "Pergunta 1" - "Resposta para a pergunta 1"

### 3b. [Remote crash due to addr message spam (part 2)](https://github.com/advisories/GHSA-qwp9-p9rr-h729)✅✅
**Links adicionais:**
- https://bitcoincore.org/en/2025/04/28/disclose-cve-2024-52919/

**Resumo:Um ataque de remote crash a nodes spamando messagens de addr o problema era relacionado a um overflow do identificador de endereços de 32 bits a solução para o problema na versão 0.29 foi dobrar o seu tamanho.**
- "Como funciona o ataque?" -  " eventualmente sendo expamado por meses ou anos pode crashar um node, por ser um identificador de 32 bits." 
### 4b. [musig2 has finally been merged in to rust bitcoin](https://github.com/rust-bitcoin/rust-secp256k1/pull/716)✅✅
**Links adicionais:**
- Nenhum
**Resumo:Musig2 conhecida como o esquema nuchuck de multsig com agregaçao de chaves usando schnoor e taproot agora foi implementado no rust bitcoin**
- "Isso ja pode ser usado para aplicações práticas?" - "aparenetemente sim"

### 5b. [Avoiding xpub+derivation reuse across wallets, in a UX-friendly manner](https://delvingbitcoin.org/t/avoiding-xpub-derivation-reuse-across-wallets-in-a-ux-friendly-manner/1644/1)✅✅
**Links adicionais:**
- Nenhum

**Resumo:Um texto propondo melhoras na ux para evitar o reuso de chaves usando o bip 48.**
- "explicação destas estratégias e de como elas funcionariam hipoteticamente?" - "ux para evitar reutilizacao de enderecos, caminhos aleatorios ou deterministicos diminuindo a probabilidade mas ainda assim tendo a possibilidade de ocorrer"

### 6b. [Bitcoin and Quantum Computing: Current Status and Future Directions](https://chaincode.com/bitcoin-post-quantum.pdf)✅✅
**Links adicionais:**
- Nenhum

**Resumo:Um Paper sobre a ameaça da computação quantica uma estimativa de tempo de implemenações de defesas, de quantidade de endereços e seus graus de riscos.**
- "Quem são estes autores?" - "dps pesquisa"

### 7b. [Weighted multisig](https://xcancel.com/mononautical/status/1921012232747421892)✅✅
**Links adicionais:Uma multsig que pode sera assinada com apenas dois terços do total de chaves no caso 11 de 20 chaves foram assinadas.**
- Nenhum

**Resumo:**
- "11 é menos de dois terços... como isso funciona?" - "as chaves tem pesos diferentes" 

### 8b. [Peach group hug](https://xcancel.com/peachbitcoin/status/1921147023262146785?s=46)✅
**Links adicionais:**
- Nenhum

**Resumo:Um esquema de concatenação de Psbts, diminuindo a quantidade de outputs**
- "Objetivos praticos? Prescisa de cordenadores?" - "mixer mais barato de withdraw sem cordenacao juntando psbts e pagndo quem tem que ser pago"



Cronograma
Warmup🌟
First mainnet use of the Taproot Annex✅
    A second JPEG has hit the annex✅
Drama🌟
Remove arbitrary limits on OP_Return (datacarrier) outputs✅
    Mempool space UTXO set report
    Ava reviews the code
    Antonie Poisont post on the topic
    Why would anyone use OP_RETURN over inscriptions aside from fees
    TX-Pingeon vs garbageman
Bitcoin🌟
Dust Expiry: Clean the UTXO set from spam✅
Legacy wallet removed✅
CVE-2024-52919 - Remote crash due to addr message spam (part 2)✅
    Bitcoin Core’s website info on the CVE
Withdrawing OP_VAULT (BIP-345)✅
musig2 has finally been merged in to rust bitcoin (musig2 my ears)✅
Avoiding xpub+derivation reuse across wallets, in a UX-friendly manner✅
Bitcoin and Quantum Computing: Current Status and Future Directions✅
Cool transaction sheenanigans🌟
Weighted multisig✅
Peach group hug✅
L2🌟
Another explanation of how Ark works✅
Liquidity requirements for Lightning payments: Ark servers and LSPs compared✅
Tangerine Upgrade: BitVM Activation on Clementine & Core Protocol Upgrades✅
    Clementine Whitepaper✅
Arkade, a Bitcoin-native virtual execution layer✅
