# Exercice Bootstrap 4 - Layout responsive avancé

Intégrez les 4 maquettes en utilisant la grille Bootstrap. Faites en sorte que les colonnes s'adaptent à toutes les tailles d'écran représentées par les artboards.

Les éléments nécessaires à l'intégration se trouvent dans le dossier **\_consigne**.

Afin de rendre les colonnes visibles, vous pouvez utiliser la CSS suivante:

```CSS
.row + .row {
  margin-top: 16px;
}

.row > .col,
.row > [class^=col-] {
  padding-top: 12px;
  padding-bottom: 12px;
  background-color: rgba(86, 61, 124, .15);
  border: 1px solid rgba(86, 61, 124, .2);
}
```

![](_consigne/maquette1@1x.png)
![](_consigne/maquette2@1x.png)
![](_consigne/maquette3@1x.png)
![](_consigne/maquette4@1x.png)
