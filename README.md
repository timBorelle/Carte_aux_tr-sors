# Carte aux trésors

# Exemple input file
```
# {C comme Carte} - {Nb. de case en largeur} - {Nb. de case en hauteur}
C - 3 - 4
# {M comme Montagne} - {Axe horizontal} - {Axe vertical}
M - 1 - 0
M - 2 - 1
# {T comme Trésor} - {Axe horizontal} - {Axe vertical} - {Nb. de trésors}
T - 0 - 3 - 2
T - 1 - 3 - 3
# {A comme Aventurier} - {Nom de l’aventurier} - {Axe horizontal} - {Axe vertical} - {Orientation} - {Séquence de mouvement}
A - Lara - 1 - 1 - S - AADADAGGA
```

# Exemple output file file (after simulation)
```
C - 3 - 4
M - 1 - 0
M - 2 - 1
# {T comme Trésor} - {Axe horizontal} - {Axe vertical} - {Nb. de trésors restants}
T - 1 - 3 - 2
# {A comme Aventurier} - {Nom de l’aventurier} - {Axe horizontal} - {Axe vertical} - {Orientation} - {Nb. trésors ramassés} 
A - Lara - 0 - 3 - S - 3
```
