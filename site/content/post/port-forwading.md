---
title: Abrindo portas no seu roteador
date: '2019-07-29T15:00:32.693Z'
---
# Abrindo portas

Esse guia vai te ensinar a setar um ip estático pra sua máquina na rede local e abrir as portas no roteador

Uma determinada porta é aberta pra um determinado dispositivo na rede (ex: porta 6000-6009 do protocolo UDP está aberta para o ip 192.168.1.3)
Se seu ip troca toda vez, isso nunca funciona. A primeira coisa é deixar esse IP Fixo, note que isso não altera em nada o seu IP Externo (o que a internet vê)

## Setando um IP Estático

- Abre o CMD
- roda `ipconfig`

Preste atenção no **Endereço IPV4** e **Gateway Padrão**

Gateway padrão Provavelmente deve ser algo tipo 192.168.1.1, esse é o endereço do seu roteador
**Endereço IPV4** é o endereço do seu PC, muito provavelmente cada vez que você liga o PC esse endereço é diferente
Você precisa fazer algo pra que ele seja sempre o mesmo.

- digite `ncpa.cpl` no cmd
- procure sua placa de rede aí ativa
- Botão direito > Propriedades
- Selecione Protocolo IP versão 4 (não mexa na caxinha do lado, só clique no nome)
- Clique no Botão propriedades
- Usar o seguinte endereço IP


Agora aqui vai depender do que tinha no ipconfig. Copie tudo igual ao que tava antes, exceto pelo **Endereço IPV4**, você tem que botar um
que não esteja sendo usado por nada na sua rede, se não funcionar tente outro, se der merda geral manda achar o ip automaticamente.

Pro DNS recomendo 1.1.1.1 e 1.0.0.1 ou 8.8.4.4 e 8.8.8.8

Ok, seu ip local está fixo agora, certifique-se que sua internet funciona. Agora é hora de abrir as portas.

## Abrindo portas

Abra seu navegador, digite o ip do Gateway padrão, deve abrir uma tela de login, digite o login e senha do seu roteador, na duvida chuta um login:admin senha:admin

Agora cada roteador é diferente.

Você pode tentar fuçar você mesmo mas eu recomendo dar uma olhada nos guias aqui: https://portforward.com/router.htm
Ignore toda e qualquer coisa sobre network utilities ou programas externos, você não precisa de nada disso.

Você também precisa saber as portas pro que você quer abrir

**GGPO/Fightcade:** 7000, 6000-6009
**Yatagarasu:** 50055-50057

Se você for jogar um jogo como melty blood, que deixa você escolher qual porta usar,
você pode usar as portas do GGPO/Fightcade no melty blood desde que o fightcade não esteja aberto.
Não podem haver duas aplicações usando as mesmas portas ao mesmo tempo.
