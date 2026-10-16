# Black Friday Unicive — página de captura

Landing da live de Black Friday da **Unicive Caruaru**: **segunda, 09/11, às 19h45, ao vivo no YouTube**.
Capta a **lista VIP** (nome, WhatsApp, e-mail) e leva ao grupo do WhatsApp.

Mesma base técnica das páginas de concursos e do Colégio, com identidade da Unicive: verde-floresta
quase preto, dourado do símbolo, Lexend + Montserrat (com itálico Playfair nos destaques).

## Antes de publicar

| O quê | Onde |
|---|---|
| ⚠ Data (09/11 — confirmar) | `CONFIG.inicio` no `script.js` + textos "09/11" no `index.html` |
| Aba da planilha (hoje `BLACK_FRIDAY_UNICIVE`) | `CONFIG.sheetAba` |
| Cursos da seção "lacrados" | seção `#cursos` |

## Seções

Hero (símbolo da Unicive montado peça por peça) → faixas → MEC (selo nota máxima com link pro e-MEC)
→ mural de formatura (polaroides das fotos reais da página de captura) → cursos com preço lacrado
→ contagem → rodapé.

As três fotos da captura com marca d'água de imagem gerada por IA ficaram de fora.

## Deploy

Estático, sem build (`"framework": null`). Imagens em `assets/`, nunca em `public/`.
