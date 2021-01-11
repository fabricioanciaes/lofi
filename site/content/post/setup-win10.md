Isso é um conjunto de scripts e ferramentas que eu uso pra instalar os programas que eu preciso da maneira mais rápida e preguiçosa possível, eu só rodo isso aqui tudo:
### Script de debloat do windows 10:
Roda no powershell como admin:
```iex ((New-Object System.Net.WebClient).DownloadString('https://git.io/JJ8R4'))```
Instala o chocolatey, instala os programas que você usa, instala o powertoys, desabilita cortana, desabilita o onedrive, clica no essentials, Security no low ou no high fica a seu critério (eu uso no high), windows update default settings pra mim é ok, nao gosto de deixar desatualizado.
### Ativação do windows:
Baixa o **massgravel**: [https://github.com/massgravel/Microsoft-Activation-Scripts](https://github.com/massgravel/Microsoft-Activation-Scripts)
Roda a versão all in one, escolhe o método de ativação (eu faço por HWID)
### Script de instalação do WSL2 (pra devs)
Link do Repositório: [https://github.com/Layer8Err/WSL2setup](https://github.com/Layer8Err/WSL2setup)
Roda no powershell como admin:
```iex ((New-Object System.Net.WebClient).DownloadString('https://git.io/JfKrM'))```
WSL é uma integração do linux com windows, assim eu crio um ambiente de desenvolvimento confiável ao invés de usar o windows. Só que ele é muito bem integrado com o windows. **Não esqueça de ligar a virtualização na bios da sua placa mãe**
---
### Instalação de programas (Opcional, pessoal)
Essa é a lista de programas que eu normalmente uso no meu pc.
Precisa ter chocolatey instalado, qualquer coisa você pode instalar por fora ou clicar no botão do install chocolatey que tem no debloater do windows 10.
no cmd ou powershell roda:
```
choco install 7zip vscode microsoft-windows-terminal transmission mpv youtube-dl obs-studio sharex chromium discord audacity python nvm ffmpeg handbrake irfanview
```
O que cada um desses programas é:
- **7zip**: Mais eficiente que o winrar, e gratuito.
- **vscode**: Editor de texto, gosto bastante.
- **microsoft-windows-terminal**: Terminal pro windows, uso em conjunto com o WSL2.
- **transmission**: Cliente de torrent, o mais minimalista.
- **mpv**: Player de vídeo. UI não é a das melhores mas tem algoritmos de scaling bom, output de open GL, gerenciamento de cor de verdade, free e open source e ainda toca streams de video quando usado junto com youtube-dl
- **youtube-dl**: utilidade pra baixar videos de sites de streaming como youtube, twitch, etc.
- **obs-studio**: Software pra streams e gravação.
- **sharex**: Utilidade pra upload de screenshot e gravação de desktop, também recorta porções da tela.
- **chromium**: Chrome só que sem as coisas proprietárias, mas ainda tá na botnet do google hue
- **discord**: Programa de chat da galera jovem
- **audacity**: Edição de áudio
- **python**: Linguagem interpretada, algumas coisas acabam usando python então é útil ter. Pra scripts rápidos e automação.
- **nvm**: Script pra instalação do Node.js, prefiro instalar pelo nvm pois fica mais fácil de trocar entre versões diferentes do Node.
- **ffmpeg**: Utilidade de encoding de video por linha de comando.
- **handbrake**: Encoding de video, por gui agora.
- **irfanview**: Viewer de imagens no windows.
