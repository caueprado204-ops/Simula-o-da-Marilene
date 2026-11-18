# ✚ Simulação Marilene

Mesa de sons para a **simulação de urgência e emergência**, feita para projetar no telão.

Desenvolvido por **Cauê Prado**.

## O que tem

- **Sirene** de ambulância realista, com 3 tipos: *Ambulância (mista)*, *Toque longo* e *Toque rápido*. Enquanto toca, as bordas da tela piscam em vermelho e azul.
- **Campainha** de entrada de paciente, com 3 tipos: *Dim-dom*, *Aviso 3 notas* e *Sensor de porta*. Ao tocar, aparece uma animação: a ambulância chega, as portas do hospital abrem e a maca entra.
- A **Marilene** fica em destaque na tela.
- **Modos dos botões:**
  - *Segurar*: toca enquanto estiver pressionado.
  - *Repetir*: um clique liga e o som fica repetindo; outro clique desliga.
- **Volume:** botões de − e +, barra de volume, mudo e o botão **Parar som**.
- Os sons são gerados pelo próprio navegador (Web Audio API), sem nenhum arquivo de áudio.

## Atalhos de teclado

| Tecla | Ação |
|---|---|
| `1` | Sirene |
| `2` | Campainha |
| `Esc` / `Espaço` | Parar todos os sons |
| `M` | Mudo |
| `↑` / `↓` | Volume |
| `F` | Tela cheia |

## Como usar

É um único arquivo: abra o `index.html` no navegador. Ele também pode ser publicado direto na Vercel ou no GitHub Pages, sem precisar de build.

Os desenhos originais da Marilene estão na pasta `assets/`.
