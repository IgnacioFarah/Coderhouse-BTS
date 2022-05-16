# Coderhouse-BTS
Pagina de bts

"Agregué estas Keywords a todos mis html"
<meta name="keywords" content="Ignacio Farah, fandom de bts, bts, integrantes de bts, cantantes coreanos, historia de bts, musica de bts">

"Segui utilizando los titulos que tenia desde un comienzo"
<title>Arg Bts Army.</title>
<title>Biografía</title>
<title>Integrantes</title>
<title>Música</title>
<title>videos</title>

"coloque esta descripción en mis html"
<meta name="descriptions" content="Pagina fandom de bts, conoce la informacion acerca de como esta conformada esta banda de kpop">


"Utilice Extend en mis titulos secundarios como por ejemplo"

h4 { 
    @extend h2
}

h3 {
    @extend h2
}

"Agregue un nuevo archivo de sccs llamado extras.scss"
"Alli aplique un Mixin en una clase perteneciente de mi css"

@mixin size ($padding, $margin) {
    margin: $margin;
    padding: $padding;
}

.ordenar {
    @include size (0px 2px, 10px 15px);
}
