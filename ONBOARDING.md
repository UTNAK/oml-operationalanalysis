# ONBOARDING

## Install VSCODE
* [VSCODE](https://code.visualstudio.com/)


## Install JAVA version 21
* [JAVA 21](https://docs.aws.amazon.com/corretto/latest/corretto-21-ug/downloads-list.html)

```bash
java --version
```

* You can get responces like this

```
openjdk 21.0.7 2025-04-15 LTS
OpenJDK Runtime Environment Corretto-21.0.7.6.1 (build 21.0.7+6-LTS)
OpenJDK 64-Bit Server VM Corretto-21.0.7.6.1 (build 21.0.7+6-LTS, mixed mode, sharing)
```

## Install Git
* Install Git: [https://git-scm.com/install/](https://git-scm.com/install/)
* Check with this command 

```bash
git --version
```

## OML-Luxor
* [OML-Luxor](https://github.com/opencaesar/oml-luxor)
* Install From *.vsix

![alt text](img/image.png)


## OML-Vision
* [OML-Vision](https://github.com/opencaesar/oml-vision/releases/tag/v0.3.0)
* Install From *.vsix


## Clone This [repository](https://github.com/UTNAK?tab=repositories)

```bash
git clone https://github.com/UTNAK/oml-operationalanalysis.git
cd oml-operationalanalysis
```

## Build / Load

```bash
./gradlew build
```

```bash
./gradlew load
```

## Access Web Browser

[http://localhost:3030](http://localhost:3030)

![alt text](img/image-1.png)



# Setup Environments for Analysis Scripts
[script](ONBOARDING.md)


- Install [Quarto](https://quarto.org/)
- Install [R](https://cran.rstudio.com/)
- Install [RStudio](https://posit.co/download/rstudio-desktop/)

```bash
R --version
quarto --version
```