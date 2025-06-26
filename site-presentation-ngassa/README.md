Développement d’un site statique en une page pour une entreprise d’école, intégrant :

une structure HTML bien organisée,

un thème CSS responsive,

un menu hamburger en JavaScript,

des effets de scroll animés.

Nous avons utilisé une stratégie de développement par branches inspirée de Git Flow pour séparer les responsabilités
main (stable)
│
├── feature/html-structure    → structure HTML de la page
├── feature/css-theme         → thème CSS du site
├── test/frontend             → intégration HTML + CSS + JS + tests visuels
 |-- dev test avant publication
| Étape                       | Commande                         |
| --------------------------- | -------------------------------- |
| Création de branche         | `git branch nom de la branch` |
| Ajout des fichiers          | `git add .`                      |
| Commit des changements      | `git commit -m "Message"`        |
| Fusion de branches          | `git merge nom-de-branche`       |
| Revenir à une branche       | `git switch nom_de_la_branche    |
| Pousser la branche (GitHub) | `git push origin nom-de-branche` |

