Les contributions externes sont les bienvenues !

# Avant de commencer...

1. Vérifiez que vous avez [un compte Github](https://github.com/signup/free).
2. _Forkez_ le dépôt.
3. Vérifiez que vous avez la dernière version du repository.
4. **Attribuez-vous** votre _ticket_ (si vous fixez un ticket). C'est important pour éviter de se marcher dessus. Si vous n'êtes pas dans l'organisation et donc que vous ne pouvez pas vous attribuer directement le _ticket_, ajoutez simplement un commentaire clair dans celui-ci (tel que _"Je prends"_).

# Contribuer aux ressources de **Bidouilleurs et Bidouilleuses**

1. Créez une branche pour contenir votre travail.
2. Faites vos modifications.
3. Poussez votre travail et faites une _pull request_.

# Quelques bonnes pratiques

* Le _workflow_ Git utilisé est le suivant :
    * Les PR sont unitaires. Aucune PR qui corrige plusieurs problèmes ou apporte plusieurs informations ne sera acceptée ; la règle est : une information ou une correction = une PR.
    * Les PR sont mergées dans la branche `master`, après une relecture légère.
    * Pensez à préfixer vos branches selon l'objet de votre PR : `typo-XXX`, `site-XXX`, `cnc-XXX`, etc.

* Faites des messages de _commit_ clairs et en français.

# Les bonnes pratiques pour les PR et les commits
## Les pull requests

* Lors de l'ouverture d'une PR, veuillez décrire ce que vous ajoutez / fixez.

## Les messages de commit

* Pour les commits, nous suivons le même ordre d'idée des standards Git, à savoir :
    * La première ligne du commit ne doit pas faire plus de 50 caractères.
    * Si besoin, complétez votre commit via des commentaires, en respectant une limite de 70 caractères par ligne.
    * Le commit doit être de préférence en français.
    * Vous pouvez également (c'est d'ailleurs conseillé) de référencer l'_issue_ que vous fixez si vous en fixez une. Par exemple : `Fixe #789`
    * Un commit doit être atomique ; il fixe / ajoute **une** chose et le fait **bien**.

* Essayez d'éviter les commits dits inutiles (`fix previous commit`, ...). Si vous en avez dans votre pull-request,
  un _squash_ sera effectué lors du _merge_.

N'hésitez pas à demander de l'aide, et bon courage !
