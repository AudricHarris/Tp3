**Nom :** Audric HARRIS  
**Groupe :** A1 groupe 1  
**Année :** BUT1  
**Binôme :** [Nom du partenaire]  

**IUT Le Havre - Cours GIT**  

---

### Compte-rendu TP3 – Travail collaboratif avec GitHub

Ce TP avait pour objectif de découvrir le travail collaboratif via GitHub en implémentant un marché de crypto-monnaies avec gestion de portefeuilles.

---

#### 1. Configuration initiale du projet

- Création du dépôt `tp3` par Athos (rôle joué par [Audric HARRIS])
- Invitation du collaborateur via *Settings > Manage Access*
- Clone du dépôt dans l'arborescence :
  ```bash
  cd courseGIT
  git clone [url_du_depot] tp3
  ```

#### 2. repatition des taches

Rôle Athos (moi) :
- Implémentation de CryptoMarche.java

Rôle Porthos (Pierre Coignard) :
- Implémentation de Portefeuille.java

#### 3. notion abordé
Branchement :

```bash
git checkout -b test
git branch
```
Synchronisation :

```bash
git merge test
git push
git pull
```

#### 4. Commandes Git utilisées

# Gestion des branches
```bash
git branch -a
git merge [branche]
git checkout -b [Nom de la branche]
```

