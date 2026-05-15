<picture>
  <img alt="git essentials logo" src="https://github.com/paobtorres/gitessentials2026/blob/main/banner/banner.png">
</picture>

# Curso Git Essentials 2026

> Bienvenidos a una nueva edición del Curso "Git Essentials: curso básico para principiantes"

## Autenticación ssh 

Usando el protocolo SSH, te puedes conectar y autenticar con servicios y servidores remotos. Con las claves SSH puedes conectarte a GitHub sin necesidad de proporcionar el nombre de usuario y el personal access token en cada visita. También puedes usar una clave SSH para firmar confirmaciones.

[Documentación oficial](https://docs.github.com/es/authentication/connecting-to-github-with-ssh).

1. Generar claves ssh nuevas: 
```ssh-keygen -t ed25519 -C "your_email@example.com"```
2. Agregar clave SSH al ssh-agent
 ```eval "$(ssh-agent -s)"```
3. Agregar llave privada SSH al ssh-agent
   ```ssh-add ~/.ssh/id_ed25519```

4. Incorporar clave a la cuenta de github: [intrucciones](https://docs.github.com/es/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)
