# Photos des montres

Deux façons d'ajouter une photo à une fiche :

## 1. Déposer un fichier ici (le plus simple)
Nomme le fichier avec l'**id** de la montre tel qu'il figure dans `data.json` :

| id dans data.json | fichier à déposer |
|---|---|
| `omega-speedmaster-moonwatch-hesalite` | `img/omega-speedmaster-moonwatch-hesalite.jpg` |
| `tissot-prx-automatic` | `img/tissot-prx-automatic.jpg` |
| `lip-himalaya-coeur-battant-40` | `img/lip-himalaya-coeur-battant-40.jpg` |

Extensions acceptées : `.jpg`, `.jpeg`, `.png`, `.webp` (testées dans cet ordre).
Depuis GitHub : bouton **Add file → Upload files**, ou glisser-déposer dans ce dossier.
Format conseillé : carré, 400×400 px environ, moins de 200 Ko.

## 2. Renseigner une URL dans `data.json`
Ajouter un champ `image` à la montre :

```json
"image": "https://upload.wikimedia.org/.../photo.jpg"
```

L'URL a la priorité sur le fichier local. Si aucune des deux n'existe,
la vignette disparaît proprement et la fiche reste bien mise en page.
