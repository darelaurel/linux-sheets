
cat file >res 2>>errors.log : show file in res2 or create errors.log file if it's not exist

cat file >res 2>&1 : envoie le resultat de la cmd(error ou standard) dans res

cat < file : affiche file (flux d'entrée)