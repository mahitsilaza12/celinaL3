# celinaL3
vuejs symfony
celina minister Orchestrator
==========================

Symfony run 
------------------------

***Backend configuration
```bash
composer install
```
***Commande create bdd 
Create a local .env.local file from .env file
```bash
$ cp .env .env.local 
```
***Commande create bdd 
Create a local .env.local file from .env file
```bash
$ php bin/console doctrine:database:create 
```
***Commande mise a jour bdd 
```bash
$ php bin/console d:s:u --force
```
***Commande ajout admin a bdd 
```bash
$ php bin/console admin:create 
```


***frontend install package
```bash
npm install
```

***frontend run 
```bash
npm run dev
```