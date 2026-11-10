# flower 🌸

An animated **flower bouquet** drawn entirely with ASCII characters on a `<canvas>` —
stems grow from the ground, leaves unfurl, lilies bloom in 3D, fireflies drift up,
and a glowing message appears above the flowers.

## Pages

| Page | Description |
| --- | --- |
| [`/`](https://cesspanganiban211-spec.github.io/iloveyouu-babyy/) | **flower** — the ASCII bouquet with the *happy monthsary baby* message |
| [`/letter-curtain.html`](https://cesspanganiban211-spec.github.io/iloveyouu-babyy/letter-curtain.html) | Letter curtain animation |
| [`/love-code-surprise.html`](https://cesspanganiban211-spec.github.io/iloveyouu-babyy/love-code-surprise.html) | Love code surprise |

## Run locally

Open `index.html` in any browser — no build step, no dependencies.

## Tune it

Everything lives at the top of `index.html`:

- `MSG` — the message shown above the bouquet
- `MSG_AT` — second at which the message fades in
- `DY` — rows the bouquet is shifted down to make room for the message
- `settings = { wind, size, glow }` — breeze, flower size, bloom glow
