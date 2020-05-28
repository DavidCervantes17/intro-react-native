## Intro a React Native

### Bootstrapping del proyecto:
#### Pre-requisitos
Es necesario tener instaladas las ultimas versiones LTS de **Node**, **npm** y **yarn**

#### Clone
```git clone https://github.com/MaxiSuppes/intro-react-native.git```

#### Instalar expo-cli globalmente
```npm install -g expo-cli```

#### Instalar dependencias
Ejecutar el comando ```yarn install``` en el root del proyecto

#### Variables de entorno
Crear un archivo ```.env``` en el directorio root y copiarle el contenido del archivo ```.env.example```.

*REACT_APP_API_URL*: Estamos usando la API gratuita https://reqres.in/api
*REACT_APP_USING_FAKE_API*: True si se quieren usar los mocks o vacío si se quiere usar la API antes mencionada.  

#### Run
```expo start```


### Contenido:
Cada una de las ramas contiene un ejemplo introductorio de algunas de las nociones principales de React.

```basic-version``` Contenido básico de una app creada con create-react-app

```navigation``` Ejemplo de navegación básica

```environment-variables``` Configuración de variables de entorno

```api-client``` Se usa un módulo para encapsular la comunicacion entre el cliente y la api. Los request se hacen a 
una [API pública]( https://reqres.in) usando [fetch API](https://developer.mozilla.org/es/docs/Web/API/Fetch_API/Utilizando_Fetch)

```master``` Tiene el contenido total de todas las ramas anteriores 

### Que falta?
No se agregó ningún test!

### Otros links de utilidad

[React Native documentation](https://reactnative.dev/)

[Tests con Jest](https://jestjs.io/)

[Airbnb React conventions](https://github.com/airbnb/javascript/tree/master/react)