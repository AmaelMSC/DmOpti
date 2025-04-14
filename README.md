# Travaux Pratiques pour le cours d'Optimisation

Cetta page regroupe tous les documents nécéssaires pour réaliser les TPs du [cours d'Optimisation](https://moodle.u-paris.fr/course/view.php?id=2434) (Université de Paris - L3 MFA/MI/IngeM). 

## Instructions pour lancer un TP

Pour lancer le TP, ouvrez le lien du TP correspondant dans un nouvel onglet :

- [TP 1](https://mybinder.org/v2/git/https%3A%2F%2Fgitlab.math.univ-paris-diderot.fr%2Fgarrigos%2Fl3optim-tp/HEAD?filepath=TP1_2021.ipynb) (et sa [correction](https://mybinder.org/v2/git/https%3A%2F%2Fgitlab.math.univ-paris-diderot.fr%2Fgarrigos%2Fl3optim-tp/HEAD?filepath=TP1_2021-correction.ipynb))
- [TP 2](https://mybinder.org/v2/git/https%3A%2F%2Fgitlab.math.univ-paris-diderot.fr%2Fgarrigos%2Fl3optim-tp/HEAD?filepath=TP2_2021.ipynb) (et sa [correction](https://mybinder.org/v2/git/https%3A%2F%2Fgitlab.math.univ-paris-diderot.fr%2Fgarrigos%2Fl3optim-tp/HEAD?filepath=TP2_2021-correction.ipynb))
- [TP 3](https://mybinder.org/v2/git/https%3A%2F%2Fgitlab.math.univ-paris-diderot.fr%2Fgarrigos%2Fl3optim-tp/HEAD?filepath=TP3_2021.ipynb) (et sa [correction](https://mybinder.org/v2/git/https%3A%2F%2Fgitlab.math.univ-paris-diderot.fr%2Fgarrigos%2Fl3optim-tp/HEAD?filepath=TP3_2021-correction.ipynb))
- [TP 4](https://mybinder.org/v2/git/https%3A%2F%2Fgitlab.math.univ-paris-diderot.fr%2Fgarrigos%2Fl3optim-tp/HEAD?filepath=TP4_2021.ipynb) (et sa [correction](https://mybinder.org/v2/git/https%3A%2F%2Fgitlab.math.univ-paris-diderot.fr%2Fgarrigos%2Fl3optim-tp/HEAD?filepath=TP4_2021-correction.ipynb))

Cela va lancer une instance de myBinder, qui vous permettra de coder en ligne, sans ne rien avoir à installer sur votre PC. 

:warning: Le temps que le serveur se lance peut prendre du **temps** (jusqu'à 1-2 minutes). Soyez donc patients.

|  |
| ---  |
|<img src="images/binder_load.png" width=400px>  |
| La page de chargement du TP. Peut prendre 1-2 minutes. |

Si au bout de deux minutes vous voyez que cela mouline toujours:
- Cliquez sur le lien `show` en bas à droite. Si vous voyez que des lignes défilent, c'est que le serveur n'est pas encore prêt (cela prend plus de temps si vous le lancez en dehors des horaires usuels de TP par exemple).
- Si le terminal reste coincé sur `Lauching server ....` pendant 1 min, il vaut mieux que vous rafraichissiez la page.

Une fois le chargement terminé vous accèderez au TP, dans une interface de type Jupyter:

|  |
| ---  |
|<img src="images/binder_TP.png" width=400px>  |
| L'interface Jupyter contenant le TP. |


## Informations importantes:

* Si vous restez inactifs pendant plus de 10 minutes, le serveur s'arrêtera. Cela veut dire que vous perdrez vos données et devrez tout recommencer de zéro  :pensive:

|  |
| ---  |
|<img src="images/binder_failure.png" width=400px>  |

Pour éviter cela je vous ai mis une ligne de code en début de TP, afin de garder la session ouverte le temps du cours.

* Tout ce que vous ferez ne sera **pas** sauvegardé en ligne. Une fois votre TP terminé, si vous souhaitez sauvegarder votre travail, il vous faudra télécharger votre notebook en cliquant en dans la barre du haut sur le bouton `Download`. (Pour des raisons qui m'échappent encore, le fichier téléchargé peut avoir 2 extensions différentes : `.json` ou `.ipynb`. Si vous avez un `.json` il faut remplacer l'extension par `.ipynb`)

|  |
| ---  |
|<img src="images/binder_download.png" width=100px>  |

* Si vous souhaitez revenir travailler ultérieurement sur votre notebook téléchargé, vous avez plusieurs options:
  - Vous disposez déjà de Jupyter/Jupyter Lab sur votre ordinateur : dans ce cas il vous suffit de lancer votre `TPX.ipynb`
  - Vous n'avez pas Python installé sur votre ordinateur et vous ne souhaitez/pouvez pas l'installer (et vous avez bien raison) : vous pouvez le lancer en ligne en utilisant le service [Google Collab](https://colab.research.google.com). Il vous suffit de vous connecter à votre compte Google, puis d'importer votre code avec l'onglet `Importer`.
  - Vous souhaitez installer python et jupyter sur votre ordinateur : pour cela je vous conseille plus que vivement d'installer la distribution Anaconda:
    * Suivez ce lien : [https://www.anaconda.com/products/individual](https://www.anaconda.com/products/individual)
    * Cliquez sur `Download`
    * Choisissez l'installeur de votre choix, en fonction de votre OS (Windows/Mac/Linux).
    * Note : le téléchargement et l'installation peuvent prendre beaucoup de temps, ce n'est pas quelque chose à faire 10min avant le TP..
    * Une fois installé, lancez jupyter ou jupyter lab et ouvrez votre `TPX.ipynb`


