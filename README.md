<h1 align="center">Documentations 👋</h1>

> Documentations de l'ensemble des modules

## Ajouter un depot de documentations adoc

Dans le fichier antora-playbook.yml, ajouter une source :

```json lines
  sources:
  - url: https://github.com/ENIecole/******
    start_path: documentations
```

## Intégration continue

Le fichier d'action GitHub publish.yml publie la documentation générée vers une page statique

## Génération de la documentation

```sh
npm run gen
```

## Auteur

👤 **Caliendo Julien**

* Github: [@caliendojulien](https://github.com/caliendojulien)
* LinkedIn: [@caliendojulien](https://linkedin.com/in/caliendojulien)

## 🤝 Contributions

Les contributions et commentaires sont les bienvenus !<br /> [ici](https://github.com/ENIecole/documentations/issues).

## Support

⭐️ Si le projet le mérite !