# Break The Task

**Break The Task** est un projet regroupant une collection complète de scripts d'automatisation visant à simplifier la gestion des infrastructures, la sécurité, et les opérations réseau. Ces scripts sont conçus pour être pratiques, efficaces, et facilement adaptables aux environnements complexes.

## Objectifs du Projet
L'objectif principal de ce projet est de fournir une bibliothèque de scripts bien organisée pour automatiser les tâches d'administration des systèmes et des réseaux. Cela inclut, sans s'y limiter, la gestion des conteneurs, la configuration réseau, la sécurité des systèmes, l'automatisation des bases de données, et bien plus encore. En utilisant ce projet, vous serez en mesure de :
- Automatiser des tâches répétitives.
- Réduire les erreurs humaines.
- Améliorer l'efficacité de la gestion des systèmes et infrastructures.
- Faciliter le déploiement, la maintenance, et la surveillance des services critiques.

Ce projet est porté par **Break The World**, une initiative visant à promouvoir des outils d'automatisation accessibles et performants pour les petites et moyennes infrastructures.

## Structure du Répertoire
- **Docker/**: Scripts pour la gestion des conteneurs et des stacks Docker. Voir [Docker/README.md](Docker/README.md) pour plus de détails.
- **Proxmox/**: Automatisation des sauvegardes, des machines virtuelles et d'autres tâches liées à Proxmox. Voir [Proxmox/README.md](Proxmox/README.md).
- **HyperV/**: Scripts pour la gestion des machines virtuelles Hyper-V. Voir [HyperV/README.md](HyperV/README.md).
- **Linux/**: Scripts généraux pour Linux, catégorisés en mises à jour, monitoring et sécurité. Voir [Linux/README.md](Linux/README.md).
  - **updates/**: Scripts pour automatiser les mises à jour du système et la maintenance du kernel.
  - **monitoring/**: Outils pour vérifier l'état de santé des systèmes et les services de monitoring.
  - **security/**: Configuration de durcissement et de sécurité.
- **Networking/**: Scripts pour la gestion des réseaux, la configuration VLAN, DNS et VPN. Voir [Networking/README.md](Networking/README.md).
- **Cloudflare/**: Automatisation des tâches Cloudflare telles que la mise à jour DNS et la création de tunnels. Voir [Cloudflare/README.md](Cloudflare/README.md).
- **Traefik/**: Scripts pour configurer et gérer les services Traefik. Voir [Traefik/README.md](Traefik/README.md).
- **MariaDB/**: Scripts de gestion de base de données, incluant les sauvegardes et les optimisations. Voir [MariaDB/README.md](MariaDB/README.md).
- **Nginx/**: Déploiement et maintenance des configurations Nginx. Voir [Nginx/README.md](Nginx/README.md).
- **PHP/**: Scripts liés à la gestion et au déploiement des services PHP. Voir [PHP/README.md](PHP/README.md).
- **Utils/**: Utilitaires et fonctions communes partagées entre divers scripts d'automatisation. Voir [Utils/README.md](Utils/README.md).
- **Mikrotik/**: Scripts pour installer et gérer Mikrotik CHR sur un VPS Debian. Voir [Mikrotik/README.md](Mikrotik/README.md).

## Utilisation
1. **Cloner le Dépôt** : Commencez par cloner ce dépôt sur votre serveur ou votre machine locale :

    ```bash
    git clone https://github.com/votre-repo/break-the-task.git
    cd break-the-task
    ```

2. **Explorer les Scripts** : Parcourez les différents dossiers pour identifier les scripts correspondant à vos besoins spécifiques.

3. **Lire les README.md** : Chaque dossier possède un fichier `README.md` qui explique les fonctionnalités principales des scripts, leurs prérequis, et la manière de les utiliser. Prenez soin de lire ces fichiers avant de lancer un script.

4. **Exécution** : Suivez les instructions détaillées dans chaque fichier `README.md` pour lancer les scripts avec les paramètres appropriés.

## License / Licence
Ce projet est sous la **licence [MIT](https://opensource.org/licenses/MIT)**.

### Règles de modification et redistribution :
- **Modification obligatoire** : Si vous modifiez ce code, vous devez redistribuer votre version modifiée sous la même licence MIT et inclure un avis précisant que le code a été modifié. Cela garantit la transparence et l'amélioration continue du projet par la communauté.
- **Redistribution** : Vous pouvez redistribuer ce code, sous forme modifiée ou non, dans n'importe quel but, tant que vous respectez les termes de cette licence.

## Contribuer
Contributions bienvenues ! Voici la procédure pour contribuer :
1. **Forker le Dépôt** : Créez une copie de ce dépôt dans votre compte GitHub.
2. **Faire des Modifications** : Apportez les modifications que vous jugez nécessaires. N'oubliez pas de tester minutieusement votre code dans divers scénarios.
3. **Mettre à Jour les README.md** : Si vous ajoutez ou modifiez des scripts, veillez à mettre à jour les fichiers `README.md` des catégories correspondantes. Cela inclut la description des nouveaux scripts, leurs fonctionnalités, leurs prérequis, et les instructions d'utilisation.
4. **Pull Request (PR)** : Une fois vos changements effectués, soumettez une **pull request**. Expliquez clairement les modifications que vous avez apportées et pourquoi elles sont bénéfiques pour le projet.
5. **Validation** : Les pull requests seront examinées par les mainteneurs du projet, et une discussion pourra être engagée si des ajustements sont nécessaires. Une fois validée, votre contribution sera intégrée au dépôt principal.

L'objectif est de maintenir un projet facile d'accès et utile pour tous les utilisateurs, donc nous comptons sur votre collaboration pour respecter ces procédures.

## Avertissements
- Ces scripts sont destinés à être utilisés sur des serveurs **Linux** (principalement Debian 12). Utilisez-les avec précaution sur d'autres distributions ou versions.
- L'exécution des scripts peut modifier les configurations de votre système ou écraser des données. **Assurez-vous de sauvegarder vos données** importantes avant de poursuivre.

## Contact
Pour toute question ou suggestion, n'hésitez pas à ouvrir un **issue** sur GitHub.
