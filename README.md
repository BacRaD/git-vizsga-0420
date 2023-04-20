git init -> inicializálva

git add .gitignore -> .gitignore hozzáadva a staging areához
$ git commit -m ".gitignore hozzáadva" -> commit szöveggel hozzáadva a main-hez

$ git branch console -> console nevű ág létrehozva
$ git checkout console -> átváltás az új ágra

$ git add . -> változások hozzáadása a staging areához (app.js, README.md)
$ git commit -m "Console.log megjelenítése betöltődéskor" -> commit szöveggel hozzáadva a console ághoz

$ git add style.css -> Háttér változtatás miatt a css hozzáadva a staging areához
$ git commit -m "Háttér megváltoztatva" -> commit szöveggel hozzáadva a console ághoz

git checkout main -> visszalépek a mianbe 
git merge console -> összefésülöm vele a consolt-t (marad a main mert abból indítottam)

$ git remote set-url origin git@github.com:BacRaD/git-vizsga-0420.git -> megadom a távoli gyűjteményt 
git push -u origin mian -> feltöltöm