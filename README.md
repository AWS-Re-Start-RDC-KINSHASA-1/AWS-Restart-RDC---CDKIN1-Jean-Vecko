# AWS-Restart-RDC---CDKIN1-Jean-Vecko
# Déploiement Automatique sur Elastic Beanstalk

Ce projet consiste en un script Python qui automatise le déploiement d'une application sur Elastic Beanstalk dès qu'une nouvelle version du code est disponible. Il utilise le SDK Boto3 pour interagir avec les services AWS.

## Configuration

Avant d'utiliser ce script, assurez-vous de configurer correctement les paramètres suivants :

- **Nom de l'application Elastic Beanstalk :** Remplacez `<nom_de_votre_application>` dans le script par le nom de votre application Elastic Beanstalk.
- **Nom de l'environnement Elastic Beanstalk :** Remplacez `<nom_de_votre_environnement>` dans le script par le nom de l'environnement Elastic Beanstalk que vous souhaitez mettre à jour.
- **Chemin vers l'application :** Assurez-vous que le chemin vers votre application est correctement défini dans le script.

## Utilisation

Pour utiliser ce script, exécutez simplement le fichier `deploy.py` à chaque fois que vous souhaitez déployer une nouvelle version de votre application sur Elastic Beanstalk. Assurez-vous que les informations d'identification AWS sont correctement configurées sur la machine où le script sera exécuté.

```bash
python deploy.py
