# Npc Protector

Patcher Synthesis qui marquer les PNJ nommés de Skyrim comme protégés

## Inspiration

Ce patcheur a été inspiré par [Protect your People - PyP - Better NPC Protection SE](https://www.nexusmods.com/skyrimspecialedition/mods/10297) il marque les mêmes PNJs comme protégés comme la version Legacy de ce mod, je pourrais ajouter les PNJs de Cutting Room Floor dans le futur, mais je n'utilise pas ce mod.

## Comment ça marche

Le patcheur a une simple liste des EditorIDs de tous les PNJs nommés qui devraient être marqués comme protégés.
Pendant le patching, il passe en revue tous les PNJs et vérifie s'ils sont dans la liste et s'ils ne sont pas déjà marqués comme essentiels ou protégés, alors il copie l'enregistrement et ajoute le flag protégé au PNJ.

## Expansion

Si vous voulez ajouter des PNJ, vous devez les ajouter au code source pour le moment, à l'avenir, j'espère les extraire dans un fichier séparé que les utilisateurs pourront facilement modifier, c'est à dire si je me donne la peine car je suis paresseux.

## Version à utiliser
0.30.4 et 0.19.2

# Crédits
Un très grand merci à Phlasriel qui a gentiment modifié le code pour qu'il fonctionne avec les particularités de la langue française.
