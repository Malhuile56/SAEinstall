# <span style = "color : orange">README SAE 1-Système Malo Dantec</span>

#### Dans ce README se trouve les commandes et les explications nécessaires pour réaliser les différentes installations d'une Machine Virtuelle, Ubuntu, JavaScript et Docker.

## <span style = "color : lightblue">Installation de la Machine Virtuelle</span> ##
#### 1- Choix de la Machine Virtuelle 

###### J'ai fait le choix d'installer une machine virtuelle plutôt qu'un 'dualboot' pusiqu'une machine virtuelle permet une meilleure isolation, c'est-à-dire que les plantages et les erreurs de la machine n'affecteront pas le système hôte. La machine virtuelle peut nous permettre également une meilleure gestion et une meilleure sécurité, ce qui est utile lorsque des menaces éventuelles affectent la VM et donc ne sont uniquement limitées à la VM et n'affectent pas le système hôte.

#### 2- Installation et configuration de la machine virtuelle (VM)

###### - Pour commencer l'installation de votre VM, vous aurez besoin d'aller sur le site "https://www.virtualbox.org/" et d'installer VirtualBox7.0 et choisir de l'installer sur votre système d'exploitation de votre système hôte. 
###### - Ensuite, vous aurez besoin d'installer l'ISO de Ubuntu sur le site "https://www.ubuntu-fr.org/download/" et installer la version recommandée (version 22.04 de Ubuntu). L'ISO est le fichier que vous téléchargez quand vous voulez créer un disque de démarrage pour installer Ubuntu sur votre ordinateur.
###### - A la suite des installations, ouvrez VirtualBox et commencez à configurer votre machine virtuelle en suivants les instructions suivantes : Créez une nouvelle machine, Indiquez son nom, puis enregistez-la. Ensuite, mettre Linux comme système d'exploitation et choisir Ubuntu(64-bit). Puis, choisissez la taille de la mémoire que vous voulez allouer à votre machine (je vous recommande d'allouer seulement la moitié de la mémoire de votre pc à votre machine). Commencez à créer votre disque virtuel en lui allouant environ 40Go de stockage, puis créez-le.

#### Par la suite, grâce à cette installation de machine virtuelle nous pourrons installer et/ou tester, à l'aide d'un terminal, Javascript, VsCode, Docker en effectuant des commandes.  

## <span style = "color : lightblue">Installation de VsCode</span>
#### 1- Dans un terminal, entrez cette commande pour installer VsCode :

```
  sudo apt install --classic code
```

#### 2- Puis, entrez cette commande pour ouvrir VsCode :

```
  code
```

## <span style = "color : lightblue">Installation de JavaScript</span>
#### - Dans un terminal, entrez ces commandes pour installer JavaScript :

```
  sudo apt install default-jdk
```

```
  sudo apt-get install nodejs
```

## <span style = "color : lightblue">Installation de docker</span>
#### - Dans un terminal, entrez ces commandes afin d'installer Docker :

```
  sudo apt install docker
```

```
  sudo snap install docker
```

## <span style = "color : lightblue">Liaison entre GitHub et VsCode</span>
#### 1- Configurer VsCode et GitHub :

###### Pour lier GitHub et VsCode, il faudra faire en amont des commandes : installer l'extension VsCode "GitHub Codespaces, créer un répertoire sur GitHub, faire "Clone Repository" sur VsCode et enregistrez-le. Maintenant, passez à l'étape 2.

#### 2- Dans le terminal de VsCode, entrez ces commandes pour lier VsCode avec GitHub:

```
  git add <nom du fichier.extension>
```

```
  git config --global user.email <email>
```

```
  git config --global user.name <nom>
```

```
  git commit -m "ex:création du fichier"
```
#### D'après les instructions ci-dessus, vous devriez avoir réussi à installer tout ce dont vous avez besoin pour créer environnement de travail complet.
#### Merci d'avoir lu mon README.
