# Spawn: In the Demon's Hand — Tradução PT-BR (Dreamcast)

Tradução para português do Brasil de **Spawn: In the Demon's Hand**, de Dreamcast (Capcom, 2000).

|                      |                                                                                                            |
| -------------------- | ---------------------------------------------------------------------------------------------------------- |
| **Versão do patch**  | v1.0                                                                                                       |
| **Jogo base**        | Spawn: In the Demon's Hand, **EUA**, código T-1216N, versão **1.000**                                      |
| **Formato do patch** | `.dcp`, para o [Universal Dreamcast Patcher](https://github.com/DerekPascarella/UniversalDreamcastPatcher) |
| **Arquivo**          | `Spawn - In the Demon's Hand (PT-BR v1.0).dcp`                                                             |
| **MD5 do patch**     | `bd94e0984d216b103579be5c6a4de84d`                                                                         |

> **Esta tradução foi feita com o auxílio de inteligência artificial (IA).**
> Valorize as equipes e os romhackers que traduzem jogos com o próprio esforço, conhecimento e dedicação, sem precisar desse tipo de ferramenta.

> **Este patch é gratuito e sempre será**, feito de fã para fã. Não venda o patch, cópias do jogo já traduzido ou discos com ele.

---

## Como aplicar

### Do que você precisa

1. **Universal Dreamcast Patcher (UDP)**, versão 2.0 ou mais nova. Baixe na [página de releases](https://github.com/DerekPascarella/UniversalDreamcastPatcher/releases). Ele roda no Windows, no Linux e no macOS.
2. **O patch:** o arquivo `.dcp` deste repositório.
3. **A sua imagem do jogo original americano, versão 1.000.** O UDP aceita:
   - **GDI** (por exemplo, o dump TOSEC "Spawn - In the Demon's Hand v1.000 (2000)(Capcom)(US)[!]");
   - **CUE/BIN** (Redump);
   - **CHD**.

Este repositório **não contém o jogo**. Use a sua própria cópia.

O patch **não funciona** com a versão japonesa (v1.003) nem com imagens já modificadas.

Para conferir uma imagem GDI TOSEC, o MD5 das faixas é:

| Faixa         | MD5                                |
| ------------- | ---------------------------------- |
| `track01.bin` | `faf97640e190b5ebf668ced5f2b41b45` |
| `track02.raw` | `87af6d21a8b10aeffb90874118531e29` |
| `track03.bin` | `97b6bdcd0ff1612f7323d0a10058217b` |

### Passo a passo

1. Abra o Universal Dreamcast Patcher e vá à aba **Apply Patch**.
2. Em **Source disc image**, selecione o `.gdi`, `.cue` ou `.chd` do jogo original.
3. Em **DCP patch file**, selecione `Spawn - In the Demon's Hand (PT-BR v1.0).dcp`.
4. Em **Patched disc image format**, escolha o formato de saída (GDI, CUE/BIN ou CHD).
5. Em **Patched disc image output folder**, escolha onde salvar.
6. Clique em **Apply Patch**.

O resultado fica na pasta **`Spawn - In the Demon's Hand (PT-BR v1.0) [GDI]`** (ou com o formato que você escolheu).

Se aparecer um erro dizendo que o patch não pôde ser aplicado, a imagem de origem não é a americana v1.000 original.

### Onde jogar

- **Emuladores:** Flycast e outros emuladores de Dreamcast que abrem GDI, CUE/BIN ou CHD.
- **Console:** Dreamcast com emulador de drive óptico (GDEMU, MODE, USB-GDROM etc.), usando a imagem gerada.

---

## O que foi traduzido

- **Tela de abertura nova:** um aviso de 5 segundos no boot, com o crédito da tradução, o aviso sobre o uso de IA e a regra de distribuição gratuita.
- **Tela de título:** PRESSIONE START e o crédito da tradução.
- **Menu principal:** MODO ARCADE, MODO TORNEIO, REDE, OPÇÕES, SITE, GALERIA.
- **Opções e configuração de botões:** todas as opções, valores, a legenda dos botões e o aviso de controle desconectado.
- **Memory Card / VMU:** todos os avisos e mensagens de erro.
- **Seleção de modo, de jogadores e de personagem**, incluindo o botão ALEATÓRIO.
- **Handicap e seleção de arena**, com os nomes de todas as arenas.
- **Telas de carregamento antes da luta:** objetivos, tempo limite, times e partidas.
- **Durante a partida:**
  - objetivos;
  - mensagens grandes (DESTRUA O INIMIGO, FASE VENCIDA, VOCÊ FOI DERROTADO!…);
  - dicas e avisos;
  - rótulos do HUD (VELOC., DEFESA, PODER, ARMAS, VIDA, RADAR);
  - pausa, continue e placar;
  - falas dos chefes.
- **Modo Torneio:** títulos, times, fases, pontuação, meta de pontos e FASE CONCLUÍDA.
- **Galeria e coleção de itens:** textos e os nomes de todos os 55 itens.
- **Ranking do attract mode.**
- **Finais dos personagens:** todos os textos dos finais, redesenhados nas imagens.
- **Acentos:** letras acentuadas foram desenhadas nas fontes do jogo (Á, É, Í, Ó, Ã, Ê, Ç, á, é, ó, ú, ã, ê, ç, conforme a fonte).

---

## O que ainda não foi traduzido

Contribuições são bem-vindas.

| Parte                                                 | Situação                                                                              |
| ----------------------------------------------------- | ------------------------------------------------------------------------------------- |
| **Vídeos** (abertura e demais `.SFD`)                 | Como no original. A abertura tem música cantada em inglês                             |
| **Modo online** (telas do lobby e de conexão)         | Como no original, em inglês                                                           |
| **Nomes dos itens durante a partida e nos finais**    | Traduzidos, mas **sem acentos**: a fonte usada nessas telas não tem letras acentuadas |
| **Nomes próprios** (personagens, chefes, "THE MAFIA") | Mantidos em inglês, de propósito                                                      |
| **Áudio** (vozes e música)                            | Como no original                                                                      |

---

## Problemas conhecidos

- Nenhum problema conhecido até agora.
- A tradução foi testada no emulador Flycast e num Dreamcast real.
- Achou algum erro (texto cortado, letra estranha, travamento)? Abra uma **issue** com um print da tela e diga onde aconteceu.

---

## Créditos

| Função                                        | Quem                                                                         |
| --------------------------------------------- | ---------------------------------------------------------------------------- |
| Tradução, romhacking e testes                 | **Imphostil** — [youtube.com/@imphostil](https://www.youtube.com/@imphostil) |
| Assistência de IA (análise, scripts e textos) | Claude (Anthropic)                                                           |
| Universal Dreamcast Patcher e formato DCP     | Derek Pascarella                                                             |
| xdelta3                                       | Joshua MacDonald                                                             |
| Emulador usado nos testes                     | Flycast                                                                      |
| Dreamcast                                     | GDEmu                                                                        |

**Fontes livres** usadas para redesenhar os textos nas imagens:

- **Uncial Antiqua** (Astigmatic)
- **PT Sans Narrow** (ParaType)
- **Oswald** (The Oswald Project Authors)
- **Patrick Hand SC** (The Patrick Hand Authors)
- **Liberation Sans** (Red Hat / Google)
- **DejaVu Sans** (Bitstream / DejaVu)
- **GNU FreeMono** (GNU FreeFont)

**Agradecimento especial** aos grupos de tradução e aos romhackers que, por anos, trabalharam à mão, sem IA e sem receber nada. Foi graças ao trabalho e ao conhecimento que eles compartilharam que projetos como este se tornaram possíveis.

---

## Aviso legal

- Este é um projeto de fã, **sem fins lucrativos** e sem ligação com a Capcom, a Todd McFarlane Productions ou a SEGA.
- _Spawn_ é marca registrada de Todd McFarlane Productions, Inc. O jogo pertence aos seus respectivos donos.
- Este repositório contém **apenas o patch**, ou seja, as diferenças entre os arquivos originais e os traduzidos, e **nenhum arquivo do jogo**.
- Não publique imagens do jogo (`.gdi`, `.bin`, `.cue`, `.chd`) nem links para elas nas issues deste repositório.
