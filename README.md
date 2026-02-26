# Press-Cute Theme - Full Press Showcase (V1)
Ce fichier est un exemple complet pour tester le thème **Press-Cute V1** avec tous les éléments hiérarchiques et fonctionnalités typographiques.
# H1 - Manchette Principale
## H2 - Titre de Rubrique
### H3 - Sous-titre de Section
#### H4 - Détail Standard
##### H5 - Note Informative
###### H6 - Point de Référence
---
## 📂 File Explorer Focus (V1)
*Survolez l'explorateur de fichiers pour voir l'effet de dimming sur les dossiers inactifs.*
*Le chemin actif sera mis en valeur sur la note actuellement ouverte.*
---
## 📍 Listes Hiérarchiques (V1)
*Vérifiez comment les formes et couleurs des puces s'héritent dans le système Press-Cute :*
- Niveau 1 : Rouge Presse - Carré plein (■)
    - Niveau 2 : Rouge Foncé - Carré vide (□)
        - Niveau 3 : Encre - Flèche (▷)
            - Niveau 4 : Bleu Encre - Diamant (◇)
                - Niveau 5 : Bleu Encre clair - Cercle (○)
                    - Niveau 6 : Bleu Nuit - Point (•)
---
## 🔢 Listes Numérotées (V1)
*Les chiffres s'affichent en blanc sur un rond rouge — style repère de journal :*
1. Premier article à la Une
2. Reportage de fond
3. Tribune libre
4. Communiqué de presse
5. Revue de presse internationale
---
## 📑 Callouts Style Encadré Presse (V1)
*Bordures rouges et typographie Cormorant Garamond :*
> [!note] Note de Rédaction
> Ceci est un **callout note**. Remarquez la bordure rouge à gauche et le titre en Cormorant Garamond bold italic.
> [!warning] Alerte Rédacteur en Chef
> Design presse pour les avertissements système.
> [!abstract] Archives Froides
> Les callouts utilisent un fond légèrement teinté et des bordures haute visibilité.
---
## 💻 Blocs de Code & Style Terminal
Voici un exemple de code inline : `git push origin master`
```bash
# Simulation Terminal
$ npm install press-cute-theme
$ obsidian --launch-pressroom
```
```javascript
function initPressHierarchy() {
    const paletteEncre = {
        h1: '#c8102e', // Rouge Presse
        h2: '#1a3a5c', // Bleu Encre
        h3: '#1a3a5c'  // Bleu Encre
    };
    return "Prêt à publier";
}
```
```python
# Exemple Python — colorisation GitHub Dark
class Journal:
    def __init__(self, titre: str, rubrique: str):
        self.titre = titre        # manchette principale
        self.rubrique = rubrique  # section du journal

    def publier(self) -> str:
        return f"[PRESSE] {self.rubrique} — {self.titre}"

edition = Journal("Titre à la Une", "Politique")
print(edition.publier())
```
---
## 🏷️ Tags & Métadonnées
Les tags utilisent une bordure rouge et un effet hover :
#presse #une #archives #reportage #press-cute
---
## 📊 Palette Typographique Press-Cute
| Élément | Police | Couleur | Identité Visuelle |
| :--- | :--- | :--- | :--- |
| **H1** | Playfair Display | Blanc sur `#c8102e` | 🔴 Manchette — fond rouge |
| **H2** | Cormorant Garamond | `#1a3a5c` | 🔵 Rubrique principale |
| **H3** | Cormorant Garamond | `#1a3a5c` | 🔵 Sous-rubrique |
| **H4** | Cormorant Garamond | `#1a3a5c` | 🔵 Détail standard |
| **H5** | Cormorant Garamond | `#1a3a5c` (75%) | 🩵 Note informative |
| **H6** | Cormorant Garamond | `#1a3a5c` (55%) | ⚪ Référence archive |
| **Corps** | Lora | `#1a1612` | 📰 Texte justifié |
| **Blockquote** | Special Elite | `#1a1612` | ⌨️ Machine à écrire |
| **Code** | Special Elite | `#e6edf3` | 💻 Fond bleu nuit |
---
## 🔗 Navigation & Tâches
- [[Lien Interne]] (style presse)
- [Lien Externe](https://github.com/ledokter/obsidian-press-cute-theme)
- [ ] Article en cours de rédaction
- [x] Article publié en ligne
---
## 📝 Formatage du Texte
**Texte en gras** (Cormorant Garamond rouge capitales — style titre secondaire)
*Texte en italique* (Lora italic — style légende photo)
~~Texte barré~~ (correction rédactionnelle)
==Texte surligné== (mise en valeur éditoriale)
---
## 📜 Notes de Bas de Page & Citations
> « Dans la presse, le premier devoir est d'informer. Le second est de ne jamais ennuyer le lecteur. »
> — *Archives de la Rédaction*

Voici une note de bas de page pour référence ultérieure[^1].

[^1]: Vérifiée par le comité éditorial — en Special Elite, style machine à écrire.

---
## Fin du Showcase
V1.0 - Forgé par DOKTER 🗞️✨


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
