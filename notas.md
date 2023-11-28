# Acerca de HTML

HTML es un lenguaje que se basa en etiquetas, las etiquetas tienen 6 niveles principales desde h1 hasta h6 que le indican al navegador la importancia en orden ascendente y el tamaño en que se muestra varia, letras mas grandes para h1 y mas pequeñas para h2.

tambien se pueden usar etiquetas de parrafo con "p", se pueden usar varias etiquetas p, y varias etiquetas h1 o h2... etc.

##  Estructurar el contenido 
Para agrupar las etiquetas podemos basarnos en el ejemplo de la siguiente imagen

![Estructurra de las etiquetas en HTML](img/imagen/estructura_html.jpg)

establescamos algunas reglas 

- utilizamos section casi siempre que queramos agrupar los heads "h".
- Utilizamos main siempre que queramos especificar cual es el contenido principal de nuestra pagina

# Acerca de css 
css es un codigo de estilo de selectores, lo utilizamos con una estructura basica de 

e {clave:valor;
    clave: valor;
}

donde e es una etiqueta o un div o una clase.... 

## flexbox 
para activar flexbox usamos 

e{
    display: flex;


}

debajo de esta linea puedes agregar caracteristicas de flex como justify-content: space-betwen ;, se debe tener mucho cuidado porque justify-content solo distribuye cuando el flex-direction está habilitado horizontalmente, cuando los elementos se muestran como column se debe cambiar esta caracteristica.

Flexbox solo funciona para distribuir elementos, no sirve para animar, por defecto flex-direction está asignado como flex-direction: row, pero podemos cambiarlo a flex-direction: column, por ejemplo

e{
    display:flex;
    flex-direction: column
}

distribuirá los hijos de e en columnas

 