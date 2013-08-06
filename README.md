proy_serv_web_grupo1
====================

Repositorio para el proyecto de Servicios Web, 2013-2.

#Obtener repositorio

Para obtener el repositorio:

1) Tener cuenta en GitHub y registrar SSH key del pc en donde se encuentre.
2) Realizar un fork del repositorio desde la pagina de GitHub.
3) Crear un clone del repositorio en su cuenta de GitHub.
   
   git clone git@github.com:"USUARIO"/"REPOSITORIO"

#Comandos basicos para agregar cambios al repositorio:

- git add . (Agrega todos los archivos nuevos y modificados en el repositorio local)
- git commit -a (Realiza commit del al repositorio local)
- git push origin master

Despues realizar el Pull Request por la pagina de GitHub.

#Rebase del repositorio

Para realizar el rebase de los repositorios se realizan los siguentes comandos:

- git remote add "Nombre" "direccionrepo" ( Agrega el link al repositorio oficial ) Nota: solo se realiza  una vez.
- git fetch "Nombre" ( Traer cambios del repositorio oficial )
- git rebase "Nombre"/"Rama" ( Aplicar cambios al repositorio local )
- git push origin master ( Aplicar los cambios al repositorio en GitHub ) 