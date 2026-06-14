# Capas dos vinis — meu ardio

Imagem que aparece no centro do disco (o "label" redondo) de cada música.

## Nome do ficheiro (importante)
Usa **exatamente o mesmo nome** do ficheiro de áudio correspondente, mas com extensão de imagem.
Assim consigo associar a capa à música automaticamente.

| Música (em /musica) | Capa (aqui em /vinis) |
|---|---|
| make-u-whole.mp3        | make-u-whole.png        |
| street-in-the-rain.mp3  | street-in-the-rain.png  |
| a-fresh-energy.mp3      | a-fresh-energy.png      |
| blue-monday.mp3         | blue-monday.png         |
| never-let-go-of-me.mp3  | never-let-go-of-me.png  |
| we-do-what-we-want.mp3  | we-do-what-we-want.png  |

## Formato da imagem
- **Forma:** quadrada (1:1) — é recortada num círculo automaticamente, por isso põe o
  conteúdo importante no centro.
- **Tamanho:** 500x500 px (mínimo 256x256) — para ficar nítida em ecrãs retina.
- **Formato:** PNG ou JPG. (Se usares JPG, diz-me, ou mantém PNG para eu não ter de mexer no código.)
- **Peso:** idealmente < 300 KB cada (otimiza para a página carregar rápido).

Se uma música não tiver capa, o disco fica simplesmente preto liso — nada parte.

No site ficam acessíveis em `/vinis/<ficheiro>.png`.
