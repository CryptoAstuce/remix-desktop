# 2. Fichiers locaux et workspace

L avantage principal de Desktop est l acces direct au systeme de fichiers. Le menu Open Folder selectionne un dossier actif qui devient le workspace de l explorateur Remix. Cette integration evite la capacite limitee du stockage local du navigateur et rend le controle de version comparable a celui d un IDE classique. Le module selectFolder.js concentre la selection et transmet le resultat au reste de l application. L acces local reste une operation sensible : le perimetre du dossier choisi doit etre compris avant d autoriser lecture et ecriture. Les erreurs de permissions ou de chemin doivent etre traitees par l interface. Les limites de ce chapitre sont documentaires : aucun dossier n a ete ouvert.

Suite : [communication entre processus](03-ipc-securite.md).
