# ***CAPÍTULO V: PRODUCT IMPLEMENTATION, VALIDATION & DEPLOYMENT***
--------
## 5.1. Software Configuration Management
En este apartado se describen las elecciones y reglas que permitirán al equipo asegurar la consistencia a lo largo de todo el proceso de desarrollo de nuestra solución.
### 5.1.1. Software Development Environment Configuration
En esta sección se ofrecen los vínculos a las aplicaciones y productos de software desarrollados durante el ciclo del proyecto utilizando los programas adecuados. 

Con este propósito, se estructurará en las siguientes categorías:

* Project Management
* Requirements Management
* Product UX/UI Design
* Software Development
* Software Testing
* Software Documentation

Además, se categorizarán los elementos de estas secciones como enlaces de referencia (para software basado en modelos Saas) o enlaces de descarga (para productos que se ejecuten en las computadoras de los miembros del equipo) para cada uno de los productos de software.

<body>
    <table>
        <tr>
            <th>PROJECT MANAGEMENT</th>
            <td>Este campo se basa en la gestión de proyectos y tiene como objetivo principal mejorar los procesos y su entorno con el fin de alcanzar los resultados deseados.</td>
        </tr>
        <tr>
            <td colspan="2">Durante el transcurso del proyecto digital, se realizará la implementación de un producto de software basado en el modelo SaaS, el cual operará a través de un navegador web. Sin embargo, no se creará una versión correspondiente de la aplicación móvil.</td>
        </tr>
    </table>
</body>

<body>
    <table>
        <tr>
            <th>REQUIREMENTS MANAGEMENT</th>
            <td>Este procedimiento se centra en garantizar que una empresa registre, compruebe y cumpla con los requisitos y deseos de sus clientes, así como de las partes interesadas internas o externas.</td>
        </tr>
        <tr>
            <td colspan="2"> <strong>Pivotal Tracker:</strong> Esta herramienta se define como una plataforma que simplifica la gestión de las historias de usuario al organizarlas en epopeyas y evaluar su importancia en el programa según su puntuación. Se seleccionó por su capacidad para permitir que cada integrante del equipo comparta una vista en tiempo real del progreso en cada proyecto, colaborando en distintas secciones o ajustando el flujo del proyecto.</td>
        </tr>
    </table>
</body>

|**Product UX/UI Design**|
|-|
|Este software facilita la creación digital de modelos que se integran en la experiencia del consumidor. En nuestro caso, estamos desarrollando un modelo de sitio web compatible tanto con computadoras como con dispositivos móviles.|

Para lograrlo, hemos empleado varias herramientas de diseño y colaboración, entre las que se incluyen:

