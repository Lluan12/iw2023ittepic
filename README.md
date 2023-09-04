# iw2023ittepic

# Práctica (Primera Parte)

![1](https://github.com/Lluan12/iw2023ittepic/assets/103333263/cfd87f4b-a335-4095-9472-e66d841b26f4)
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

![2](https://github.com/Lluan12/iw2023ittepic/assets/103333263/9eb309a8-7c4e-44ab-af5c-eeb607c680a0)
![3](https://github.com/Lluan12/iw2023ittepic/assets/103333263/23ba33ce-a749-4417-a6ea-99bc01f0f344)


# Agregar archivos, crear el tag y subir los cambios
echo . > 1.txt
git tag v0.1
git add .
git commit -m "Agregacion del tag"
git push 


# Cuenta de github, verificacion a dos pasos y la clave
![4](https://github.com/Lluan12/iw2023ittepic/assets/103333263/8021ff82-df7d-4f6b-a10c-bc2a11a0d88c)

![5](https://github.com/Lluan12/iw2023ittepic/assets/103333263/2cd3d9a8-ee6a-4d4c-b1b3-99722b119ff3)

ssh-keygen
![6](https://github.com/Lluan12/iw2023ittepic/assets/103333263/fcbc1515-60cd-4f87-afaa-57ef6e0590bc)

![7](https://github.com/Lluan12/iw2023ittepic/assets/103333263/14f7920b-20d4-4e6d-b3fb-b46d57fce1fb)


# Creacion de tabla

    Nombre     |    Github
--------------------------------
Ivan Robles    | https://github.com/IvanRobles19/iw2023ittepic.git
---------------------------------------------------------------------
Paul Ochoa     | https://github.com/PaulOchoa952/iw2023ittepic.git
---------------------------------------------------------------------
Paul Machain   |  https://github.com/PaulRazon/iwittepic2023.git
---------------------------------------------------------------------
Erick Ramirez  | https://github.com/Elery2711/iw2023ittepic.git
---------------------------------------------------------------------
Victor Pacheco | https://github.com/XxXelbichoXxX/iw2023ittepic.git
----------------------------------------------------------------------

![8](https://github.com/Lluan12/iw2023ittepic/assets/103333263/12635197-e6bb-486e-bf04-36189f6061c9)
![10](https://github.com/Lluan12/iw2023ittepic/assets/103333263/b7fd9d9b-1348-4b0d-8720-07d3b657a9bf)
![11](https://github.com/Lluan12/iw2023ittepic/assets/103333263/8954bb34-52c1-4341-a81b-468de75aab6a)
![12](https://github.com/Lluan12/iw2023ittepic/assets/103333263/81e67cd9-0ce2-47da-803f-49fc4503330d)
![13](https://github.com/Lluan12/iw2023ittepic/assets/103333263/dec8b36c-a0a2-4b4b-9b94-73e2c68080ac)


# Agregación de colaborador

![14](https://github.com/Lluan12/iw2023ittepic/assets/103333263/c4474cf8-1370-4a04-a4d3-cc5fc5de9148)



# Práctica (Segunda Parte)

# Crear rama y posicionar carpeta de trabajo
git branch v.02

![image](https://github.com/Lluan12/iw2023ittepic/assets/103333263/f2c89804-93e8-4961-9b19-12df7de1a45b)

git checkout v.02 

# Anadir archivo 2.txt a la rama

![image](https://github.com/Lluan12/iw2023ittepic/assets/103333263/92edd413-4f1c-4e7b-a36d-e2d11c3f5d18)

# Subir cambios al repositorio remoto

git add .
git commit -m "Agregacion de un txt a la rama"
git push --set-upstream origin v.02

# Merge directo

git checkout main
git merge v.02

![image](https://github.com/Lluan12/iw2023ittepic/assets/103333263/fb5acd8e-58b9-49ce-ac23-ac6b216011f7)


# Merge con conflicto

git add 1.txt
git commit -m "Modificacion de 1.txt"

git checkout v.02

![image](https://github.com/Lluan12/iw2023ittepic/assets/103333263/cb35af48-6256-4192-a34a-8aa1707194ea)

git add 1.txt
git commit -m "Mensaje de adios en 1.txt"

git checkout main
git log --oneline --decorate --all --graph

![image](https://github.com/Lluan12/iw2023ittepic/assets/103333263/7acfe1e1-3df3-4502-a4f4-80fe102c50e1)

![image](https://github.com/Lluan12/iw2023ittepic/assets/103333263/6adbb24e-f968-400b-b842-c52b27a94af7)

git commit -m "Conflicto arreglado"

# Crear tag y borrar rama

git tag -a v0.2 -m "Version de la practica 0.2"
git branch -D v.02

# Listado de cambios

![image](https://github.com/Lluan12/iw2023ittepic/assets/103333263/d1a212c3-ce94-420f-8c7e-b04c72d07de9)


# Creación de una organización
