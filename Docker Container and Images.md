```bash
docker images
```
Der Befehl "docker images" listet die lokal verfügbaren Docker-Images auf dem System auf.

```bash
docker ps -a
```
Der Befehl "docker ps -a" listet alle Container auf dem Docker-Host auf, sowohl die laufenden als auch die gestoppten.

```bash
docker stop m122
```
Stopt den Container

```bash
docker run -itd --rm --name myContainer myImage
```
startet das Image mit dem name myContainer und der Container wird beim stop gelöscht(--rm)

```bash
docker exec -it myContainer bash
```
Dieser Befehl öffnet die Shell in einem laufenden Docker-Container namens "myContainer".