**1. Uxpressia:** Uxpressia es una plataforma en línea especializada en mapeo de la trayectoria del cliente. Nos ayuda a crear mapas de impacto y perfiles de usuario, como User Personas, Empathy Maps y Journey Maps. Puedes obtener más información sobre Uxpressia en [este enlace](https://uxpressiacom/).                                                      
**2. MIRO:** MIRO es una pizarra digital colaborativa en línea que se adapta a diversas actividades colaborativas, como investigación, ideación, creación de lluvias de ideas y mapas mentales. Es una herramienta versátil que facilita el trabajo en equipo. Descubre más sobre MIRO en [su sitio web](https://miro.com/app/dashboard/).                                                        
**3. Figma:** Figma es una herramienta de prototipado web y un editor de gráficos vectoriales. A diferencia de otras herramientas, Figma se ejecuta en línea, lo que permite crear modelos que funcionan tanto en navegadores web como en navegadores móviles. Puedes explorar Figma en [este enlace](https://www.figma.com/design/).                                                    
**4. Lucid Chart:** Esta es una aplicación de diagramación en línea que permite a los usuarios colaborar y trabajar juntos en tiempo real para crear una variedad de diseños, incluidos diagramas UML, mapas mentales, prototipos de software y otros tipos de diagramas. Puedes conocer más acerca de Lucid Chart en [este enlace](https://lucid.app/lucidchart/).                                            
**5. Overflow:** Overflow es una herramienta de diagramación que ofrece la posibilidad de colaborar en tiempo real. Utilizamos esta herramienta para crear diagramas de Userflows. Si deseas obtener más información sobre Overflow, visita [su sitio web](https://userflow.com/app/).                                                

Estas herramientas nos ayudan a dar vida a nuestros diseños digitales y a asegurar que nuestros productos sean accesibles y atractivos en diversas plataformas.

- **Software Development:** El desarrollo de software es una estrategia empleada en la elaboración de productos de software. Esta técnica se emplea para establecer un método que dirige el desarrollo del software, y cada etapa describe un enfoque particular para las diversas actividades que tienen lugar durante el proceso.

A continuación, te mostramos algunas herramientas y tecnologías esenciales que emplearemos en el proyecto:

**1. GitHub:** GitHub es una plataforma de repositorio colaborativo utilizada para almacenar y gestionar el progreso de proyectos realizados por grupos de personas. Puedes acceder al repositorio del proyecto en [este enlace](https://github.com/OpenSource-Grupo4).                                                                  
**2. Webstorm:** Webstorm es un entorno de desarrollo de JetBrains, una compañía especializada en software, diseñado para el desarrollo web en JavaScript. Esta herramienta ofrece facilidades para probar sitios web en navegadores como Google Chrome. En nuestro proyecto, usaremos WebStorm para trabajar con lenguajes como HTML, CSS y JavaScript. Obtén más información sobre WebStorm [aquí](https://www.jetbrains.com/webstorm/).          
**3. HTML:** HTML es un lenguaje de marcado utilizado en el desarrollo de sitios web para crear hipertextos y enlazar a otros documentos. Proporciona herramientas para diseñar sitios web y se puede combinar eficazmente con CSS y JavaScript. En nuestro proyecto, utilizaremos HTML para implementar la estructura de la página web. Obtén más información sobre la edición de archivos HTML en WebStorm [aquí](https://www.jetbrains.com/help/idea/editing-html-files.html).                                                          
**4. CSS:** CSS es un lenguaje de estilo para la web que permite mejorar la interfaz de usuario añadiendo elementos como colores y tamaños, entre otros. También es posible crear un estilo en CSS y aplicarlo al sitio web creado en HTML. Este lenguaje será utilizado en la implementación del diseño de nuestra plataforma web. Puedes obtener más información sobre CSS [aquí](https://www.jetbrains.com/help/idea/style-sheets.html).             
**5. JavaScript:** JavaScript es un lenguaje de programación interpretado que funciona bajo el paradigma de programación orientada a objetos (POO), utilizando prototipos en lugar de clases para la implementación. Permite crear dinámicas para los usuarios a través de la lógica de programación y será utilizado en la creación de interacciones dinámicas en la plataforma web. Encuentra más detalles sobre JavaScript [aquí](https://www.jetbrains.com/help/idea/javascript-specific-guidelines.html).   

Estas herramientas y tecnologías serán esenciales para el desarrollo exitoso de nuestro producto de software.

- **Software Testing:** Esto implica examinar los componentes y el rendimiento del software bajo prueba a través de procesos de validación y verificación.
- **Lenguaje Gherkin:** Este tipo de lenguaje, denominado DSL (Lenguaje Específico de Dominio), se crea con el propósito específico de resolver problemas particulares. Además de ser convertible en código, permite incorporar historias de usuario del programa junto con sus componentes asociados, como Característica, Escenario, Ejemplo, Esquema de Escenario, Dado, Cuando, Entonces y Y.
- **Software Documentation:** Se trata de los textos escritos o ilustraciones que acompañan al software de computadora o se integran en su código fuente. Esta documentación tiene como objetivo explicar cómo funciona el software o cómo utilizarlo.

### 5.1.2. Source Code Management

### 5.1.3. Source Code Style Guide & Conventions

### 5.1.4. Software Deployment Configuration

## 5.2. Landing Page, Services & Applications Implementation

### 5.2.1. Sprint 1

#### 5.2.1.1. Sprint Planning 1

#### 5.2.1.2. Sprint Backlog 1

#### 5.2.1.3. Development Evidence for Sprint Review

#### 5.2.1.4. Testing Suite Evidence for Sprint Review

#### 5.2.1.5. Execution Evidence for Sprint Review

#### 5.2.1.6. Services Documentation Evidence for Sprint Review

#### 5.2.1.7. Software Deployment Evidence for Sprint Review

#### 5.2.1.8. Team Collaboration Insights during Sprint


--------------
### 5.2.2. Sprint 2

#### 5.2.2.1. Sprint Planning 2

#### 5.2.2.2. Sprint Backlog 2

#### 5.2.2.3. Development Evidence for Sprint Review

#### 5.2.2.4. Testing Suite Evidence for Sprint Review

#### 5.2.2.5. Execution Evidence for Sprint Review

#### 5.2.2.6. Services Documentation Evidence for Sprint Review

#### 5.2.2.7. Software Deployment Evidence for Sprint Review

#### 5.2.2.8. Team Collaboration Insights during Sprint

### 5.2.3. Sprint 3

#### 5.2.3.1. Sprint Planning 3

#### 5.2.3.2. Sprint Backlog 3

#### 5.2.3.3. Development Evidence for Sprint Review

#### 5.2.3.4. Testing Suite Evidence for Sprint Review

#### 5.2.3.5. Execution Evidence for Sprint Review

#### 5.2.3.6. Services Documentation Evidence for Sprint Review

#### 5.2.3.7. Software Deployment Evidence for Sprint Review

#### 5.2.3.8. Team Collaboration Insights during Sprint


### 5.2.4. Sprint 4

#### 5.2.4.1. Sprint Planning 4

#### 5.2.4.2. Sprint Backlog 4

#### 5.2.4.3. Development Evidence for Sprint Review

#### 5.2.4.4. Testing Suite Evidence for Sprint Review

#### 5.2.4.5. Execution Evidence for Sprint Review

#### 5.2.4.6. Services Documentation Evidence for Sprint Review

#### 5.2.4.7. Software Deployment Evidence for Sprint Review

#### 5.2.4.8. Team Collaboration Insights during Sprint

--------------


## 5.3. Validation Interviews

### 5.3.1. Diseño de Entrevistas

### 5.3.2. Registro de Entrevistas

### 5.3.3. Evaluaciones según heurísticas

## 5.4. Video About-the-Product
