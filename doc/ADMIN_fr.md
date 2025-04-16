MARL fonctionne avec le mode Local par défault, c'est-à-dire que toutes les données sont traitées dans le navigateur de l'utilisateur et que rien n'est envoyé au serveur.

Cependant MARL possède également un mode Serveur qui permet aux utilisateurs disposants de la permission d'accéder à cette application de consulter une archive stockée à une adresse donnée.
Pour activer le mode Serveur, il faut indiquer un ou plusieurs chemin(s) vers des dossiers d'archives Mastodon dans le panneau de configuration ci-dessous.
Chaque archive Mastodon doit être extraite dans le dossier indiqué (ce pourrait être par exemple sur ce serveur à l'emplacement `/home/yunohost.app/marl` si vous souhaitez que l'archive Mastodon soit inclue par défaut dans chaque sauvegarde de l'application).
En cas d'utilisation partagée, vous pourriez vouloir purger l'archive des messages privés contenus dans cette archive. Pour ce faire il existe l'outil `outbox cleanup` ([lien GitHub](https://github.com/s427/MARL/blob/main/tools/outbox-cleanup/readme.md)).
