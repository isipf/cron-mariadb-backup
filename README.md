# Mariadb Cron Backup

## Description
Projet de containeur docker avec un client mariadb pouvant acceuillir des script dans les dossiers cron prédéfini pour faire un dump de la base de donnée


## Installation
1. Télécharger le projet
```
cd existing_repo
git remote add origin https://gitlab.com/stegens-labs/docker/mariadb-cron-backup.git
git branch -M main
git push -uf origin main
```

## Usage
1. Ouvrir le terminal à la racine du projet
2. Executer `docker-compose up`

Il est possible d'ajouter des jobs via les dossiers dans les répetoires etc/periodic

## Contributing
State if you are open to contributions and what your requirements are for accepting them.

For people who want to make changes to your project, it's helpful to have some documentation on how to get started. Perhaps there is a script that they should run or some environment variables that they need to set. Make these steps explicit. These instructions could also be useful to your future self.

You can also document commands to lint the code or run tests. These steps help to ensure high code quality and reduce the likelihood that the changes inadvertently break something. Having instructions for running tests is especially helpful if it requires external setup, such as starting a Selenium server for testing in a browser.

## Authors and acknowledgment
David Chungue et Thomas Stegen

https://mariadb.com/kb/en/mariadb-dump/
https://devopscell.com/cron/docker/alpine/linux/2017/10/30/run-cron-docker-alpine.html
