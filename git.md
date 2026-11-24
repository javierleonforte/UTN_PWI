**Crear repositorio...**
    git init

**Para dar seguimiento a los archivos con git usamos...**
    git add .

**Para que los archivos a los que git da seguimientos los VERSIONE, usamos...** 
    git commit -m 'mensaje'

**Para renombrar la rama maestra a main...**
    git branch -m main

**Para agregar un origen remoto**
    git remote add origin dirrecion-del-repo.git

**Para saber a que direccion remota esta conectada nuestro repo** 
    git remote -v

**Para subir el ultimo commit a la nube (repositorio remoto conectado)**
    git push -u origin main

**Si queremos actualizar/sincronizar nuestro repositorio local con el remoto debemos ejecutar**
    git add .
    git commit -m 'mensaje'
    git push