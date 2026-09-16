# 1. Architecture Electron de Remix Desktop

Remix Desktop est une enveloppe Electron autour de l IDE Remix. Le processus principal prepare la fenetre, le menu et les ponts avec le systeme ; le rendu affiche l application web et ses plugins. Le depot separe cette orchestration de la logique de l interface afin de conserver une experience proche de Remix en ligne. La configuration determine notamment l URL ou les ressources chargees et les options de fenetre. Ce choix donne un acces natif aux fichiers tout en conservant les contraintes d une application web embarquee. Le depot est ancien et le README le signale comme obsolete au profit d une nouvelle version. Les limites de ce chapitre sont documentaires : aucune installation ni execution n a ete realisee.

Suite : [fichiers et workspace](02-fichiers-workspace.md).
