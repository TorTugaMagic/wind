# WSL subsistema y docker 

```powershell
#Desde el terminal de Poweshell
   wsl --install -d Ubuntu-24.04 # Puedes poner la version de tu preferencia.
   wsl -l -o # Antes puedes elegir la version disponible de tu preferencia. lo anterior te mostrará todas las versiones disponibles para intalar.

   wsl -l -v  # depsues puedes cmprobar con el sigueinte comando.

   wsl --set-default-version <Version # para agregar la version de wsd 1 o 2

   wsl -s Debian #  Puedes intalar dos versione y con este comando puedes elegir la que gustes como determanda. 

   wsl -d Debian # si tienes instalado varias versiones puede usar este comando  para elegir la version que quieres usar. desde powershell

```

```Powershell
#Powershel
   wsl # desde powershel para usar la distruibucion predeterminada.
   wsl -d Debian # para usar una de las distribuciones instaladas.

```

# GIT en Subsystema
##
```BASH
    mkdir wind
    touch alice.ipynb
```
```BASH
    git add .
    git status # para ver el estado del git 
    git commint -m "Primeros archivos del subsystem"
    git log # para ver los commit realizados.
```

```BASH
    git branch <tort>
```


```BASH
    git push -u origin tort
```

## El correro Tiene que coincidir con la github y asi como el usuario.
```BASH
   git config --global user.email "tort@github.com"
   git config --global user.name "tort"

    #Despues git push

   git push -u origin tort
```
