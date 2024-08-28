# Contador de Calorías

Este proyecto es una aplicación web para contar calorías, construida utilizando React, Vue.js, y Tailwind CSS. El objetivo principal de este proyecto fue aprender a utilizar el hook `useReducer` en React para gestionar el estado de la aplicación de manera más eficiente y optimizar su rendimiento.

Puedes ver la aplicación en acción [aquí](https://react-contador-calorias.netlify.app).

## Tabla de Contenidos

- [Descripción del Proyecto](#descripción-del-proyecto)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Instalación](#instalación)
- [Funcionalidades](#funcionalidades)
- [Uso de useReducer](#uso-de-usereducer)
- [Créditos](#créditos)
- [Conclusión](#conclusión)

## Descripción del Proyecto

La aplicación de contador de calorías permite a los usuarios ingresar alimentos o ejercicios junto con su nivel de calorías mediante un formulario. Estos elementos se listan en la aplicación, donde el usuario puede editarlos o eliminarlos. Además, la aplicación calcula y muestra las calorías consumidas, las calorías quemadas, y la diferencia numérica entre ambas, permitiendo a los usuarios llevar un control sobre su alimentación.

## Tecnologías Utilizadas

- **React**: Una biblioteca de JavaScript para construir interfaces de usuario.
- **Vue.js**: Un framework progresivo para construir interfaces de usuario.
- **Tailwind CSS**: Un framework CSS de utilidades para desarrollo rápido de interfaces.

## Instalación

Para ejecutar este proyecto localmente, sigue estos pasos:

1. Clona el repositorio:
    ```bash
    git clone https://github.com/tuusuario/contador-calorias.git
    ```
2. Navega al directorio del proyecto:
    ```bash
    cd contador-calorias
    ```
3. Instala las dependencias:
    ```bash
    npm install
    ```
4. Inicia el servidor de desarrollo:
    ```bash
    npm run dev
    ```

## Funcionalidades

- **Ingresar Alimentos o Ejercicios**: Permite agregar alimentos o ejercicios junto con sus niveles de calorías.
- **Editar o Eliminar Elementos**: Los usuarios pueden editar o eliminar cualquier elemento de la lista.
- **Calorías Totales**: Calcula y muestra las calorías consumidas, las calorías quemadas, y la diferencia entre ambas.

## Uso de useReducer

Para este proyecto, utilicé el hook `useReducer` de React con el fin de gestionar el estado de la aplicación de manera más estructurada y eficiente. `useReducer` es especialmente útil en situaciones donde el estado de la aplicación es complejo o donde múltiples subcomponentes necesitan actualizar partes del estado de manera consistente.

### ¿Qué Aprendí?

- **Manejo Eficiente del Estado**: `useReducer` me permitió centralizar la lógica de actualización del estado, facilitando la lectura y mantenimiento del código.
- **Optimización del Rendimiento**: Al utilizar `useReducer`, pude evitar renders innecesarios, optimizando así el rendimiento de la aplicación.
- **Patrones de Diseño**: Comprendí mejor los patrones de diseño para la gestión del estado en aplicaciones React, lo que me preparó para proyectos más grandes y complejos.

## Créditos

Este proyecto fue realizado como parte del curso de React y TypeScript de [codigoconjuan](https://codigoconjuan.com). Agradezco profundamente la enseñanza y los recursos proporcionados durante el curso, que me permitieron adquirir las habilidades necesarias para desarrollar esta aplicación.

## Conclusión

Este proyecto fue una excelente oportunidad para profundizar en el uso de `useReducer` en React. A través de la implementación de esta aplicación de contador de calorías, logré optimizar la gestión del estado, mejorar la estructura de mi código, y adquirir conocimientos valiosos sobre patrones de diseño en React. Esta experiencia me ha preparado mejor para enfrentar desafíos más avanzados en el desarrollo de aplicaciones web.
