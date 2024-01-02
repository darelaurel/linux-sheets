
###whereis
whereis file : search binary, packages


####mlocate & locate
sudo updatedb : va mettre a jour la BD de mlocate

mlocate: dispose d'une BD ayant des index de tous les files du OS

/var/lib/mlocate: show database

###find
find -name "fileName" -type d|f (dir or file) -size +5M


###apropos
apropos cmd : liste section du manuel de cmd

###find
find /media/darel/DATA -name "redux" : recherche redux dans /media/darel/DATA


###grep
grep occurence file : recherche et affiche occurence dans file

###uniq
trie les elements sans doublon dans un file

###sort
trie les elements dans un file


###wc file
affiche nombre de ligne, nombre de mots, nombre d'octet du file

###cut 

cut -d : -f 1 file.txt

Affiche la premiere colonne delimitée par :
exemple   1: ABCD => output 1  if -f 2 output => ABCD