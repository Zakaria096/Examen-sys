level 0
cd  ..(jusqu’à home)
cd level (vers le dossier level)
Puis ls pour afficher le contenu 
cd 00_welcome (vers le dossier welcome)
Puis ls pour afficher le contenu 
cat README.md (pour afficher le contenu du dossier README.md)
solution : bitwarrior 

level 1
cd ..(jusqu’à home)
cd level
cd 01_choice_tree (ouvrir ce dossier)
cd blue (vers le dossier blue)
cd hats(puis vers hats)
cd grey(puis vers grey)
cd solution(puis vers solution)
cd patience(puis vers patience)
cat SOLUTION.txt(pour afficher la solution enfin)
solution : patience
(Tout en utilisant ls a chaque dossier fouillis)

level 2
cd .. (jusqu’à Home)
cd level 
cd 02 (pour entrer dans le level 2)
ls -al(ls n’a pas fonctionné mais ls -al car le fichier était caché)
cd .porb( le fichier qui était caché)
ls -al(encore des fichiers cachés)
cat .solution(pour afficher la solution cachée)
solution :HiddenIsConfig

level 3
cd ..(toujours jusqu’à Home)
cd 03(pour aller vers 3)
cat .bash_history (après un ls -al .bash history s’est montré,on l’affiche ici)
solution :RepeatingHistory

level 04
cd ..(toujours jusqu’à home)
cd 04_kwisatz (vers le level 4)
cat README.nfo(c’était le seul fichier dedans qui dit d’aller vers «~»)
cd  ~(pour aller vers ~)
cd level (il y avait des dossiers mais level est le vrai)
cd 04_kwisatz(dossier dans level à afficher)
cat README2.md(c’était dans le dossier 04_kwistatz)
solution :AndOfCourseIDoKnowChown

level 5
cd ..(jusqu’à home)
cd 05_privacy(le level 05)
cat README.md(c’était dans le level 5(après chmod a+rx REAMDE.md))
solution :OKPRIVATE

N.B : On utilise ls ou ls -al a chaque dossier ouvert bien entendu 
