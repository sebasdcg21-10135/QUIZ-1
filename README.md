# QUIZ-1
1. Inicialización del repositorio local:
   $ git init
   Initialized empty Git repository in /ruta/a/tu/carpeta/.git/

2. Añadir el archivo `suma.c++` al repositorio:
   $ git add suma.c++
   $ git add .

3. Realizar el commit con el mensaje:
   $ git commit -m "Agregar programa de suma en C++"
   [master (root-commit) a1b2c3d] Agregar programa de suma en C++
   1 file changed, 12 insertions(+)
   create mode 100644 suma.c++

4. Vincular el repositorio local con el repositorio remoto en GitHub:
   $ git remote add origin https://github.com/tu-usuario/tu-repositorio.git

5. Subir los cambios al repositorio en GitHub:
   $ git push -u origin master
   Counting objects: 3, done.
   Writing objects: 100% (3/3), 1.25 KiB | 1.25 MiB/s, done.
   Total 3 (delta 0), reused 0 (delta 0)
   To https://github.com/tu-usuario/tu-repositorio.git
      a1b2c3d..d4e5f6g  master -> master

6. Ver el log de commits:
   $ git log --oneline
   a1b2c3d (HEAD -> master) Agregar programa de suma en C++
   d4e5f6g Mensaje de commit anterior
