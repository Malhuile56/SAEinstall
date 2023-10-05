# <span style = "color : orange">README SAE 1-Système Malo Dantec</span>

#### Dans ce README se trouve les commandes et les explications nécessaires pour réaliser les différentes installations d'une Machine Virtuelle, Ubuntu, JavaScript et Docker.

## <span style = "color : lightblue">Installation de la Machine Virtuelle</span> ##
#### 1- Choix de la Machine Virtuelle 

###### J'ai fait le choix d'installer une machine virtuelle plutôt qu'un 'dualboot' pusiqu'une machine virtuelle permet une meilleure isolation, c'est-à-dire que les plantages et les erreurs de la machine n'affecteront pas le système hôte. La machine virtuelle peut nous permettre également une meilleure gestion et une meilleure sécurité, ce qui est utile lorsque des menaces éventuelles affectent la VM et donc ne sont uniquement limitées à la VM et n'affectent pas le système hôte.

#### 2- Installation et configuration de la machine virtuelle (VM)

######

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