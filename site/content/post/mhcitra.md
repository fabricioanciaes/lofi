---
title: Jogando MHXX / MH4U via citra (Online)
date: '2021-04-01T00:48:26Z'
---

### Download do emulador
[Rasp's Citra custom build 1472](https://mega.nz/file/t0s2FYiC#MTMRbMVaqfvfXxtBnpRECzbIQzRYhOkstakvt_2s8SU)
[Batch pra desencriptar os jogos (.CIA/.3DS)](https://gbatemp.net/download/batch-cia-3ds-decryptor.35098/download?version=35152)

### Download dos CIA
- [MHXX (Base)](https://hshop.erista.me/landing?id=20134)
- [MHXX (English patch V5 + Update)](https://hshop.erista.me/landing.html?id=6774)
- [MH4U (Base)](https://hshop.erista.me/landing?id=2120)
- [MH4U (Update 1.4)](https://hshop.erista.me/landing?id=2860)

### Download das Texturas HD

#### MHXX
- [UI](https://drive.google.com/file/d/113xJ-8rO0UvHQDnBZQ3vuL8Ve0K6k24u/view?usp=sharing)
- [Villages](https://drive.google.com/open?id=1DiIQkgbvydL9fkgdcVR7bONENJz_a_Ho)
- [Environments](https://drive.google.com/open?id=1F4UnwyqteiE-UOafvi8X9pwRPsp1Iz3F)
- [Monsters](https://drive.google.com/open?id=1tRCMRRxNVsvQIkuAyc1zHvepSlTHiW4C)
- [Armors](https://drive.google.com/file/d/1YSzbwsamQ1GqXh3jnmP4rJ2PQj8cLmeg/view?usp=sharing)
- [Weapons](https://drive.google.com/file/d/1AcAekoa_0f2bB0NKRqvbhQs8BHvluQWB/view?usp=sharing)

#### MH4U
- [UI (186MB)](https://drive.google.com/file/d/1PAC2oAML0yHDM25k58fl4cPHQU4lGcT1)
- [Models (Monsters/NPCs/Characters) (560MB)](https://drive.google.com/file/d/1N_8Z0as_GJmdrl7C9NMuUx8UAlOGbZmd)
- [Armor (2.7GB)](https://drive.google.com/file/d/1-elvKBmsLEK7bpw5HfR7p1V5Guy_i0yu)
- [Weapons (1GB)](https://drive.google.com/file/d/17sQCkbTYGBQlrPviRl2coUXavBa3jRv0)
- [Maps (1.1GB)]( https://drive.google.com/file/d/1no7SDbEItuBpVqOWhvrmTFD2fxc2byKd)
- [Other (Effects/Palicos/Pitfall) (117MB)](https://drive.google.com/file/d/169ql1BH6QzXRcxAMpu8R1i7eV7BhBzsZ)
- [Alternate Button Textures](https://drive.google.com/drive/folders/18CsXVT7_bQvZZbE_2Yvibcs3GIBDO8tx)

----

### Descriptografando os CIAs

Pegue o batch pra desencriptar os arquivos cia/3ds, coloque seus CIA dos updates e do jogo base todos dentro da pasta do Batch CIA 3DS Decryptor e rode o batch, ele automaticamente vai processar esses arquivos e remover a criptografia deles.

Video de exemplo: https://www.youtube.com/watch?v=XmWkReCT_34

Abra o `citra-qt.exe`, vá em `File > Install CIAs` e escolha os CIAs descriptografados que você acabou de fazer.

Depois disso os jogos devem aparecer na sua lista de jogos logo na tela inicial do Citra.


### Cheats essenciais
Abra o jogo, `Emulation > Cheats` adcione um novo cheat
Esses cheats (tirando o 30fps lock do MH4U) são essenciais pro jogo rodar legal.

**MHXX**
- 60 FPS Unlock

```
0088E584 EEF01A49
```

**MH4U**
- Remove 3D (Aumenta FPS Drasticamente)

```
610572CC 00000000
B10572CC 00000000
00006BA8 010F036E
D2000000 00000000
```
- 30 FPS LOCK (pra pcs fracos e celulares)

```
61057194 00000000
B1057194 00000000
00000030 41F00000
D2000000 00000000
```

### Instalando Texturas HD

Com o jogo fechado, Vá em `Emulation > Configure`, na barra lateral vá em `Graphics` e marque `Use Custom Textures`.

Clique com o botão direito no ícone do jogo na lista de jogos do Citra, `Open custom texture location`

Coloque as texturas lá dentro da seguinte forma:

![https://i.imgur.com/x9BhR9J.jpg](https://i.imgur.com/x9BhR9J.jpg)
