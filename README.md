Página de ejemplo para explicar el manejo de Git
-------------------------------------------------
** Si el repositorio es nuevo :
echo "# Descripción de su repositorio" >> README.md
git init
git add README.md
git commit -m "Primer commit de est ereporitorio"
git branch -M main
git remote add origin https://github.com/nietomartin/nombre_de_su_repositorio_creado_en_github.git
git push -u origin main

** O si ya cuenta con el repositorio en github
git remote add origin https://github.com/nietomartin/ADR-prueba1-azuredevops.git
git branch -M main
git push -u origin main

** O si desea importar desde otro repositorio, ud puede inicializar con codigo desde Subversion, Mercurial, or TFS project
