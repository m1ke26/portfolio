# Imagens do dossier — /lair (estética CIA)

As imagens que aparecem no **lado direito** do player. São escolhidas
**aleatoriamente** a cada música (não estão associadas a nenhuma faixa).

## Nome do ficheiro
Qualquer nome serve — são um "pool" aleatório. Sugestão: simples e sem espaços,
ex: `01.jpg`, `truman.jpg`, `langley.jpg`. Larga quantas quiseres (4, 10, 20…).

## Formato da imagem
- **Cor:** não importa — o site aplica **preto e branco + grão/scanlines** por CSS,
  por isso todas ficam com o mesmo look, mesmo que as originais sejam a cores.
- **Orientação:** de preferência **horizontal (landscape)**, tipo foto de arquivo.
  São recortadas para encher o painel (`object-fit: cover`), põe o essencial ao centro.
- **Tamanho:** ~1200px de largura chega. < 500 KB cada, idealmente.
- **Formato:** JPG (fotos) ou PNG.

## Direitos
Fotos históricas do governo dos EUA (pré-1978, tipo arquivo CIA/National Archives)
são normalmente **domínio público** — seguras. Evita fotos modernas com copyright.

## Depois de as adicionares
Diz-me e eu ligo-as ao player (num site estático tenho de registar a lista dos
ficheiros no código — é rápido). No site ficam em `/dossier/<ficheiro>`.
