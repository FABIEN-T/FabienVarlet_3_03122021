# Projet 3 ohmyfood!
[Lien GitHub pages](https://fabien-t.github.io/Fabien_P3/public/)
***
## Contexte
Ohmyfood! est une entreprise de commande de repas en ligne. Notre concept permet aux
utilisateurs de composer leur propre menu et réduire leur temps d’attente dans les
restaurants car leur menu est préparé à l’avance. Plus de perte de temps à consulter la carte
!

## Objectif
Développer un site proposant le menu de 4 grands restaurants parisiens.

## Technologies
* Le développement devra se faire en CSS, sans JavaScript.
* Aucun framework ne devra être utilisé, en revanche l’utilisation de SASS serait un
plus.
* Aucun code CSS ne devra être appliqué via un attribut style dans une balise HTML.
* Tout le code doit être versionné sur GitHub et le site devra être accessible sur
Github Pages une fois terminé.

```
<!-- voici un exemple html -->
<div class="functioning__button">
    <div class="functioning__round">1</div>
        <i class="fas fa-mobile-alt functioning__icon functioning__icon--color"></i>
        <p class="functionning__paragraph">Choisissez un restaurant</p>                
    </div>

<!-- voici un exemple scss -->
.banner {
    background-color: $grey-place-bkgd;
    box-shadow: inset 0px 3px 3px $grey-place-shdw;
    // box-sizing: border-box;
    &__place {
        display: flex;
        justify-content: flex-start;
        align-items: center;
        width: 177px;
        margin: 0px auto;
        padding: 18px 0px;
    }
    &__icon {
        margin-bottom: 4px;
        margin-right: 13px;
        color: $footer;
    }
    &__city {
        // box-sizing: border-box;
        font-weight: 500;
    }
}
```     