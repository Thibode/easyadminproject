# EasyAdminProject

Galerie de peinture

## Environnement de développement

### Pré-requis

* PHP 7.4
* Composer
* Symfony CLI 
* Docker
* Docker-compose

Vous pouvez verifier les pré-requis (sauf Docker et Docker-compose) avec la commande suivante (de la CLI Symfony) :

```bash
symfony check:requirements
```
### Lancer l'environnement de développement

```bash
docker-compose up -d
symfony serve -d
```