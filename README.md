# Administration Windows et Active Directory — Notes de cours

Notes de révision du module ASR02 (Windows Server, Active Directory, accès aux ressources, GPO), sous forme de site web statique.

Ouvrir `index.html` dans un navigateur suffit, aucune dépendance à installer.

## Publier avec GitHub Pages

1. Créer un dépôt sur GitHub et y déposer `index.html` et ce `README.md` à la racine.
2. Dans le dépôt : **Settings → Pages**.
3. Sous **Build and deployment**, choisir **Deploy from a branch**, branche `main`, dossier `/ (root)`, puis **Save**.
4. Le site est en ligne après une ou deux minutes à l'adresse `https://<utilisateur>.github.io/<depot>/`.

En ligne de commande :

```bash
git init
git add index.html README.md
git commit -m "Notes Windows et AD"
git branch -M main
git remote add origin https://github.com/<utilisateur>/<depot>.git
git push -u origin main
```

## Fonctionnalités

- Sommaire fixe avec la fiche en cours surlignée
- Filtre plein texte (sans accents) sur toutes les fiches
- Cases « Révisé » avec barre de progression, gardées dans le navigateur
- Thème clair ou sombre selon le système, version mobile et impression

## Source

Support « Module ASR02 — Administration Windows et Active Directory ». Pensez à vérifier que le support peut être diffusé avant de rendre le dépôt public.
