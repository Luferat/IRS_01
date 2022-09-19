# Blog do IRS
Este é um aplicativo Web front-end experimental para testar os recursos do HTML5, juntamente com CSS3 e JavaScript.

Basicamente, o aplicativo é um pequeno blog com publicação de postagens e um sistema de comentários.

## Wireframe do tema
Mobile first
```
╔═══════════════════════╗
║       LOGOTIPO        ║  → Cabeçalho <header>
║        TÍTULO         ║ 
╠═══════════════════════╣
║ início contatos sobre ║  → Menu principal <nav>
╠═══════════════════════╣
║                       ║
║                       ║
║        CONTEÚDO       ║  → Conteúdo <main>
║                       ║             <article>
║                       ║
╠═══════════════════════╣
║    BARRA INFERIOR     ║  → Conteúdo <aside>
╠═══════════════════════╣
║       RODAPÉ          ║  → Rodapé <footer>
╚═══════════════════════╝
```
Telas maiores
```
╔══════════════════════════════════╗
║            LOGOTIPO              ║  → Cabeçalho <header>
║             TÍTULO               ║ 
╠══════════════════════════════════╣
║    início   contatos    sobre    ║  → Menu principal <nav>
╠═══════════════════════╦══════════╣
║                       ║          ║
║                       ║  BARRA   ║
║       CONTEÚDO        ║ LATERAL  ║  → Conteúdo <main>
║                       ║          ║             <article>
║                       ║          ║             <aside>
╠═══════════════════════╩══════════╣
║              RODAPÉ              ║  → Rodapé <footer>
╚══════════════════════════════════╝
```
## Mapa de navegação
```
              ┌───────┐
              │ index │
              └───┬───┘
     ┌────────────┼────────────┐
┌────┴────┐  ┌────┴────┐  ┌────┴────┐
│ artigo  │  │ contato │  │  sobre  │
└─────────┘  └─────────┘  └─────────┘
```