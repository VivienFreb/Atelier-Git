# Projet fictif : Projet de page de connexion Web
## Introduction
Ce projet est un modèle de page de connexion Web que vous pouvez utiliser comme base pour votre propre projet. Il contient une page de connexion simple avec un formulaire de connexion, quelques fonctionnalités basiques d'une page de connexion ainsi que deux exemples de boutons de connexion via des services externes.

## Objectifs
L'objectif de cet atelier est de fournir un projet fictif sur lequel vous pourrez travailler les notions de GitHub en collaboration, telles que les branches, les merge et les conflits. <br>
Vous serez invités à ajouter de nouvelles fonctionnalités à la plateforme dans des branches distinctes, à les fusionner avec la branche principale et à gérer les conflits qui pourraient survenir.

## Instructions
Voici les instructions pour utiliser ce projet dans votre propre dépôt Git :

<ol>
<li>Cloner ce dépôt sur votre ordinateur :</li>

```git
git clone https://github.com/VivienFreb/Atelier-Git.git
```

<li>Créer un nouveau dépôt sur Gitea ou un autre service Git en ligne.</li>
<li>Pousser le code de ce dépôt dans votre nouveau dépôt :</li>

```git
cd GithubCollab
git remote set-url origin https://adresse-de-votre-nouveau-depot.git
git push -u origin master
```

<li>Demandez à chaque membre de votre groupe de récupérer le dépôt et de créer une nouvelle branche pour ajouter une des fonctionnalités de la liste fournie ci-dessous.</li>

<li>Une fois que chaque membre a terminé, chacun devra trouver une solution pour fusionner leur branche avec leur nouvelle fonctionnalité à la branche principale du projet.

<li>Si des conflits surviennent, les membres peuvent travailler ensemble pour les résoudre et fusionner leurs modifications.</li>

</ol>

## Fonctionnalités à ajouter

Voici la liste des fonctionnalités que vous pouvez ajouter à la page de connexion pour votre projet de collaboration en groupe :

<i>NB: Les fonctionnalités sont plus ou moins identiques pour une bonne raison, l'idée est que vous travaillez sur le même fichier, sur la même partie pour justement avoir des conflits à régler.</i>

<details>
<summary>Ajouter une option pour se connecter avec LinkedIn :</summary>
<ul>
<li>Ajouter une nouvelle balise &lt;a&gt; pour le bouton de connexion</li>
<li>Ajouter une classe pour le bouton (par exemple "linkedin-btn") pour pouvoir le styliser dans le CSS</li>
<li>Ajouter un nouvel événement onclick pour le bouton, qui redirige vers la page de connexion de LinkedIn</li>
<li>Vérifier que la page est fonctionnelle et que le bouton redirige bien vers la page de connexion LinkedIn</li>
</ul>
</details>

<details>
<summary>Ajouter une option pour se connecter avec Facebook :</summary>
<ul>
<li>Ajouter une nouvelle balise &lt;a&gt; pour le bouton de connexion</li>
<li>Ajouter une classe pour le bouton (par exemple "facebook-btn") pour pouvoir le styliser dans le CSS</li>
<li>Ajouter un nouvel événement onclick pour le bouton, qui redirige vers la page de connexion de Facebook</li>
<li>Vérifier que la page est fonctionnelle et que le bouton redirige bien vers la page de connexion Facebook</li>
</ul>
</details>

<details>
<summary>Ajouter une option pour se connecter avec un compte GitHub :</summary>
<ul>
<li>Ajouter une nouvelle balise &lt;a&gt; pour le bouton de connexion</li>
<li>Ajouter une classe pour le bouton (par exemple "github-btn") pour pouvoir le styliser dans le CSS</li>
<li>Ajouter un nouvel événement onclick pour le bouton, qui redirige vers la page de connexion de GitHub</li>
<li>Vérifier que la page est fonctionnelle et que le bouton redirige bien vers la page de connexion GitHub</li>
</ul>
</details>

<details>
<summary>Ajouter une option pour afficher le mot de passe :</summary>
<ul>
<li>Ajouter une nouvelle balise &lt;span&gt; pour le bouton de l'icône de l'oeil</li>
<li>Ajouter une classe pour le bouton (par exemple "toggle-password-btn") pour pouvoir le styliser dans le CSS</li>
<li>Ajouter un nouvel événement onclick pour le bouton, qui modifie le type d'input du mot de passe de "password" à "text"</li>
<li>Vérifier que le bouton fonctionne correctement en montrant et cachant le mot de passe</li>
</ul>
</details>

## Notions
Cela vous permettra de voir et d'apprendre les concepts suivants :

* [Création de branches.](https://git-scm.com/docs/git-branch)
* [Fusion de branches.](https://git-scm.com/docs/git-merge) 
* [Résolution de conflits.](https://git-scm.com/docs/git-merge#_how_to_resolve_conflicts)