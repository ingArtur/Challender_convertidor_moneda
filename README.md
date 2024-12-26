# Desafío de Conversor de Monedas

## Descripción

Este proyecto utiliza la API [ExchangeRate API](https://www.exchangerate-api.com/) para desarrollar una aplicación que proporcione la tasa de cambio actual para una cantidad específica en la moneda solicitada. Las opciones de conversión están visibles para el usuario.

## Estructura del Proyecto

El espacio de trabajo contiene las siguientes carpetas principales:

- `src`: Carpeta donde se encuentran los archivos fuente del proyecto.
- `lib`: Carpeta donde se almacenan las dependencias necesarias.

Los archivos de salida compilados se generarán de forma predeterminada en la carpeta `out`.

Si deseas personalizar la estructura de carpetas, puedes editar las configuraciones del proyecto en **`File` > `Settings` > `Project: [nombre del proyecto]` > `Project Structure`**.

## Requisitos

Este proyecto requiere las siguientes bibliotecas:

- [Gson](https://repo1.maven.org/maven2/com/google/code/gson/gson/2.11.0/gson-2.11.0.jar)
- [Dotenv-java](https://repo1.maven.org/maven2/io/github/cdimascio/dotenv-java/3.1.0/dotenv-java-3.1.0.jar)

Descarga estas bibliotecas y colócalas en la carpeta `lib` de tu proyecto.

## Configuración y Ejecución

Sigue estos pasos para configurar y ejecutar el proyecto en **IntelliJ IDEA**:

1. Clona este repositorio.
2. Abre el proyecto con **IntelliJ IDEA**.
3. Edita el archivo `.env.template`:
    - Agrega tu clave API obtenida desde [ExchangeRate API](https://www.exchangerate-api.com/).
    - Renombra el archivo a `.env`.
4. Abre el archivo `App.java` y ejecútalo. Puedes ejecutar el archivo haciendo clic derecho sobre el archivo y seleccionando **Run 'App'** o usando el atajo de teclado `Shift + F10`.

## Gestión de Dependencias

En **IntelliJ IDEA**, puedes gestionar las dependencias de tu proyecto a través de la interfaz de **Maven** o **Gradle**, si decides agregar un archivo de configuración para estas herramientas. Para más detalles, consulta la [documentación oficial de IntelliJ IDEA](https://www.jetbrains.com/idea/documentation/).
