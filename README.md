# bootstrap-poste-dev
**Prise en main de son poste de développement**

## Installation

#### Gestionnaire de paquets
  * MAC
    * [Homebrew](https://brew.sh/index_fr.html)
    * _Recette_ : **`brew -v`**
  * Ubuntu
    * _Recette_ : **`apt -v`**
  * Windows
    * [Powershell](https://docs.microsoft.com/en-us/powershell/scripting/setup/installing-windows-powershell?view=powershell-6)
    * _Recette_ : **`Get-Host`**

#### Navigateur Web
  * [Chrome](https://www.google.com/chrome/browser/desktop/index.html)

#### Git
  * [Git](https://git-scm.com/downloads)
  * _Recette_ : 
    * **`git --version`**
    * **`git clone https://github.com/celinegilet/bootstrap-poste-dev`**

#### Java (Java Development Kit)
  * [Java](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
  * _Recette_ : **`java --version`**

#### Maven
  * [Maven](https://maven.apache.org/download.cgi)
  * Sous MAC : **`brew update`** **`brew install maven`**
  * Ubuntu : **`sudo apt install -y maven`**
  * _Recette_ : 
    * **`mvn -v`**
    * [Tests unitaires java + maven](https://github.com/celinegilet/java-maven-kata)

#### Gradle
  * [Gradle](https://gradle.org/install/)
  * Sous MAC : **`brew update`** **`brew install gradle`**
  * Ubuntu :
    * **`sudo add-apt-repository ppa:cwchien/gradle`**
    * **`sudo apt update`**
    * **`sudo apt install -y gradle`**
  * _Recette_ : 
    * **`gradle -v`**
    * [Tests unitaires gradle + maven](https://github.com/celinegilet/java-gradle-kata) 

#### Node / Npm
  * [Node + Npm](https://nodejs.org/en/download/)
  * _Recette_ : 
    * **`node -v`**
    * **`npm -v`**
    * [Tests unitaires NodeJs](https://github.com/Akhilian/NodeJSKata)
  * _Facultatif_ : installation d'un gestionnaire de version Node.js [N](https://github.com/tj/n) pour switcher d'une version à une autre

#### IntelliJ
  * [IntelliJ Version Ultimate](https://www.jetbrains.com/idea/download) avec licence
  * [Tests unitaires java + maven](https://github.com/celinegilet/java-maven-kata)
  * [Tests unitaires gradle + maven](https://github.com/celinegilet/java-gradle-kata)
  * [Prendre en main ses raccourcis](https://resources.jetbrains.com/storage/products/intellij-idea/docs/IntelliJIDEA_ReferenceCard.pdf)
  * [Pb de raccourcis sous MAC](https://youtrack.jetbrains.com/issue/IDEA-165950#comment=27-2053321) 
  * Customiser **File and Code Template** pour les tests (Given/When/Then)
  * Installer les **plugins** de base (GIT/ESLint/editorconfig)

#### VirtualBox / Vagrant
  * [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
  * [Vagrant](https://www.vagrantup.com/downloads.html)
  * _Recette_ : se connecter sur une image vagrant en **`ssh`**

#### Text/Code Editor
  * [Visual Studio Code](https://code.visualstudio.com/)
  * [Atom](https://atom.io/)
  * [SublimeText](https://www.sublimetext.com)
  * [Nodepad++](https://notepad-plus-plus.org/download/)

#### Amazon CLI
  * [Amazon CLI](http://docs.aws.amazon.com/fr_fr/cli/latest/userguide/installing.html)

#### Ansible
  * [Ansible](http://docs.ansible.com/ansible/latest/intro_installation.html)
  * [Installation pour MAC](https://valdhaus.co/writings/ansible-mac-osx/)

## Notes
  * [Index des installations via brew](http://brewformulas.org/)
  * [Index des artifacts via maven](https://mvnrepository.com/)
  * [Index des boxes Vagrant](https://app.vagrantup.com/boxes/search?utf8=%E2%9C%93&sort=downloads&provider=&q=)
  * [Tuto usage vagrant](http://sourabhbajaj.com/mac-setup/Vagrant/README.html)
