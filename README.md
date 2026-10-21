# rayane.silush.com

Mon portfolio et mon CV. Tout ce qui est poussé sur `main` est en ligne environ 1 minute
plus tard (Cloudflare Workers Builds).

## Ce qu'il y a dans ce dépôt

| Fichier | Rôle |
|---|---|
| `public/index.html` | La page du site (texte en anglais) |
| `public/Rayane_Yayaoui_Resume.pdf` | Le CV téléchargeable depuis le site |
| `cv/Rayane_Yayaoui_Resume.docx` | Le même CV en Word, à modifier |
| `public/404.html` | Page « introuvable » |
| `public/robots.txt`, `public/sitemap.xml` | Pour Google |
| `public/_headers` | En-têtes de sécurité (ne pas toucher) |
| `wrangler.json` | Configuration Cloudflare (ne pas toucher) |

## Modifier le site

### 1. Le plus simple : depuis github.com (ordinateur ou téléphone)

1. Ouvrir `public/index.html`, cliquer sur le crayon ✏️.
2. Changer le texte voulu (chercher avec Ctrl+F). Ne modifier que le texte entre les balises,
   par exemple ce qui est entre `<li>` et `</li>`.
3. « Commit changes… » → « Commit changes ». En ligne en environ 1 minute.

Exemple, ajouter une ligne à l'expérience chez Speed North America : dans la section
`My path`, sous `Speed North America · Wooster, OH`, copier la ligne `<li>…</li>` et changer
son texte.

### 2. Avec un assistant (Copilot gratuit dans GitHub, ou Claude)

Lui demander en français, par exemple :

> Dans public/index.html, ajoute à mon expérience chez Speed North America : « Prepare the
> monthly reporting package for the French parent company ». Garde le même style.

Relire la modification proposée, puis valider. Avec Claude (claude.ai relié à GitHub, ou
Claude Code), on peut aussi lui demander de mettre à jour le Word et la PDF.

## Mettre à jour le CV PDF

1. Télécharger `cv/Rayane_Yayaoui_Resume.docx`, le modifier dans Word.
2. Fichier → Exporter → PDF, avec exactement le nom `Rayane_Yayaoui_Resume.pdf`.
3. Sur github.com : dossier `public/` → « Add file » → « Upload files » → déposer la PDF
   (elle remplace l'ancienne) ; déposer aussi le .docx modifié dans `cv/`.

Règles pour que le CV reste lisible par les logiciels de recrutement (ATS) :
une seule colonne, pas de tableau, pas de photo, pas d'icône, titres standards
(Professional Summary, Skills, Professional Experience, Education), une page.
**Pas de téléphone ni d'e-mail personnel sur la version publique** : utiliser
`rayane@silush.com` (transféré vers ma boîte). La version avec mon téléphone, je l'envoie
seulement directement aux recruteurs.

## En cas d'erreur

Le site ne s'affiche plus correctement ? Sur github.com, onglet « Commits », ouvrir le
dernier commit qui fonctionnait et cliquer « Revert », ou demander à Namoussi.

## Avant chaque modification

- Rien d'inventé : chaque chiffre ou réalisation doit pouvoir être expliqué en entretien.
- Les chiffres font la différence aux États-Unis (« réduit la clôture de 10 à 6 jours »).
