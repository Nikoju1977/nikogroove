# NikoGroove — Cyber-Fest-Noz

> **Statut portfolio (octobre 2026) — variante conservée, non sélectionnée dans la vitrine.** La version de référence retenue pour la groovebox Cyber-Fest-Noz est EBM-BRETONNE. Cette variante reste consultable pour préserver son historique et comparer les évolutions. Voir [la politique de sélection](https://github.com/Nikoju1977/Nikoju1977/blob/main/CURATION.md) et [le projet de référence](https://github.com/Nikoju1977/EBM-BRETONNE.).


**Catégorie : musique électronique & création sonore** · Studio Niko Design

Expérimentation de groovebox EBM / Breizh fonctionnant dans le navigateur. Le document principal `index.html` affiche « Cyber-Fest-Noz V2 — Groovebox EBM Breizh ». Le dépôt contient également `index.v1.html`, version antérieure.

## Lancer le projet

```bash
python3 -m http.server 8000
```

Ouvrir http://localhost:8000/ dans un navigateur récent, ou ouvrir directement `index.html` si les restrictions du navigateur le permettent.

## Dépendances et fonctionnement

L'interface et la logique sont embarquées dans les fichiers HTML. Le moteur sonore **Tone.js** est chargé par CDN et les typographies proviennent de Google Fonts : le projet n'est pas totalement autonome hors connexion. Le navigateur peut exiger un clic ou un toucher avant la lecture audio.

## Organisation du dépôt

- `index.html` — expérience principale.
- `index.v1.html` — version conservée.
- `.github/workflows/` — automatisations GitHub éventuelles.

## Positionnement

Projet **créatif et expérimental**, sans promesse de stabilité sur tous les appareils. Les ressemblances avec [EBM-BRETONNE.](https://github.com/Nikoju1977/EBM-BRETONNE.) méritent d'être évaluées avant toute fusion ou suppression : les historiques sont conservés séparément.

[Voir tous les projets classés par thème](https://github.com/Nikoju1977).
