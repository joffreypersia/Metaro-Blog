# Metaro Blog

Metaro Blog aide les photographes de presse, les iconographes et les rédactions à documenter ce qu’une image montre, à savoir d’où vient l’information et à conserver cette information jusqu’à la publication.

Metaro Blog helps photojournalists, picture editors, and newsrooms caption, credit, verify, and deliver images with their context intact.

## Rédiger avec les skills Metaro

Les skills se trouvent dans `.agents/skills/`. Ouvrez ce dépôt dans un agent compatible, puis indiquez le nom du skill, la langue, le public visé et les sources disponibles. Pour un guide pratique, ajoutez le logiciel, sa version et le format des fichiers si vous les connaissez.

| Skill | Quand l’utiliser |
| --- | --- |
| [`metaro-redaction-fr`](.agents/skills/metaro-redaction-fr/SKILL.md) | Rédiger, réviser ou adapter pour un lectorat francophone. |
| [`metaro-writing-en`](.agents/skills/metaro-writing-en/SKILL.md) | Draft, edit, or adapt for an English-speaking readership. |
| [`metaro-editorial-review`](.agents/skills/metaro-editorial-review/SKILL.md) | Vérifier les affirmations techniques, les légendes, les crédits et les risques liés à la publication, en français ou en anglais. |

> Utilise `$metaro-redaction-fr` pour expliquer à un photographe indépendant la différence entre le champ Creator et la ligne de crédit IPTC. Appuie-toi sur la spécification IPTC et donne un exemple fictif clairement signalé.

> Use `$metaro-writing-en` to adapt this French brief for a newsroom picture editor. Keep the IPTC property names, source links, and limits of the evidence intact.

La [charte éditoriale](editorial/charte.md) fixe les choix communs aux deux langues. La [sélection de skills et de sources](editorial/ressources.md) indique où approfondir la révision, la rédaction technique et la vérification des images.

## Premiers sujets à traiter

- **Crédit photo et droits.** Que remplir dans `Creator`, `Credit Line` et `Copyright Notice` quand une agence distribue la photo d’un indépendant ?
- **Métadonnées à la livraison.** Quels champs survivent au passage du JPEG livré au fichier effectivement servi par un CMS ? Comparer un fichier témoin, son export et sa copie publiée.
- **Légende sous délai.** Comment rédiger une légende quand la scène est claire mais que l’identité d’une personne reste à confirmer ?
- **Provenance d’une image.** Que peut-on apprendre d’une date EXIF et d’un Content Credential ? Quelles vérifications restent à faire ?
