<!-- TITLE: [FR] Commandes du chat -->
<!-- SUBTITLE: Décrit toutes les commandes de discussion disponibles, même les commandes non évidentes ou non documentées. -->

# Commandes du chat Discord

Alors que l’accès à certaines des commandes "slash" de Discord est assez évident, il y a certaines choses qui peuvent être faites dans la boîte de rédaction d’un message qui sont quelque peu non documentées (ou difficiles à trouver). Pour vous éviter d’avoir à fouiller dans les journaux des changements et les articles de support, voici ce que vous pouvez faire dans la zone de texte :

* **Réagir au message précédent** (ordinateur et iOS) : pour ajouter une réaction au message précédent dans le chat, écrivez simplement `+:nomdusmiley:` dans la zone de texte et envoyez-le. Par exemple, écrire `+:smile:` ajoute la réaction sourire. Cela fonctionne même avec les emojis personnalisés, en supposant que vous êtes sur le bon serveur ou que vous avez Nitro !
* **Modifier votre message précédent avec la flèche vers le haut** (ordinateur uniquement) : au lieu de cliquer avec le bouton droit de la souris sur un message, de sélectionner « Modifier le message » et de cliquer dans la zone d’édition, vous pouvez simplement appuyer sur la flèche du haut pour éditer votre dernier message sur ce canal !
* **Corriger une faute de frappe rapidement avec s/** (ordinateur et iOS) : vous avez écrit "hye" au lieu de "hey" et vous souhaitez réparer cela rapidement ? Utilisez `s/hye/hey` ! Utiliser une variation de `s/un mot/un autre mot` va éditer votre message précédent. Cela ne change qu’un seul cas (le premier), mais pour réparer rapidement une faute de frappe, c’est pratique !
* **Récupérer l’ID d’un élément à mentionner** : tout ce qui peut être mentionné dans la discussion (emoji, utilisateur, canal, rôle, etc.) peut être utilisé pour obtenir l’identifiant de cet élément. Par exemple, tapez `\@user` pour obtenir l’identifiant d’un utilisateur. `\@role` pour obtenir un ID de rôle, `\#channel` pour obtenir un identifiant de canal. Les emojis Unicode réguliers vous donneront le vrai caractère Unicode (au lieu de l’image) qui pourra alors être utilisé dans votre nom d’utilisateur, donc `\:poop:` au contenu de votre cœur !
* **Obtenir un emoji Unicode** : Si vous échappez un emoji avec un `\`, vous obtiendrez sa forme Unicode. Ainsi, `\:smiley:` ne retourne pas la version Discord de `:smiley:` mais retourne la version Unicode (😃). Note : cela ne fonctionne qu’avec les emojis standard, pas avec ceux personnalisés.

## Commandes slash

Ces commandes commençant par un slash (une barre oblique) ne sont disponibles que sur ordinateur et iOS. Malheureusement, les utilisateurs d’Android n’ont pas cette chance.

* `/tableflip` : envoie `(╯°□°）╯︵ ┻━┻` dans la discussion.
* `/unflip` : envoie `┬─┬ ノ( ゜-゜ノ)` dans la discussion.
* `/shrug` : Envoie `¯\_(ツ)_/¯` dans la discussion.
* `/me <un message>` : envoie votre message en italique, dans le style de l’IRC. Identique au simple envoi de votre message avec `*<un message>*` (`*` pour l’italique).
* `/nick <nouveau pseudo>` : modifie votre pseudonyme sur le serveur à ce que vous placez après la commande. Nécessite l’autorisation « Changer de pseudo » sur le serveur.
* `/tenor <recherche>` et `/giphy <recherche>` : cherche des GIF animés sur internet, en utilisant l’un des deux sites.
* `/xivdb <recherche>` : cherche dans la base de données de **XIVDB** et envoie un lien à n’importe quel contenu en jeu.

> Lorsque `<quelque-chose>` est utilisé, cela indique que vous pouvez y insérer n’importe quels mots, à l’exception du `<>`. C’est un « espace réservé ».
