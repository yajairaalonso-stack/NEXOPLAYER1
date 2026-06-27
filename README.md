#NexoPlayer# Modulo 2
Yajaira Melissa Alonso Martinez
Yajaira Rachel Marroquin Alfaro

Nexo player es una herrarienta o una pagina we de streameing para ver series y peliculas animadas, donde se pueden 
encontrar distintos tipos de peliculas animadas, tanto como romanticas, accion y historia.

#CaracteristicasPrincipales:
#Encabezado  atratactivo con una serie de imagens donde se aprecia muchas peliculas anime (Poster)
#Secccion de bienvenida con mensaje de introduccion a la apagina
Catalogos de estrenos 7 animes en tendencia
Tienda en linea d0onde se spueden apreciar los precios 
Footer donde se escuentra informacion de la web


#Tecnologías utilizadas:
#HTML5 para la estructura semántica.
#Style en CSS para estilos, colores y tipografía.
#Flexbox y Grid para organizar tarjetas y secciones.
#Media Queries para responsividad en móviles.

Hola me puedes mejorar este bloque de codigo optimizanmdolo y genera colores con contrates AAA y anade variables css 

.nav ul {
  list-style: none;
  display: flex;
  gap: 35px;
  justify-content: center;
}
.nav a {
  color: #e9ebe3;
  text-decoration: none;
  font-weight: bold;
  font-size: 1.3rem;
}
.nav a:hover { color: #c7a82a; }

.inicio {
  background: hwb(311 11% 25% / 0.403);
  padding: 120px 40px; /* más espacio */
}
.welcome-box {
  text-align: center;
  margin-bottom: 50px;
}
.welcome-box h2 {
  font-size: 3rem; /* más grande */
  margin-bottom: 25px;
  color: #112b44;
}
.welcome-box p {
  font-size: 1.5rem;
  line-height: 1.8;
}
.banner-img {
  width: 100%;
  border-radius: 12px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.3);
}

.video-grid, .product-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 20px;
}

.card {
  background: #cb88c0;
  border-radius: 10px;
  padding: 15px;
  text-align: center;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}
.card img { width: 100%; border-radius: 8px; }
.card button {
  background: #3c9daa; color: #d6d4d4; border: none;
  padding: 10px 15px; border-radius: 6px; cursor: pointer;
}

REsulatdos
:root {
  /* Paleta accesible con contraste AAA */
  --color-bg-primary: #1a1a2e;   /* azul oscuro */
  --color-bg-secondary: #16213e; /* azul más profundo */
  --color-accent: #e9c46a;       /* dorado contrastante */
  --color-text-light: #f1faee;   /* casi blanco */
  --color-text-dark: #0d1b2a;    /* azul muy oscuro */
  --color-card-bg: #264653;      /* verde azulado */
  --color-card-btn: #2a9d8f;     /* verde brillante */
  --color-card-btn-text: #ffffff;
}

/* Navegación */
.nav ul {
  list-style: none;
  display: flex;
  gap: 2.2rem;
  justify-content: center;
}
.nav a {
  color: var(--color-text-light);
  text-decoration: none;
  font-weight: bold;
  font-size: 1.2rem;
  transition: color 0.3s ease;
}
.nav a:hover {
  color: var(--color-accent);
}

/* Sección Inicio */
.inicio {
  background: var(--color-bg-primary);
  padding: 120px 40px;
  color: var(--color-text-light);
}
.welcome-box {
  text-align: center;
  margin-bottom: 50px;
}
.welcome-box h2 {
  font-size: 3rem;
  margin-bottom: 25px;
  color: var(--color-accent);
}
.welcome-box p {
  font-size: 1.4rem;
  line-height: 1.8;
  color: var(--color-text-light);
}
.banner-img {
  width: 100%;
  border-radius: 12px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.4);
}

/* Grids */
.video-grid, .product-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 20px;
}

/* Tarjetas */
.card {
  background: var(--color-card-bg);
  border-radius: 10px;
  padding: 15px;
  text-align: center;
  box-shadow: 0 4px 8px rgba(0,0,0,0.2);
  color: var(--color-text-light);
}
.card img {
  width: 100%;
  border-radius: 8px;
}
.card button {
  background: var(--color-card-btn);
  color: var(--color-card-btn-text);
  border: none;
  padding: 10px 15px;
  border-radius: 6px;
  cursor: pointer;
  font-weight: bold;
  transition: background 0.3s ease;
}
.card button:hover {
  background: #21867a; /* tono más oscuro para feedback */
}



Preguntas
¿El código generado por la IA respetó el diseño responsivo? 
Si la estructura se mantuvo con flexbox y grid lo que asegura que los elementos se adapten auntomatucamente.
¿Qué ventajas técnicas aportó la refactorización de la IA en comparación con su código manual? 
En realidada mas que todo cambio por que centralizo lo colores y tipografías, también mejoro la accesibilidad y se ve un código mas limpio.


