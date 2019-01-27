---
title: Jogando Street Fighter EX2+ Online
date: '2019-01-27T01:24:22-02:00'
---
Esse guia é feito pra ser a maneira mais fácil de jogar SFEX2+ online. Já tem um link pronto.

Recomendo também que entre no nosso discord para achar partidas:

[http://discord.me/sfex2pbrasil](http://discord.me/sfex2pbrasil)

---
<a href="https://www.mediafire.com/file/2x1ggf3wctie4j8/SFEX2P_Netplay.rar/file">
<h1>Link de download do emulador</h1>
</a>


## Configurando os controles e colocando seu nick.

2. Rode o `SFEX2P.bat`

![SFEX2P.bat](https://cdn.discordapp.com/attachments/535317795395862548/538848391686520843/unknown.png)

3. Escolha `4: Offline`
4. Com o jogo aberto, aperte `alt+shift+1` e configure seus controles

![Configuração de controle](https://cdn.discordapp.com/attachments/535317795395862548/538848503225647134/unknown.png)

> **Atenção:** Cada botão será perguntado duas vezes, a terceira sendo o turbo (rapid). Apenas faça bind dos rapid pra alguma tecla qualquer no teclado.

![Configuração de controle](https://cdn.discordapp.com/attachments/535317795395862548/538850249213739008/unknown.png)

5. Aperte T, subirá uma caixa de texto no emulador, digite `/nick seunickaqui`

6. Feche o emulador

## Conectando com outra pessoa

1. Abra o `SFEX2P.bat` novamente.
2. Escolha a opção `1: Connect to _______`
3. O script te perguntará uma gamekey. A gamekey é um indentificador da partida. Você e seu oponente devem usar a mesma gamekey (Pode imaginar como uma senha para a sala)

![Perguntando sobre a gamekey](https://cdn.discordapp.com/attachments/535317795395862548/538848736021839883/unknown.png)

> Basta seu oponente repetir os mesmos passos para conectar com você, tenham certeza de combinar de usar a mesma gamekey.

----

## Extras:

<div style="border:2px solid #d61e1e; padding: 0.2rem 1rem; color:#d61e1e; width:100%; border-radius: 0.25rem;">
<p>
ESSES MODOS SÃO OPCIONAIS, VOCÊ NÃO PRECISA USAR ELES, SÃO UMA MANEIRA ALTERNATIVA DE CONECTAR.
</p>
</div>

#### Pra que servem os outros modos?
Os modos com self hosted funcionam um pouco diferente, a opção `3: [Self hosted] Host match` Abrirá uma instância do servidor do mednafen e colocará uma gamekey padrão de `1234`

O opção `2: [Self hosted] Connect` irá perguntar o ip do servidor do oponente e usar a gamekey padrão de `1234`.

Player 1 hosteia o servidor, player 2 conecta nele.

Cheque o `standard.conf` dentro da pasta do servidor e faça as alterações necessarias (certifique-se que a porta usada no `standard.conf` é a mesma que a variável `%DEFAULTPORT%` no .bat).

Você vai precisar abrir a porta que você definir, recomendo por padrão que use a porta `4046`
