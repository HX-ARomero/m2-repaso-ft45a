# Módulo 2 | REPASO
  
## Cohorte FT45a - 23/11/2023
  
### Idea general del proyecto
  
<img src="./src/assets/m2-repaso.png" width="600px">
  
### Temas que repasaremos:
- React
  - Componentes funcionales
  - Estados y props
  - React-Router-DOM
  - Formularios
- Redux
- Hooks
  
### Componentes a desarrollar:
- Dentro de la carpeta "components" ya se encuentra la estructura básica de cada componente.
- Landing: Vista de Bienvenida.
  - Permitirá ingresar el nombre y email del usuario y guardarlo en un estado global.
- NavBar: Mostrará el nombre del usuario y los link de navegación.
  - No debe renderizarse en el Landing.
- Home: Cargará los episodios en un estado local.
  - Para ello utilizaremos el endpoint de la [API Rick&Morty](https://rickandmortyapi.com/api/episode).
- Card: Renderizará la información de cada uno de los episodios.
  - Permitirá que un episodio sea cargado a un estado global de Redux "Favoritos".
  - A los datos de cada episodio agregaremos las propiedades:
    - "completed": que tendrá un valor de false al inicio
    - "rating": que tendrá un valor inicial de 3
- Favorites: Muestra los episodios cargados en el estado global de "Favoritos".
  - Permite modificar la propiedad "completed" a true.
  - Permite modificar el "rating" entre 1 y 5.
- Detail: Muestra más información sobre el episodio favorito seleccionado.