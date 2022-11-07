# Prueba de Acceso a la empresa Rappi

Enunciado de la prueba de acceso a la empresa Rappi para Android.

## Descripción de la prueba

El primer paso del proceso de selección consiste en superar esta prueba, está diseñada para evaluar tu conocimiento y experiencia como desarrollador Android.

Por favor ten en cuenta lo siguiente:
- La API a consumir se encuentra aquí (por comodidad he buscado otra API más sencilla):
  - [Listado de Películas](https://movies-and-shows-api.cyclic.app/movies)
  - [Detalle de la Película](https://movies-and-shows-api.cyclic.app/movies?id=xxxx) (sustituir las xxxx por el id obtenido del listado)
- Consumir el API de películas y series de la siguiente pagina: https://developers.themoviedb.org/4/getting-started/authorization
- Cada película y/o series debe poder visualizar su detalle.
- Debe funcionar tanto online como offline (cache).
- Debe tener un buscador offline por título.

## Implementación a realizar:

1. Usar una arquitectura por capas donde queden definidas:
  - Capa de Presentación: Gestiona la visualización de los datos.
  - Capa de Dominio: Gestiona la lógica de la app.
  - Capa de Datos: Gestiona la información de la app.
2. En la capa de datos se implementaran la siguientes fuentes:
   - Xml (SharedPreferences)
   - Memory
   - Room
   - API (Retrofit)
   - Firebase RealTime
3. En la capa de presentación:
   - Activity
   - Fragment
   - ViewModel
   - Coroutines
   - LiveData
   - Widgets: ImageView, TextView, etc.

## Arquitectura 

Una vez acabada la prueba describa en un readme brevemente:

1. Las capas de la aplicación (por ejemplo capa de persistencia, vistas, red, negocio, etc) y qué clases pertenecen a cual.
2. La responsabilidad de cada clase creada.

## Programación base

Responda y escriba dentro del Readme con las siguientes preguntas:

1. En qué consiste el principio de responsabilidad única? Cuál es su propósito?
2. Qué características tiene, según su opinión, un “buen” código o código limpio

## Entregables

1. Link de github del código de la prueba
2. Dentro de repositorio de github el readme con las explicaciones y preguntas solicitadas.

## Deadline:
Tres días o 72 horas después de la confirmación de recibido del email.  
