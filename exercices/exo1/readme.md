# Exercice 1

Suite à un oubli de la part du créateur de l'exercice plusieurs éléments n'ont pas été ajoutés dans la page.

Il en revient à vous pour corriger les erreurs qui y sont glissés

**Note :** Le fichier `index.html` est en lecture seule et n'est affiché qu'à titre indicatif. Vous ne pouvez agir sur ce fichier qu'en javascript.


> 1. Selectionnez le premier fils de l'élèment `body` et modifiez son contenu en `Rick Astley - Never Gonna Give You Up`.
> 2. Sélectionnez tous les éléments possèdant la classe `couplet` et supprimer la première ligne qui est en double.  
>    *N'oubliez pas de supprimer le `<br />` qui cause le retour à la ligne*
> 3. Le refrain s'est dupliqué à cause de l'écho. Supprimez les occurences en double.  
>    *N'oubliez pas de supprimer le `<br />` qui cause le retour à la ligne*
> 4. Maintenant que toutes les erreurs ont été corrigées, supprimer l'élément ayant pour id `erreur`

*Conseils :*

 - Utilisez `firstElementChild`[<sup>ref</sup>](https://developer.mozilla.org/fr/docs/Web/API/ParentNode/firstElementChild) pour sélectionner le premier `Element` d'un Node.
 - Utilisez `document.getElementById("un_id")`[<sup>ref</sup>](https://developer.mozilla.org/fr/docs/Web/API/Document/getElementById) pour récuperer un élément ayant pour id `un_id`. 
 - Pour sélectionner tous les éléments qui possèdent une classe, utilisez `document.getElementsByClassName("nom_classe")`[<sup>ref</sup>](https://developer.mozilla.org/fr/docs/Web/API/Element/getElementsByClassName) ou `document.querySelectorAll(".nom_classe")`[<sup>ref</sup>](https://developer.mozilla.org/fr/docs/Web/API/Document/querySelectorAll)  
   **Attention, ces fonctions retournent un tableau.**
 - Utilisez `parent.removeChild(enfant)`[<sup>ref</sup>](https://developer.mozilla.org/fr/docs/Web/API/Node/removeChild) afin de supprimer un élément `enfant` d'un élément `parent`.
 - Faites attention lorsque vous modifiez les elements d'une liste lors de son parcours.

@[Exercice 1]({ "layout": "aside", "stubs": ["exo1/src/index.js", "exo1/read-only/index.html"], "command": "echo \"TECHIO> open -s /project/target/exo1/src/ index.html\"" })
