# Week 8 - Challenge 4

# JustR-Pokémon Next.js

Crea una aplicación con Next.js, que tenga un menú de navegación con las siguientes páginas:

- Home: un texto de bienvenida
- Pokémon: un listado de Pokémon que venga de la PokeAPI (sin paginación, sólo los 10 primeros) con CSR
- Mis pokémon SSR: un listado de Pokémon que venga de tu API (sin paginación) con SSR
- Mis pokémon SSG: un listado de Pokémon que venga de tu API (sin paginación) CON SSG
- Mis pokémon ISR: un listado de Pokémon que venga de tu API (sin paginación) CON ISR, que actualice cada 20 segundos

En cada uno de los tres últimos listados, si se hace clic se debe llevar al usuario a una página de detalle del Pokémon seleccionado, generado con el método correspondiente y con fallback: true.
