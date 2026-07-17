<div align="center">

# órulo · Design System

**Informação é tudo.**

Sistema visual da Órulo — a maior plataforma de imóveis novos do Brasil.
Claro, sofisticado e acessível, construído sobre dois modos que se alternam
e uma base inegociável: as **cores oficiais** e a **Poppins**.

`v2` · 07/2026

</div>

---

## 👀 Ver o guia

Abra o **[`index.html`](index.html)** no navegador. É o guia visual completo e
interativo: alterna entre os dois modos (claro/escuro), copia as cores com um
clique e mostra tipografia, logo, grid, linguagem visual e o checklist.

## 📁 O que tem aqui

```
orulo-design-system/
├── index.html                     → guia visual interativo (comece por aqui)
├── docs/
│   └── diretrizes-de-criacao.md   → as diretrizes completas (fonte da verdade)
├── tokens/
│   ├── colors.css                 → cores oficiais como variáveis CSS
│   └── tokens.json                → todos os tokens (cores, tipografia, grid)
└── assets/
    └── logo/                      → wordmark (placeholders — trocar pelo oficial)
```

## 🎨 Fundamentos rápidos

**Cores oficiais (inegociável)**

| Cor | HEX | Papel |
|---|---|---|
| Azul principal | `#0037FF` | Cor-marca, fundo escuro, CTA |
| Marinho | `#01178B` | Fundo escuro premium, números |
| Branco | `#FFFFFF` | Fundo padrão do Modo Claro |
| Off-white | `#F4F6FF` | Fundo claro alternativo |
| Preto | `#3D3D3D` | Corpo de texto |
| Cinza | `#7B7B7B` | Texto secundário |
| Cinza 2 | `#BDBDBD` | Linhas e divisores |
| Neon | `#BCFF00` | Sinal: grifo, selo, glow — **máx. ~10%** |

**Proporção:** ~70% dominante · ~20% apoio · **~10% neon** (nunca superfície).

**Tipografia:** Poppins em 100% das peças, tracking padrão. Hierarquia por
tamanho + peso.

**Grid:** base de 8px · margem externa de 96px · formato-mestre 1080×1350 (4:5).

**Dois modos:** claro (editorial) e escuro (impacto/tech) se alternam no feed —
nunca 4–5 posts seguidos no mesmo modo.

## 🚀 Usar os tokens

```css
/* importe as variáveis */
@import url("tokens/colors.css");

.cta {
  background: var(--orulo-azul);
  color: var(--orulo-branco);
  border-radius: var(--orulo-raio-card);
  box-shadow: var(--orulo-sombra);
}
```

## 📌 Antes de publicar qualquer peça

Rode o **checklist de validação** (no fim do `index.html` ou na §13 das
diretrizes). Se passar nos 12 pontos, está no padrão Órulo.

---

<div align="center">
<sub>Inegociáveis: cores oficiais + Poppins. O resto evolui.</sub>
</div>
