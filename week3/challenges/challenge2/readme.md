# Week 3 - Challenge 2

## Tour of Heroes 💀 !

Deberás de programar "Tour of Heroes".

[Aquí](https://angular.io/generated/live-examples/toh-pt6/stackblitz.html) tienes una demostración de cómo debería de verse la página (puede tardar un poco en cargar, paciencia).

## Requisitos

- **NO ES NECESARIO REPLICAR LA PARTE DE MENSAJES QUE APARECE ABAJO**
  ![messages.png](./assets/messages.png)
- Deben de utilizarse los siguientes componentes:
  - **NavBar** (que reutilizaremos en las 3 páginas)
    ![nav-bar.png](./assets/nav-bar.png)
  - En la página de "home" o dashboard:
    - **TopHeroes**
      ![top-heroes.png](./assets/top-heroes.png)
    - **SearchBar**
      ![search-bar.png](./assets/search-bar.png)
  - En la página "heroes" o list:
    - **NewHeroeForm**
      ![new-heroe-form.png](./assets/new-heroe-form.png)
    - **HeroesList**
      ![heroes-list.png](./assets/heroes-list.png)
    - **HeroBadge**
      ![hero-badge.png](./assets/hero-badge.png)
  - En la página details:
    - **HeroDetails**
      ![hero-details.png](./assets/hero-details.png)
    - **HeroNameForm**
      ![hero-name-form.png](./assets/hero-name-form.png)
    - **NavigationButtons**
      ![nav-buttons.png](./assets/nav-buttons.png)

1. Se utilizará BEM/SASS.
2. Se debe desplegar a Netlify.

## Milestones

1. Home y Heroes totalmente estáticos, es decir, los componentes no tienen "funcionalidad".
2. Details totalmente estática, sin funcionalidad, pero sólo debe de haber un archivo html, que de alguna manera sea capaz de "leer" qué heroes estás buscando para cargar sus detalles.
3. A partir de este milestone añadiremos funcionalidad. Es normal que la información que cambiemos con esta funcionalidad no se conserve entre las páginas. No te preocupes por eso, puesto que es el punto 8 del challenge.
4. Añadir funcionalidad de búsqueda
5. Añadir funcionalidad de añadir héroe
6. Añadir funcionalidad de borrar héroe
7. Añadir funcionalidad de editar héroe
8. ¿Se te ocurre alguna manera de hacer que la información se guarde entre páginas?
