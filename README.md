# Press-Cute 🗞️

> Un thème Obsidian inspiré de l'esthétique de la **presse écrite** — ambiance journal papier recyclé, encre fraîche et salle de rédaction.

![Version](https://img.shields.io/badge/version-1.0.0-c8102e?style=flat-square)
![Obsidian](https://img.shields.io/badge/Obsidian-1.0%2B-7c3aed?style=flat-square&logo=obsidian)
![License](https://img.shields.io/badge/license-MIT-1a3a5c?style=flat-square)

---

## ✨ Aperçu

Press-Cute transforme ton vault en une salle de rédaction de journal. Chaque élément typographique a été pensé pour évoquer la presse écrite traditionnelle tout en restant parfaitement lisible à l'écran.

---

## 🎨 Caractéristiques

### Typographie
| Élément | Police | Style |
|---|---|---|
| **H1** | Playfair Display | Fond rouge, texte blanc, capitales — style manchette |
| **H2 → H6** | Cormorant Garamond | Bleu encre, bold italic, hiérarchie décroissante |
| **Corps de texte** | Lora | Serif élégant, justifié, espacement journal |
| **Blockquotes & Notes** | Special Elite | Machine à écrire ancienne |
| **Code** | Special Elite | Fond bleu nuit, colorisation GitHub Dark |

### Couleurs
| Nom | Valeur | Usage |
|---|---|---|
| Rouge presse | `#c8102e` | Accents, H1, bordures, listes |
| Bleu encre | `#1a3a5c` | Titres H2–H6 |
| Papier recyclé | `#b8b0a0` | Fond principal |
| Bleu nuit | `#0d1b2a` | Fond des blocs de code |

### Fonctionnalités
- 📰 **Fond papier journal recyclé** avec texture de lignes subtiles
- 🔴 **H1 sur fond rouge** — style Une de journal, texte blanc
- 🔵 **H2–H6 en Cormorant Garamond** bold italic bleu encre
- ⌨️ **Blockquotes & Footnotes** en police machine à écrire (Special Elite)
- 💻 **Blocs de code** : fond bleu nuit `#0d1b2a` + colorisation syntaxique GitHub Dark
- 🔢 **Listes numérotées** : chiffres blancs sur ronds rouges
- 🔺 **Drop cap** rouge sur le premier paragraphe
- 🏷️ **Tags** style étiquette presse rouge
- 📋 **Callouts** avec titre Cormorant Garamond bold
- 🌑 **File Explorer Focus** : dimming des dossiers inactifs

---

## 📦 Installation

### Via le gestionnaire de thèmes Obsidian *(recommandé)*
> Publication en cours — disponible prochainement dans la galerie communautaire.

### Installation manuelle
1. Télécharge la [dernière release](../../releases/latest) (fichier `.zip`)
2. Extrais le dossier `Press-Cute/`
3. Copie-le dans `.obsidian/themes/` de ton vault
4. Redémarre Obsidian
5. **Paramètres → Apparence → Thèmes** → sélectionne **Press-Cute**

```
ton-vault/
└── .obsidian/
    └── themes/
        └── Press-Cute/        ← le dossier doit s'appeler exactement "Press-Cute"
            ├── manifest.json
            └── theme.css
```

> ⚠️ Le nom du dossier doit être **exactement** `Press-Cute` (respecter la casse).

---

## 🌐 Polices requises

Press-Cute charge automatiquement ses polices depuis **Google Fonts** (connexion internet nécessaire au premier chargement) :

- [Cormorant Garamond](https://fonts.google.com/specimen/Cormorant+Garamond) — titres H2–H6
- [Lora](https://fonts.google.com/specimen/Lora) — corps de texte
- [Playfair Display](https://fonts.google.com/specimen/Playfair+Display) — H1
- [Special Elite](https://fonts.google.com/specimen/Special+Elite) — blockquotes, footnotes, code

---

## 🖥️ Compatibilité

| Plateforme | Statut |
|---|---|
| Obsidian Desktop (Windows / macOS / Linux) | ✅ Testé |
| Obsidian Mobile (iOS / Android) | ⚠️ Non testé |
| Mode clair | ✅ |
| Mode sombre | ✅ (fonctionne, optimisé pour le clair) |

---

## 📁 Structure du dépôt

```
Press-Cute/
├── theme.css          # Feuille de style principale (~950 lignes)
├── manifest.json      # Métadonnées du thème (nom, version, compatibilité)
├── screenshot.png     # Aperçu 512×288px pour la galerie Obsidian
└── README.md          # Ce fichier
```

---

## 🗺️ Feuille de route

- [ ] Screenshot officiel pour la galerie
- [ ] Support complet du mode sombre
- [ ] Variables Style Settings pour personnalisation
- [ ] Soumission à la galerie communautaire Obsidian

---

## 🤝 Contribution

Les contributions sont les bienvenues ! N'hésite pas à ouvrir une [issue](../../issues) pour signaler un bug ou suggérer une amélioration.

1. Fork le dépôt
2. Crée une branche : `git checkout -b fix/mon-correctif`
3. Commite tes changements : `git commit -m "fix: description du correctif"`
4. Push : `git push origin fix/mon-correctif`
5. Ouvre une Pull Request

---

## 📄 Licence

Distribué sous licence **MIT**. Voir [`LICENSE`](LICENSE) pour plus d'informations.

---

## 🙏 Remerciements

- Inspiré par l'esthétique de la presse écrite traditionnelle
- Colorisation syntaxique GitHub Dark via [StylishThemes/Syntax-Themes](https://github.com/StylishThemes/Syntax-Themes)
- Communauté [Obsidian](https://obsidian.md/) pour la documentation thèmes

---

<p align="center">
  Fait avec ☕ et de l'encre rouge par <strong>DOKTER</strong>
</p>
MIT License

Copyright (c) 2025 DOKTER

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
