# com.Sololevelling.app  
## 📘 Documentation Git / GitHub

## 🚀 Initialiser un dépôt Git
```bash
git init
git remote add origin <url_ssh>
```

## ➕ Ajouter des fichiers et envoyer sur GitHub
```bash
git add .
git commit -m "commentaire"
git push origin main
```

## 🌿 Créer une branche
```bash
git checkout -b develop
```

## 🔄 Bonne pratique : Pull Request & Revue de code
1. Créer une branche pour une nouvelle fonctionnalité.
2. Faire les modifications dessus.
3. Envoyer la branche sur GitHub :
```bash
git push origin develop
```
4. Sur GitHub → ouvrir une Pull Request vers `main`.
5. Faire la revue de code puis fusionner.

