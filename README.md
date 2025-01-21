# Conversor de Monedas

En este emocionante desafío de programación, te invitamos a construir tu propio **Conversor de Monedas**. Aprenderás a realizar solicitudes a una API de tasas de cambio, a manipular datos JSON y, finalmente, a filtrar y mostrar las monedas de interés. ¡Prepárate para una experiencia práctica y emocionante en el desarrollo Java!

---

## Pasos del Proyecto

### 1. Configuración del Ambiente Java
- Instala un **IDE** como IntelliJ IDEA, Eclipse o NetBeans.
- Asegúrate de tener **Java JDK 11+** instalado.
- Configura un proyecto Maven o Gradle (opcional) para gestionar dependencias.

### 2. Creación del Proyecto
- Inicia un nuevo proyecto en tu IDE.
- Crea una estructura básica con el paquete principal y clases necesarias.

### 3. Consumo de la API
- Utiliza una API pública como [ExchangeRate-API](https://www.exchangerate-api.com/) o [Open Exchange Rates](https://openexchangerates.org/).
- Configura una clase para realizar solicitudes HTTP usando bibliotecas como `HttpURLConnection`, `Apache HttpClient` o `OkHttp`.

### 4. Análisis de la Respuesta JSON
- Recibe los datos JSON devueltos por la API.
- Utiliza bibliotecas como `Gson` o `Jackson` para analizar los datos y convertirlos en objetos Java.

### 5. Filtro de Monedas
- Selecciona monedas de interés.
- Permite al usuario elegir qué monedas desea visualizar o convertir.

### 6. Exibición de Resultados a los Usuarios
- Presenta los datos de manera amigable.
- Implementa una interfaz de consola o gráfica para mostrar las tasas de cambio y realizar conversiones.

---

## Tecnologías Recomendadas
- **Java JDK**: Para el desarrollo principal.
- **Gson/Jackson**: Para analizar datos JSON.
- **OkHttp/HttpClient**: Para realizar solicitudes HTTP.
- **Maven/Gradle**: Para gestión de dependencias.

---

## Ejemplo de Uso
```bash
Ingrese la moneda de origen: USD
Ingrese la moneda de destino: EUR
Ingrese el monto a convertir: 100
Resultado: 100 USD equivale a 92 EUR.
```

---
