# Bienvenido a mi Página Personal en GitHub

---

¡Hola! Soy Ingeniero en Deasarrollo de Software, mi nombre es _Juan Carlos Ruiz Gomez_, y esta es mi página personal en GitHub. Aquí puedes encontrar información sobre mí y mis proyectos.

**Correo:** [JuanCarlosRuizGomez2000@gmail.com](https://mail.google.com/). <img src="https://upload.wikimedia.org/wikipedia/commons/7/7e/Gmail_icon_%282020%29.svg" alt="Gmail" width="25" height="25">

**Telefono:** [477-589-65-03](https://web.whatsapp.com/). <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="Whatsapp" width="25" height="25">

**Domicilio:** [Calle Jardín de Bilbao 219A Jardines de San Juan II 37295 León Guanajuato](https://www.google.com/maps/place/Jdn.+de+Bilbao+219a,+37295+Le%C3%B3n+de+los+Aldama,+Gto./@21.0984953,-101.5771748,17.75z/data=!4m14!1m7!3m6!1s0x842bbd97f3a250f3:0xabc2ba9598e4f16!2sJARDINES+DE+SAN+JUAN!8m2!3d21.0986963!4d-101.5782661!16s%2Fg%2F11csrgthvr!3m5!1s0x842bbd9f3f346163:0xf5b4c421ca66c4c9!8m2!3d21.099158!4d-101.57489!16s%2Fg%2F11lgqgn9tb?entry=ttu). <img src="https://i.blogs.es/6caa48/pngegg-13-/450_1000.png" alt="Google Maps" width="30" height="30">

# Acerca de mí

Soy una persona muy diligente y comprometida, con una gran pasión por el trabajo. He demostrado mi capacidad para desempeñarme de manera eficiente incluso en situaciones de presión. Me apasionan los desafíos y encontrar soluciones que contribuyan a alcanzar los objetivos trazados por la empresa. Actualmente, busco una organización que me brinde la oportunidad de desarrollar y aplicar las habilidades que he adquirido como estudiante universitario en un ambiente laboral estimulante.

# Proyectos
* **Geolocalizador Avanzado (Node Js)**
  + Backend.
  + Parceo de direcciones.
  + Busquedas avanzadas dentro de la BD.
  + Persistente a fallos.
  + Creacion de la Base de Datos.
  + Arquitectra Cliente-Servidor.
* **SIA (Node Js)**
  + Backend.
  + Uso de CORS, tokens y tabla roles-permisos.
  + Envio de emails.
  + Funciones cronologicas mediante node-Schedule.
  + Creacion de la Base de Datos.
  + Arquitectra MVC.
  + Generacion de reportes (pdf y html).
* **Que plan hoy (Android Studio)**
  + Frontend y Backend.
  + Toma de coordenadas.
  + Consumo de servicios de terceros y propios.
  + Listado de restaurantes mas cercanos y con promociones para el dia de hoy.
  + Creacion de la Base de Datos.
  + Arquitectra MVC.
* **LuxuryRest (React)**
  + Frontend y Backend.
  + Pasarela de pago.
  + Consumo de servicios de terceros y propios.
  + Listado de productos y ERP al generar un articulo.
  + Creacion de la Base de Datos.
  + Arquitectra MVC.
* **LuxuryRest (. Net en C# y Python)**
  + Frontend y Backend.
  + Pasarela de pago.
  + Consumo de servicios de terceros y propios.
  + Listado de productos y ERP al generar un articulo.
  + Proceso ETL.
  + Dashboard de compras/ventas.
  + Creacion de la Base de Datos.
  + Arquitectra MVC.

# Educación
* **Colegio Escuela de Nivel Medio Superior de León (ENMSL San Miguel)**
  + Certificado de estudios, 2018.
  + Bachiller en Físico-Matemático, 2018.
* **Universidad Tecnológica de León (UTL)**
  + Promedio académico 9
  + Ing. Desarrollo de Software Multiplataforma, 2024

# Experiencia laboral
* **Programador Jr. (Backend)**
  + Manejo del computador.
  + Uso directo de servidores internos y de produccion.
  + Despliegues continuos.
  + Pruebas y soportes a sistemas.
  + Respaldos y restauraciones de Bases de Datos.
  + ItsMarts, Febrero 2024 - Hasta la fecha.
* **Asesor Telefónico**
  + Manejo del computador.
  + Estándar de Cobranza con el cliente directo.
  + Cuidado de la imagen de la compañía mediante un habla apropiado.
  + Muñoz, Abril 2021 - Oct 2021
* **Auxiliar de Calidad**
  + Impresión de precios y promociones.
  + Administración de artículos de la tienda.
  + Conteo de los productos en las bodegas.
  + Manejo del TC (Aparato de su Sistema Directo).
  + Bodega Aurrera, Marzo 2022 - Sep 2022
* **Asistente General**
  + Limpieza de las máquinas y/o lugar de trabajo.
  + Cobranza mediante su sistema y atención al cliente.
  + Preparación de las pizzas.
  + Little Caesars, Mayo 2019 - Mar 2020
* **Vendedor de Celulares Movistar**
  + Trato con el cliente.
  + Manejo del computador.
  + DM Comunicaciones, Enero 2016 - Julio 2017
  
# Lenguajes y Frameworks de programación
* Java
* JavaScript
* TypeScript
* Python
* Android Studio
* HTML5 y CSS
* MySQL
* Flutter
* Flask y Dash
* Java Spring
* . Net en C#
* Angular
* Node JS
* PostgreSQL
* SQL server
* Mongo
* SQLite
* Express
* React

## Cursos / Habilidades

> Certificacion de Excel Avanzado
>
> Conocimiento avanzado en Telecomunicaciones Cisco, 2022
>
> Cursos Udemy en Angular, Node Js y PostgtreSQL de cero a experto.

## Lenguajes

> Español Nativo - Nivel Oral y Escrito Avanzado.
>
> Inglés - Nivel Oral y Escrito Medio.

### Prueba de mis servicios

```javascript
const express = require('express'); 
const bodyParser = require('body-parser'); 
const { parseDireccion } = require('./src/controlador/funciones'); 
const scoringMaestro = require('./src/controlador/scoring'); 
// CARGA LAS VARIABLES DE ENTORNO DESDE EL ARCHIVO .env
require("dotenv").config(); 

// Creación de la aplicación Express
const app = express(); 
const port = process.env. PORT || 3000; 

// Middleware para analizar el cuerpo de las solicitudes en formato JSON
app.use(bodyParser.json()); 
app.use(express.urlencoded({ extended: true })); // x-www-form-urlencoded
// MIDDLEWARE PARA SERVIR ARCHIVOS ESTÁTICOS DESDE LA CARPETA 'public'
app.use(express.static("public")); 

// Endpoint para geolocalizar una dirección proporcionada por el usuario
app.post('/geolocalizar', async (req, res) => {

    try {
        // Obtener la dirección proporcionada por el usuario desde el cuerpo de la solicitud
        const { direccion = '', limit = 5 } = req.body;

        // Validar que venga la direccion con algun valor de busqueda.
        if(!direccion) return res.status(404).json({ ok: false, error: 'Falta capturar alguna direccion al  servicio. Intente nuevamente' });

        // Parsear la dirección según la Norma Técnica sobre Domicilios Geográficos
        const direccionParsed = parseDireccion(direccion);
        console.log(direccionParsed);

        // Funcion que enrutara acorde al parseo recibido
        const results = await scoringMaestro(direccionParsed);
        // Ordenar scoring mas alto primero
        let sortedResults = results.sort((a, b) => b.scoring.fiability - a.scoring.fiability);
        // Recortar a solo 10 resultados
        sortedResults = sortedResults.slice(0, limit);
        // Devolver las coordenadas encontradas
        if (results.length > 0) {
            return res.status(200).json({ ok: true, results: sortedResults });
        } else {
            return res.status(404).json({ ok: false, error: 'Sin resultados.' });
        }
    } catch (error) {
        // Manejar cualquier error que pueda ocurrir durante el proceso de geolocalización
        console.error('Error al geolocalizar dirección:', error);
        return res.status(500).json({ ok: false, error: 'Contacte al Administrador.' });
    }

}); 

// Iniciar el servidor
app.listen(port, () => {

    console.log( `Servidor Express escuchando en el puerto ${port}` );

}); 
