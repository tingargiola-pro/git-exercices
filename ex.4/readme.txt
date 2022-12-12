PARTIE 1:
Vous avez beaucoup travaillez et êtes satisfait du résultat.
Seulement voilà, il y a un bug...

Il est tard et il vous tarde de rentrez chez vous.
Peut être que la nuit vous portera conseil.

Vous ne souhaitez cependant pas laisser votre travail non sauvegardé mais votre code n'étant pas stable
vous ne pouvez pas non plus le pusher sur master.

Vous décidez de créer une branche:
- Créez et naviguer sur une nouvelle branche appelée "file-second"
- Commitez votre travail
- Pusher (n'oubliez pas de créer l'upstream)

PARTIE 2

Vous avez bien dormi et avez l'esprit clair. Voua allez pouvoir régler ce bug.
En allant à votre bureau votre chef vous appelle, Un bug urgent en production doit être corrigé au plus vite.

- Naviguez sur master
- Récupérez la dernière version
- Ajoutez une ligne au fichier first.txt contenant le mot "three"
- Commitez et pushez vos modifications

PARTIE 3

Il est maintenant temps de s'occuper de ce bug.

- Récupérez la branche file-second

PARTIE 4

Bien évidemment, il manquait un 'E' entre le 'D' et le 'F'

Il faudra intégrer cette correction sur la branche master!

- Modifiez le fichier pour faire la correction
- Commitez
- Pushez
- Mergez la branche sur master
- Pushez master

PARTIE 5

La branche file-second n'a plus de raison d'être vous pouvez la Supprimer
- Supprimer la branche file-second local et son upstream


----------

* English Version *

PART 1:
You have worked hard and the result is beautiful.
But somehow there's a bug.

It's late, your partner wants you to go home.

Hell, maybe a good night sleep (or a good night something else)
will help you find that stupid bug.

So you want to go home, but you don't want to leave the work unsaved,
that would be unprofessional. And you're a pro.

So, as the code cannot be merged into master yet, you decide to create a branch.

- Create and checkout a new branch named "file-second"
- Commit the current state
- Push it (remember, the branch does not exists yet on origin)


PART 2:
Your mind is clear and ready to tackle that nasty bug.
As you march to your desk like the conquerant you are, your boss stops you.

There's an urgent fix that needs to go out in prod just. right. now.

- Checkout the branch master
- Pull it to get the last version
- Add a "three" to the file first.txt
- Commit and push the changes to that new file


PART 3:
Now is the time to tackle the problem, let's get back to your work.

- Checkout the branch file-second


PART 4:
Of couuuuurse !
You found it, the 'E' is missing between 'D' and 'F'

After fixing the bug, the awesomeness can be mnerged into master.

- Modify the file so that it's beauty is complete
- Commit the difference
- Push it
- Merge it into master
- Push master
- Brag


PART 5:
You are a good citizen (or at least in this story we assume you are).
You are not working anymore on the branch file-second

- Delete the branch file-second both localy and in origin
