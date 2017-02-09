# Capítulo 4: gitbook-cli

## 3.1 ¿Qué es gitbook-cli?

**gitbook-cli** es un paquete implementado en Node.js disponible desde el gestor de paquetes 'npm' mencionado en el capítulo anterior. Nos proporciona herramientas con el fin de facilitar la creación, gestión y publicación de un libro en la plataforma GitBook también mencionada.

## 3.2 Cómo instalar gitbook-cli

Podemos hacerlo de dos maneras:

**1. Para un proyecto**

```
npm install gitbook-cli --save
```

**2. De manera global**

```
npm install -g gitbook-cli
```

## 3.3 Cómo utilizar gitbook-cli

El primer uso que nos puede interesar es el crear un libro. Para ello utilizaremos:

```
gitbook-cli init <book_name>
```

donde book_name es el nombre del libro que queremos crear

Además podemos 'publicar' el libro de manera local con el fin de testear el libro
