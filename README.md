# Apasimant — Paisatge sonòre ASMR procedurau

Aplicacion web monopagina que genera sons ASMR **enterament sintetizats dins lo navegaire** via la Web Audio API. Degun fichier àudio extèrne — toti li sons son produches algoritmicament en tèms reiau.

**En dirècte :** [asmr.13h.be](https://asmr.13h.be)

## Declenchaires disponibles

| Declenchaire | Descripcion |
|---|---|
| Tapping | Percussions legieuras sus una superfícia |
| Scratching | Grapanhaments texturats |
| Whispering | Chuchotejanças sinteticas |
| Writing | Son d'escriptura manuscrita |
| Crinkling | Frussinament de papier/plastic |
| Page Turning | Virolhament lent de libre |
| Kinetic Sand | Sable cinetic |
| Fluffy Mic Brushing | Escoubinhament de microfòni |
| Plueio & Tempèsta Luenh | Brug rose + tronc distant |
| Riéu | Aigo que corre |

## Foncionalitats

- **Volum mestre** emé contrôle per declenchaire
- **Mòde seqüenciaire** — transitions douças automaticas en bóucle entre declenchaires
- **Sandbox interactiu** — zòna tactila/raton per declencà sons a la vòla
- **Visualizaire àudio** — canvas en tèms reiau
- **Minutièr de sòmi** — arrèst automatic a 15 min, 30 min o 1 ora
- **Lectura/pausa teclatre** (barra d'espaci)
- Interfàcia escura, responsive, sens dependéncias de costat servidor

## Stack

- HTML/CSS/JS vanilha — fichier unic `index.html`
- [Tailwind CSS](https://tailwindcss.com) via CDN
- [Lucide Icons](https://lucide.dev) via CDN
- Web Audio API (natiu navegaire)
- Deployat sus GitHub Pages emé CNAME personalizat

## Lançar en locau

```bash
# Quauque servidor HTTP static, per exemple :
npx serve .
# o
python3 -m http.server
```

Dubrir `http://localhost:3000` (o lo pòrt indicat).

