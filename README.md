# iw2023ittepic

# Realizar el comit inicial y crear el archivo README
echo "# iw2023ittepic" >> README.md
git init
git add README.md
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/Lluan12/iw2023ittepic.git
git push -u origin main

# ignorar archivos
echo . > privado.txt
mkdir privada

.gitignore


# Agregar archivos, crear el tag y subir los cambios
echo . > 1.txt
git tag v0.1
git add .
git commit -m "Agregacion del tag"
git push