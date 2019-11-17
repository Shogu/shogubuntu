# shogubuntu
Mémo pour installer et paramétrer POP!_OS sur un XIAOMI AIR 13.3 2017 (Optimus)


Pourquoi POP!_OS?

Cet OS propose un clone d'Ubuntu adapté, donc un système prêt à l'emploi mais tweakable à souhait, basé sur un Gnome-Shell proche de la version Vanilla, avec un réel effort fait sur l'esthétique et la cohérence du thème, et SURTOUT une prise en charge très aboutie de la double carte graphique Optimus.

Bref cet OS signé des américains System76 propose par défaut un ensemble de critères que je devais préalablement réaliser à la main.

Téléchargement : (ATTENTIOn prendre la version INTEL/AMD et non la version NVIDIA. La 1ere installera de toute façon le pilote de la discrete card, tandis que la 2nde n'installe pas les drivers Intel, visiblement): 
https://pop-iso.sfo2.cdn.digitaloceanspaces.com/19.10/amd64/intel/10/pop-os_19.10_amd64_intel_10.iso


INSTALLATION :

Pop! gère nativement l'UEFI grâce à systemd-boot : adieu Grub!

J'ai fait le choix d'installer à la main avec une partition EFI d'environ 500 MO, et une partition system+home sur le reste du SSD : Dropbox synchronise mes documents donc nul besoin de faire un /home à part pour les réinstalls comme à l'époque.

Pas de partition swap à l'installation, j'installe un swap dynamique géré par systemd.



Réglages communs : 

-Prise en charge des langues
-Suppression des logiciels inutiles (ATTENTION laisser Geary et Evolution pour ne pas casser l'agenda intégré à Gnome. Ne pas supprimer l'Aide car le paquet pop-desktop risque 
Réglages d'interface et d'ergnonomie 

-Extensions Gnome Shell

-Réglages DCONF



Réglages Autonomie

Réglages Optimisation système


