apt-get -f install : install all missing dependancies
 

dpkg -i file.deb ==>install standalone package file

dpkg -P ==> delete package & dependancies

dpkg --force-all --purge ==> delete package & dependancies & config files

apt-get update : met a jour la liste des depots

apt-cache search <name> :recherche le package name


apt-get autoremove <name> : supprime package & dependances du package

apt-get --purge <name> : suprime fichiers de config du package


apt-get autoremove --purge <name> : suprime package, dependances & files de config ===>
les  fichiers personnels sont toujours présents dans mon HOME ==> a supprimer manuellement

apt-get upgrade : met a jour des depots & dependances

apt-get remove $(deborphan)  ===> supprime tous les packages orphelins


apt-get dist-upgrade : met a jour des depots & dependances & potentiels nouvelles dependances

### INSTALLER DEPUIS UN PPA(Personal Package Archive)

sudo add-apt-repository ppa:ppaPath
apt-get update namePackageOfPPA
apt-get install <paquetOfPPA>













