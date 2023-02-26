# template
A template for the organization of files and their content so that it is easier to navigate. 
You must extract the file (unzipped) to access everything.

Un modèle pour l'organisation des fichiers et de leur contenu afin qu'il soit plus facile de naviguer.
Vous devez extraire le fichier (décompressé) pour accéder à tout.

# folow me
On instagram : instagram.com/madara_red1
Join our discord : dsc.gg/supermarche

# STYLE

<!-- Français -->
1. Plusieurs fichiers "name.css" on été crée afin de modifier plus facilement son code par exemple [footer.css](./style/structure/footer.css) contiendra uniquement le code du footer de la page, généralement le footer est le le même su l'emsemble des pages donc cela est plus pratique si on veux le modifier pour toute les pages a la fois. Mais attention! Les différentes class(.exemple) et id(#exemple) devront y correspondre, tout dépendra de comment vous nommerez celui ci.
2. Le fichier [webkit.css](./style/structure/webkit.css) contiendra tout ce qui est relatifs au webkit. Tout les fichiers devront être soigneusement lier dans votre fichier ".html" dans la "head" de la page avec la balise "<link rel="stylesheet" href="./style/structure/namefile.css">". Ils sont déclarer dans un sous dossier [structure](./style/structure/) afin d'être différencier des fichiers ".css" spécifique à chaque fichiers.
3. Pour les fichiers ".html" se trouvant dans le dossier [page](./page/) 2 "." seront nécéssaire avant "/style/..." par exemple: "../style/about.css" tout simplement car le fichier se trouve en dehors du dossier.

<!-- English -->
1. Several "name.css" files have been created in order to modify its code more easily, for example [footer.css](./style/structure/footer.css) will only contain the code for the footer of the page, generally the footer is the same on all the pages so it is more practical if you want to modify it for all the pages at the same time. But beware! The different class(.example) and id(#example) will have to correspond to it, everything will depend on how you name it. They are declared in a subfolder [structure](./style/structure/) in order to be differentiated from ".css" files specific to each file.
2. The [webkit.css](./style/structure/webkit.css) file will contain everything related to the webkit. All files must be carefully linked in your ".html" file in the "head" of the page with the "<link rel="stylesheet" href="./style/structure/namefile.css">".
3. For ".html" files located in the folder [page](./page/) 2 "." will be necessary before "/style/..." for example: "../style/about.css" simply because the file is outside the folder.

# SCRIPT

<!-- Français -->
1. Pour les scripts, ils se trouveront tous dans le dossier [script](./script/) avec comme fichier "principal" [main.js](./script/main.js) comme fichier de base, il peuvent être renommés selon leurs utilité par exemple: pour un un script qui a pour but de demander confirmation pout actualisé la page web(=beforeunload), nous allons nommés donc le fichier "beforeunload.js" et l'ajouté au "head" dans le fichier ".html" où vous voudriez que le script ai un effet. Vous pouvez également mettre le script dans votre fichier directement si ça deviens trop compliquer. Petit tips: Déclarer tout les scripts et mettre ceux que vous ne voulez pas en commentaire(CTRL + :) les "descativerons" de  votre fichier, ils seront donc ignorés.
2. Tout les types de scripts sont acceptés c'est à dire: js(JavaScript), py(Python), etc...
3. Pour les fichiers ".html" se trouvant dans le dossier [page](./page/) 2 "." seront nécéssaire avant "/script/..." par exemple: "../script/main.js" tout simplement car le fichier se trouve en dehors du dossier.

<!-- English -->
1. For the scripts, they will all be in the [script](./script/) folder with the "main" file [main.js](./script/main.js) as the base file, they can be renamed according to their usefulness for example: for a script which aims to request confirmation for updating the web page (=beforeunload), we will therefore name the file "beforeunload.js" and add it to the "head" in the file ".html" where you would like the script to have an effect. You can also put the script in your file directly if it gets too complicated. Little tips: Declare all the scripts and put the ones you don't want in comments (CTRL +:) the "descativeons" of your file, they will therefore be ignored.
2. All types of scripts are accepted, i.e.: js (JavaScript), py (Python), etc...
3. For ".html" files located in the folder [page](./page/) 2 "." will be necessary before "/script/..." for example: "../script/main.js" quite simply because the file is outside the folder.

# PICTURE

<!-- Français -->
1. Les médias ou autrement dit dans ce cas "pictures"(qui veut dire photos en anglais) se trouverons dans ce dossier, bien évidemment plusieurs format son pris en compte: .png, .jpg, .jepg, etc.. 

<!-- English -->
1. The media or in other words in this case "pictures" (which means photos in English) will be found in this folder, of course several formats are taken into account: .png, .jpg, .jepg, etc.
