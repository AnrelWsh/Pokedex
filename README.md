# OptiSkuu : Pokédex

En groupe nous avons réalisé un poké dex à l'aide de l'api PokéApi. Nous avons utilisé prinicipalement du JS pour l'affichage ainsi que CSS et Tailwind pour la partie style.

## Fonctionnalités :

* Pokedex 
    * Afficher tout les pokemons de la **1ere generation** à la **8eme.**
    * Trier le pokédex par **type**
    * Rechercher un pokemon, indépendament de la génération définie
    * Affichage de la forme **shiny** lors du **hover** de ce dernier
    * **Drag & Drop** des pokemons du pokedex vers son équipe
    * Au **click sur le pokemon**, affiche la page de ce dernier
    * Choisir un pokemon aléatoire parmis les 900 existant

#

* Equipes :
    * Affichage de son/ses équipe(s) dénifie(s) préalablement
    * Affichage des **avantages/faiblesses de types** de l'équipe
    * Affichage de la **moyenne de stats** de l'équipe

#

* Pokemon :
    * Affiche le pokemon selectionné, et on hover, sa forme shiny
    * Affiche le/les types du pokemon selectionné, ainsi que son poids et sa taille
    * Donne les informations de combat du pokemon :
        * Type(s) :
            * Ses faiblesses de type (x2 en défense et x0.5 en attaque)
            * Ses avantages de type (x2 en attaque et x0.5 en défense)
            * Le/les type(s) au(x)quel(s) il ne fait pas de dégats, ou bien au(x)quel(s) il ne prend pas de degats
        * Ses stats :
            * Hp
            * Defense
            * Def Spe
            * Atk
            * Atk Spe
            * Vitesse
        * Les attaques qu'il peut apprendre :
            * Avec leurs nom et leurs type
            * Leurs précision
            * Leurs type de dégats (spe ou physique)
            * Leurs dégats
            * Leurs PP

