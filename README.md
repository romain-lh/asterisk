# asterisk

Une fois ansible configurer nous allons effetuer un clone, pour ce faire nous allons utiliser la commande suivante : 

``` git clone https://github.com/romain-lh/asterisk``` 

une fois le git clone effetuer il suffit de lancer asterisk-compose.yml avec la commande : 

```ansible-playbook -i hosts asterisk-compose.yml```

une fois l'installation d'asterisk effetuer nous allons nous rendre dans la machine client pour lancer asterisk avec la commande : 

``` asterisk -vvvvc```
