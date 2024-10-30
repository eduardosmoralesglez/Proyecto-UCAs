# Proyecto UCA`s Conectadas plus.

En este proyecto lo que se busca es crear un entorno donde las personas asociadas a las UCA puedan realizar pedidos de mensajería y paquetería, entre miembros de las UCA o con miembros asociados a la red de distribución, sin la necesidad de que un mensajero pase por sus residencias para comprobar si tienen que pedidos disponibles. Este proyecto va a mejorar la eficiencia de los portadores y los tiempos de espera para la llegada de los paquetes para los miembros.

(Lo base en un juego __"Death Stranding"__)

## Comandos usados para la creación de la rama vercion1

```code
bae2@jpexposito-VirtualBox:~/repositorios/prueba-1$ git pull origin main 
Desde https://github.com/eduardosmoralesglez/prueba-1
 * branch            main       -> FETCH_HEAD
Actualizando 1774d8f..9164686
Fast-forward
 README.md | 6 ++++--
 1 file changed, 4 insertions(+), 2 deletions(-)
bae2@jpexposito-VirtualBox:~/repositorios/prueba-1$ cat README.md 
# Proyecto UCA`s Conectadas plus.

En este proyecto lo que se busca es crear un entorno donde las personas asociadas a las UCA puedan realizar pedidos de mensajería y paquetería, entre miembros de las UCA o con miembros asociados a la red de distribución, sin la necesidad de que un mensajero pase por sus residencias para comprobar si tienen que pedidos disponibles. Este proyecto va a mejorar la eficiencia de los portadores y los tiempos de espera para la llegada de los paquetes para los miembros.

(Lo base en un juego __"Death Stranding"__)
bae2@jpexposito-VirtualBox:~/repositorios/prueba-1$ ls
img  README.md
bae2@jpexposito-VirtualBox:~/repositorios$ sudo mv prueba-1/ proyecto-UCAs
```

---

```code
bae2@jpexposito-VirtualBox:~/repositorios/proyecto-UCAs$ git checkout -b version-1
Cambiado a nueva rama 'version-1'
bae2@jpexposito-VirtualBox:~/repositorios/proyecto-UCAs$ git branch 
  main
* version-1
bae2@jpexposito-VirtualBox:~/repositorios/proyecto-UCAs$ 
```

---

```code
bae2@jpexposito-VirtualBox:~/repositorios/proyecto-UCAs$ git push -u origin version-1 
Username for 'https://github.com': eduardosmoralesglez
Password for 'https://eduardosmoralesglez@github.com': 
Total 0 (delta 0), reusados 0 (delta 0), pack-reusados 0
remote: This repository moved. Please use the new location:
remote:   https://github.com/eduardosmoralesglez/Proyecto-UCAs.git
remote: 
remote: Create a pull request for 'version-1' on GitHub by visiting:
remote:      https://github.com/eduardosmoralesglez/Proyecto-UCAs/pull/new/version-1
remote: 
To https://github.com/eduardosmoralesglez/prueba-1
 * [new branch]      version-1 -> version-1
Rama 'version-1' configurada para hacer seguimiento a la rama remota 'version-1' de 'origin'.
bae2@jpexposito-VirtualBox:~/repositorios/proyecto-UCAs$ 
```

---

![](./img/001.png)

---

```code
bae2@jpexposito-VirtualBox:~/repositorios/proyecto-UCAs$ git branch -r
  origin/HEAD -> origin/main
  origin/main
  origin/version-1
bae2@jpexposito-VirtualBox:~/repositorios/proyecto-UCAs$ 
```

---

```code

```
