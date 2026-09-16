# 3. IPC, fenetre et frontiere de securite

Electron relie le processus principal et le rendu par des points d entree explicites. main.js et config.js forment la frontiere qui configure la fenetre, les ressources et les actions natives ; applicationMenu.js expose les commandes visibles. Chaque passage entre contenu web et systeme doit limiter les donnees acceptees et les capacites accordees. Cette separation est la cle de surete du produit : un plugin ou une page compromise ne doit pas obtenir plus de droits que necessaire. Les versions historiques d Electron et les choix de preload doivent donc etre relus avant toute reutilisation. Le README ne constitue pas une garantie de securite actuelle. Les limites de ce chapitre sont documentaires : aucune analyse dynamique n a ete executee.

Suite : [distribution](04-distribution.md).
