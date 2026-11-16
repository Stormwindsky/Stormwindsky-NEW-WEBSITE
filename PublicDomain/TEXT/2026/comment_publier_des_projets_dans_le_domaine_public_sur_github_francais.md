# Comment je publie correctement mes projets open-source dans le « Domaine Public » sur GitHub

Si vous vous demandez comment je structure mes projets depuis fin 2026 jusqu'à probablement début 2027, eh bien, cette documentation est faite pour vous.

> **NOTE DE LICENCE :** Cette « documentation » est très courte et est placée dans le Domaine Public sous la licence **CC0 1.0**.

Elle est conçue avant tout comme une liste de choses à retenir — des points que j'aurais aimé connaître à mes débuts.

---

### ⚠️ AVERTISSEMENTS IMPORTANTS

* **Ceci n'est pas un avis juridique :** Je ne suis ni un avocat, ni un expert absolu en droit. Je peux donc faire des erreurs. Prenez ces informations avec recul et faites vos propres recherches si nécessaire.
* **Méthode personnelle et irréversibilité :** Ce guide présente simplement *ma* façon de faire pour créer des projets GitHub « Domaine Public » compatibles à l'international. Voyez cela comme un conseil si vous souhaitez réellement libérer vos créations. **Réfléchissez bien avant d'appliquer ces licences :** une fois qu'un projet est placé dans le Domaine Public (ou sous des licences équivalentes), **il n'y a aucun retour en arrière possible**. C'est définitif et à vie !

---

### 💡 Mes recommandations principales

Si vous souhaitez partager du code source dans le « Domaine Public » à l'échelle internationale, **N'UTILISEZ JAMAIS la licence CC0 1.0 ni la licence nommée The Unlicense pour votre code.**

Certes, tout le monde le fait (surtout avec la CC0 1.0), mais il faut **réserver les licences Creative Commons uniquement aux ressources (assets)** — comme les images, les sons ou les textes — et **non au code source**, afin d'éviter tout flou juridique.

La licence **The Unlicense** est *presque* parfaite, mais elle pose un problème majeur : elle est incompatible avec les lois de nombreux pays en Europe. Dans plusieurs juridictions, il est légalement impossible de renoncer à ses droits moraux de son vivant. La CC0 1.0 intègre une clause de repli pour contourner ce problème légalement, mais *The Unlicense* ne possède pas cette sécurité pour le code source.

#### Alors, quelles licences choisir pour le code ?
Bien qu'il ne s'agisse pas techniquement de « Domaine Public » au sens strict, elles agissent exactement de la même manière dans la pratique. Je vous recommande les licences **MIT-0** (*MIT No Attribution*) et **BSD-0** (*BSD Zero Clause*).

Désormais, pour tous les projets que je veux rendre 100 % « Domaine Public », j'utilise cette combinaison :
* **Code source / Scripts :** Double licence **MIT-0** et **BSD-0**.
* **Ressources (Assets) :** Licence **CC0 1.0**.

De cette façon, vous avez la certitude d'offrir vos projets GitHub sans aucune restriction et sans piège juridique à travers le monde.

---

### 🔗 Dépôts utiles et exemples concrets

Pour vous faciliter la tâche, voici deux dépôts GitHub que j'ai créés :

1. **Modèle de triple licence prêt à l'emploi :**
   Pour réunir les trois licences en un seul fichier — précisant clairement que les **assets sont sous CC0 1.0** et que les **scripts/le code sont sous MIT-0 & BSD-0** — je vous recommande de télécharger le fichier `LICENSE` de ce dépôt. N'oubliez pas d'y **ajouter votre pseudonyme / nom ainsi que l'année** !
   👉 [Triple-Licenses-Public-Domain sur GitHub](https://github.com/Stormwindsky/Triple-Licenses-Public-Domain)

2. **Exemple concret (Projet Scratch) :**
   Voici un projet Scratch que j'ai créé et placé dans le « Domaine Public » en appliquant exactement cette méthode (**MIT-0 & BSD-0** pour le code source du projet et **CC0 1.0** pour les assets) :
   👉 [Lava-Legacy-Retake sur GitHub](https://github.com/Stormwindsky/Lava-Legacy-Retake)