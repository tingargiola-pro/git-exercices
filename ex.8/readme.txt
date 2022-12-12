Vous avez travaillé de longues heures sur une fonctionnalité.
Vous avez commité régulièrement pour pouvoir revenir facilement en arrière en cas de besoin.

Il est temps de merger tout ça dans master mais vous ne voulez pas que
tous vos commit préfixés WIP (Work In Progress) apparaissent sur le dépôt.

Vous voulez squashez tous vos commit en un seul.

- Utilisez `git rebase -i` pour squasher tous vos commit WIP en un seul
  tout en laissant les autres en place
- Utilisez `git push` pour envoyer vos commit dans master


----------

* English Version *


You have worked for many hours on a feature and have regularly
commited localy your work so you can always go back to previous states.

Now it is time to merge this great feature of yours into master.

As you are a good citizen, you don't want every commit named "WIP"
(Work In Progress) to be pushed to origin, so you're going to squash
all your commits into one.

- Use `git rebase -i` to squash all "WIP" commits into one
  but leave the previous commits as they are semantic.
  Don't forget to put a comprehensible commit message.
- Use `git push` to merge into master.
