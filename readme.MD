# Comandos para GIT 👊🏼 💢

#### Crear un repositorio
```
git init
```

---

#### Agregar archivos al repositorio
```
git add fileName.ext
```

ó

```
git add .
```

---

#### Hacer un commit
```
git commit -m "mensaje descriptivo"
```

---

#### Verificar el status del repositorio
```
git status
```

---

#### Pushear al repositorio remoto
```
git push origin master
```

---

#### Pullear del repositorio remoto
```
git pull origin master
```

---

#### Crear una rama
```
git branch NOMBRE_RAMA
```

---

#### Cambiarse a una rama
```
git checkout NOMBRE_RAMA
```

---

#### Crear y cambiarse a una rama
```
git checkout -b NOMBRE_RAMA
```

---

#### Eliminar una rama LOCAL
```
git branch -d NOMBRE_RAMA
```
> -D (d mayúscula) para borrar sin importar cambios en esa rama

---

#### Eliminar una rama REMOTO
```
git push origin —delete NOMBRE_RAMA
```

---

#### Merge entre ramas locales
```
git checkout NOMBRE_RAMA
git merge NOMBRE_RAMA_A_MERGEAR
```

---

#### Crear una rama en REMOTO
```
git push -u origin NOMBRE_RAMA
```

---

#### Sacar del STAGE un archivo
```
git rm --cached NOMBRE_ARCHIVO
```

---

#### Borrar un archivo del repositorio que ya sido agregado
```
git rm -f NOMBRE_ARCHIVO 
```

> Eliminará al archivo de la carpeta

---

#### Para ver a donde apunta el repositorio remoto
```
git remote -v
```

#### Para cambiar la URL del repositorio remoto
```
git remote set-url origin https://github.com/USERNAME/REPOSITORY.GIT 
```

#### Para regresar a un commit anterior
```
git checkout HEAD~1 
```

> Devuelve al commit anterior. Si se quiere regresar commits más atrás, basta con cambiar el número 1 con la cantidad de commits deseada.

---

#### Para volver al último commit hecho
```
git checkout master
```

---

#### Para moverse entre commits
```
git checkout SHA
```

> Tener precaución de ver el SHA de los commits posteriores. SHA es el número del commit, generalmente los últimos 7 dígitos

---

#### Guardar cambios momentaneamente
```
git stash
```

---

#### Aplicar los cambios guardados momentaneamente
```
git checkout NOMBRE_RAMA
git stash apply
```

---

#### Eliminar los cambios guardados momentaneamente
```
git stash clear
```

---

#### Ver el historial de commits 
```
git log —oneline
```
ó 
```
git log
```
ó
```
git log --graph

```

---

#### Copiar un archivo desde otra rama / commit
```
git checkout NOMBRE_RAMA path/to/file.txt
```

---

#### Pull de una rama específica en remoto
```
git fetch (en master)
git checkout --track -b NOMBRE_RAMA
git pull origin NOMNRE_RAMA
```

---

#### Ver las ramas en remoto
```
git remote show origin 
```

---

#### Borrar un usuario global
```
git config --global --unset-all user.name (NOMBRE_USUARIO)
```

---

**Made with ❤️ by: [Javi Herrera](https://javier-herrera.com)**

*Si te parece interesante este tipo de contenido, puedes agradecerme con un Follow en mis siguientes redes sociales. Lo estimaría un montón.*

[![icon linkedin](./images/icon-linkedin.png)](https://www.linkedin.com/in/japsolo/)
[![icon instagram](./images/icon-instagram.png)](https://www.instagram.com/thefullstackdevs/)
[![icon spotify](./images/icon-spotify.png)](https://open.spotify.com/show/3J2dLuBSfzt9VVnEF8q18a)

