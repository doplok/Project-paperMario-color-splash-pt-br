# Paper Mario: Color Splash — Português do Brasil

Versão da tradução: **1.0.0**.

Tradução de 6.940 entradas em 48 arquivos de mensagens. Substitui os textos do idioma inglês por português brasileiro, com acentos e cedilha usando as fontes existentes do jogo.

## Compatibilidade

- Jogo de Wii U, edição USA, identificador `000500001f600a00`, versão interna `16`.
- Instalação em uma cópia extraída do jogo, com pastas `code`, `content` e `meta`.
- No Cemu, mantenha o idioma do console em **inglês (English)**.
- Outras regiões, versões e combinações com mods não foram verificadas. Mods que alteram os mesmos arquivos podem entrar em conflito.

## Instalação

1. Feche o jogo e o Cemu.
2. Localize a pasta do jogo que contém `code`, `content` e `meta`.
3. Antes de instalar, copie `content/messages/US_Final_English` e `content/fs.table` para uma pasta de backup fora da pasta do jogo. Guarde esse backup.
4. Copie a pasta `content` deste pacote para a pasta do jogo, **mesclando as pastas** e substituindo somente os 49 arquivos correspondentes. Não apague nem substitua a pasta `content` inteira.
5. Inicie o jogo com o idioma do console em inglês.

O pacote contém 48 arquivos `.msbt.lz` traduzidos e a tabela `content/fs.table` atualizada. Instale os dois juntos. Ele requer uma cópia própria do jogo e não funciona sozinho.

## Restauração

Feche o jogo e restaure do seu backup a pasta `content/messages/US_Final_English` e o arquivo `content/fs.table`, substituindo os arquivos da tradução. Não remova a pasta `content` inteira.

## Escopo e observações

- Textos desenhados em imagens e sprites não foram alterados. O aviso **“Press A to Start”** da tela inicial continua em inglês porque faz parte de uma textura.
- Fontes, executável, saves e configurações de controle do Cemu não foram alterados.
- Os 49 arquivos foram conferidos por SHA-256, e as 6.940 entradas foram relidas após a instalação. O responsável pelo projeto relatou que a tradução ficou perfeita ao experimentá-la; não foi realizado um teste documentado de toda a campanha.
- Se os diálogos permanecerem em inglês, confira o idioma do console e se os arquivos foram copiados para a mesma instalação que o Cemu está abrindo. O aviso inicial em inglês é esperado.

## Integridade

`manifest.json` registra os caminhos relativos, tamanhos e hashes SHA-256 dos arquivos originais e traduzidos. `SHA256SUMS.txt` permite conferir o conteúdo deste pacote. No Linux, dentro desta pasta:

```sh
sha256sum -c SHA256SUMS.txt
```

## Créditos

Projeto solicitado, dirigido e experimentado por doplok. Tradução, ferramentas de integração e verificações produzidas com assistência de IA pelo OpenAI Codex e agentes auxiliares.

Projeto de fãs, sem vínculo com a Nintendo. Paper Mario: Color Splash e seus elementos pertencem aos respectivos titulares. Este pacote não concede direitos sobre o jogo original.
