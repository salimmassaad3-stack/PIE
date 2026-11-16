PIE — Installation du projet

1. Prérequis

Avant de commencer, assurez-vous d'avoir installé :

Git : https://git-scm.com/downloads

uv : https://docs.astral.sh/uv/getting-started/installation/

Pour vérifier que les installations fonctionnent, ouvrez PowerShell et exécutez :

git --version
uv --version

2. Récupérer le projet et installer l'environnement

Ouvrez PowerShell dans le dossier où vous souhaitez installer le projet PIE.

Copiez-collez ensuite les commandes suivantes :

git clone https://github.com/REMPLACER_PAR_VOTRE_URL/PIE.git
cd PIE
uv sync --locked
