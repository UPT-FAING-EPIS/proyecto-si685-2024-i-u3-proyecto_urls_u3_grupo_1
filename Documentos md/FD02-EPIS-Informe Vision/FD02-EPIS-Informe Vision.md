Logo de Mi Empresa		Logo de mi Cliente

![C:\Users\EPIS\Documents\upt.png](Aspose.Words.6c833a1d-34d6-49a4-95de-0e359edc278f.001.png)

**UNIVERSIDAD PRIVADA DE TACNA**

**FACULTAD DE INGENIERIA**

**Escuela Profesional de Ingeniería de Sistemas**


` `**Casa de Cambio en Línea**

Curso: Diseño y Arquitectura de Software


Docente: Ing. Patrick José Cuadros Quiroga


Integrantes:

***Chambi Cori, Jerson Roni	(2021072619)***

***Flores Quispe, Jaime Elias	(2021070309)***

***Leyva Sardon, Elvis Ronald     (2021072614)***

***Luna Peña Edinson Oscar 	(2020066320)***




**Tacna – Perú**

**2024**

|CONTROL DE VERSIONES||||||
| :-: | :- | :- | :- | :- | :- |
|Versión|Hecha por|Revisada por|Aprobada por|Fecha|Motivo|
|1\.0|MPV|ELV|ARV|18/04/2024|Versión Inicial|
|2\.0||||24/042024|Version Intermedio |
|3\.0||||30/04/24|Versión Final|












**Sistema *Casa de Cambio en Línea***

**Documento de Visión**

**Versión *1.0***



|CONTROL DE VERSIONES||||||
| :-: | :- | :- | :- | :- | :- |
|Versión|Hecha por|Revisada por|Aprobada por|Fecha|Motivo|
|1\.0|MPV|ELV|ARV|10/10/2020|Versión Original|

**ÍNDICE GENERAL**



<a name="_gjdgxs"></a>1.	Introducción	1

1.1	Propósito	1

1.2	Alcance	1

1.3	Definiciones, Siglas y Abreviaturas	1

1.4	Referencias	1

1.5	Visión General	1

\2.	Posicionamiento	1

2.1	Oportunidad de negocio	1

2.2	Definición del problema	2

\3.	Descripción de los interesados y usuarios	3

3.1	Resumen de los interesados	3

3.2	Resumen de los usuarios	3

3.3	Entorno de usuario	4

3.4	Perfiles de los interesados	4

3.5	Perfiles de los Usuarios	4

3.6	Necesidades de los interesados y usuarios	6

\4.	Vista General del Producto	7

4.1	Perspectiva del producto	7

4.2	Resumen de capacidades	8

4.3	Suposiciones y dependencias	8

4.4	Costos y precios	9

4.5	Licenciamiento e instalación	9

\5.	Características del producto	9

\6.	Restricciones	10

\7.	Rangos de calidad	10

\8.	Precedencia y Prioridad	10

\9.	Otros requerimientos del producto	10

`	`b) Estándares legales	14

`	`c) Estándares de comunicación	15

`	`d) Estándares de cumplimiento de la plataforma	15

`	`e) Estándares de calidad y seguridad	15

[CONCLUSIONES	](#_3znysh7)16

[RECOMENDACIONES	](#_2et92p0)16

[BIBLIOGRAFÍA](#_tyjcwt)[	](#_tyjcwt)17

[WEBGRAFÍA](#_3dy6vkm)[	](#_3dy6vkm)17

















1. Introducción

   Desde la antigüedad los seres humanos hemos requerido o visto por conveniente que el ahorro como un método de ver nuestra capital o dinero a futuro es así que nos remontándonos a la historia llegamos a ver que el trueque era el método de cambio efectivo entre un bien y servicio tal es así que no se veía o se tenía sentido o mejor dicho no se daba valor a bien por dinero (monedas) posterior a ello aparicio el dinero (billete, cheque y tasas de cambio)  por lo que dio paso al dinero digital y a toda transacción virtual significando que en  el mundo globalizado de hoy las transacciones financieras atraviesan fronteras sin restricciones, y la necesidad de intercambiar monedas extranjeras de manera eficiente y segura se ha vuelto indispensable. En este contexto, las casas de cambio en línea emergen como actores clave, ofreciendo plataformas digitales que facilitan el intercambio de divisas de forma rápida, conveniente y transparente.

   Una Casa de Cambio en Línea es una entidad financiera que opera en el mundo virtual, permitiendo a los usuarios intercambiar una moneda por otra a través de una plataforma en línea. Estas casas de cambio ofrecen una variedad de servicios, desde la compra y venta de divisas hasta la gestión de transacciones internacionales. Además, proporcionan información actualizada sobre las tasas de cambio y garantizan la seguridad de las transacciones mediante el uso de tecnologías como la autenticación mediante un token. Según Polatova, Z., Bukenov, G. y Bukenova, I. (2022). Una casa de cambio de divisas en línea es un programa que automatiza el cambio de divisas y la conversión de dinero, lo que ayuda a limitar las posibles pérdidas causadas por las fluctuaciones monetarias.

   Para garantizar el funcionamiento óptimo de una Casa de Cambio en Línea en el entorno altamente dinámico y competitivo de las finanzas digitales, es imperativo desarrollar un sistema informático robusto y escalable que se ajuste a los estándares de seguridad más rigurosos y garantice una experiencia de usuario fluida y satisfactoria.

   En este contexto, la aplicación de patrones de diseño se convierte en un componente esencial del proceso de desarrollo de software. Los patrones de diseño, siendo soluciones probadas para problemas recurrentes en el diseño de software, permiten abordar de manera sistemática y eficiente los desafíos inherentes a la implementación de una Casa de Cambio en Línea. Al adoptar estos patrones, los desarrolladores pueden crear estructuras de software flexibles y modulares que facilitan la incorporación de nuevas funcionalidades, la adaptación a cambios en los requisitos del negocio y la corrección de errores de manera más eficaz.

   Por lo que con la legislación vigente se tendrá en cuenta los montos que son regularizados por ley significando que según el tipo de persona natural y jurídica se establecen ciertas cantidades las cuales se rigen a la legislación peruana y a la Superintendencia de Banco (SBS) y seguros del País.


1. Propósito

Explorar y demostrar cómo los patrones de diseño Singleton, Factory Method y Builder pueden ser aplicados de manera efectiva en el desarrollo de una Casa de Cambio en Línea para mejorar su estructura, funcionamiento, eficiencia para ser eficaz en su utilización optimizando las transacciones para el usuario.

1. Alcance

El alcance del proyecto abarca la aplicación de los patrones de diseño Singleton, Factory Method y Builder respectivamente en el contexto de una Casa de Cambio en Línea. Se concentrará en analizar cómo estos patrones pueden ser implementados para mejorar la estructura, funcionamiento y eficiencia del sistema de Casa de Cambio en Línea, con el objetivo de proporcionar una experiencia de usuario más fluida y segura.

Es así que el mencionado informe no solo describe teóricamente cada uno de los patrones de diseño, sino que también proporcionará ejemplos prácticos de implementación dentro del contexto de una Casa de Cambio en Línea y de una operación digital. 

1. Definiciones, Siglas y Abreviaturas

- Patrón de Diseño: Es una solución general y reutilizable para un problema común en el diseño de software. Proporciona una descripción estructurada de cómo resolver un problema particular, que ha sido probada y utilizada con éxito en diferentes contextos

- Singleton: Garantizar que una clase tenga una única instancia y proporcionar un punto de acceso global a esa instancia. Esto es útil cuando solo se necesita una única instancia de una clase en toda la aplicación, como por ejemplo, para manejar la conexión a una base de datos o para gestionar la configuración global

- Factory Method:  Es una interfaz para crear un objeto, pero permite a las subclases decidir qué clase instanciar. Esto proporciona una manera de delegar la creación de objetos a las subclases, lo que hace que el código sea más flexible y fácil de mantener. Por ejemplo, en un videojuego, una clase "EnemyFactory" podría tener un método para crear diferentes tipos de enemigos, como "createGoblin" o "createDragon", y las subclases de "EnemyFactory" podrían implementar estos métodos para crear instancias específicas de enemigos.


- Builder: se utiliza para construir un objeto complejo paso a paso. Permite la creación de diferentes representaciones de un objeto utilizando el mismo proceso de construcción. Esto es útil cuando un objeto tiene muchas partes y se quiere simplificar su creación proporcionando un constructor paso a paso. Por ejemplo, en la creación de un objeto "Meal" que incluye varios componentes como entrante, plato principal y postre, el patrón Builder puede utilizarse para construir diferentes tipos de comidas (por ejemplo, "HamburgerMealBuilder" o "VegetarianMealBuilder") utilizando el mismo proceso de construcción.


1. Visión General

En ese sentido exploramos cómo los patrones de diseño  Singleton, Factory Method y Builder pueden mejorar una Casa de Cambio en Línea. Por ende  analizaremos cómo estos patrones simplifican la estructura del sistema, para así mejorar la interacción del usuario y optimización del  acceso a los datos. También veremos ejemplos prácticos de su implementación y discutiremos sus beneficios en la eficiencia y funcionalidad del sistema.

Es así que los patrones de diseños antes mencionados proporcionan soluciones prácticas y efectivas a problemas comunes realizados en el diseño de Software ayudando a mejorar la modularidad con  la reutilización del código y la mantenibilidad de las aplicaciones.

1. Posicionamiento

   1. Oportunidad de negocio

Expansión en el Mercado de Divisas Digitales:

- Con la llegada o venida de la Pandemia (COVID 19)  es donde el usuario en aras de salvaguardar su integridad así como de su familia vio por conveniente.

- La tendencia hacia la digitalización en el sector financiero presenta una oportunidad para la Casa de Cambio en Línea para ofrecer una plataforma segura, conveniente y eficiente para el intercambio de divisas digitales.

- Aprovechando esta oportunidad de negocio, la Casa de Cambio en Línea puede expandir su base de clientes, aumentar sus ingresos y fortalecer su posición competitiva en el mercado de divisas digitales.

1. Definición del problema

La definición del problema radica en los desafíos que enfrenta en su estructura y funcionamiento. Estos incluyen la complejidad del sistema, dificultades en la interfaz de usuario, acceso ineficiente a los datos y limitaciones en la escalabilidad. La complejidad del sistema dificulta su comprensión y mantenimiento, mientras que una interfaz de usuario complicada puede confundir a los usuarios. Abordar estos problemas es crucial para mejorar la eficiencia operativa, la experiencia del usuario y la capacidad de adaptación del proyecto.

1. Descripción de los interesados y usuarios
   1. Resumen de los interesados
- Clientes: Su principal interés radica en la seguridad, conveniencia y eficiencia del servicio.
- Inversores: Buscan obtener retornos sobre su inversión a través de su rentabilidad.
- Reguladores: Su interés radica en garantizar el cumplimiento de las leyes y regulaciones financieras.
- Equipo Interno: Su interés está en el éxito del proyecto y la sostenibilidad a largo plazo.

  1. Resumen de los usuarios

- Seguridad y Confianza: Los usuarios buscan una plataforma segura y confiable.
- Conveniencia y Facilidad de Uso: Esperan una experiencia de usuario intuitiva y fácil de usar.
- Variedad de Divisas y Tasas Competitivas: Desean acceso a una amplia gama de divisas digitales y tasas de cambio competitivas.
- Transparencia y Claridad: Valorarán la transparencia en los procesos de transacción.
- Soporte al Cliente Eficiente: Esperan un servicio de atención al cliente receptivo y eficiente.

  1. Entorno de usuario

El entorno del usuario está marcado por la digitalización de las transacciones financieras y la creciente adopción de divisas digitales. Los usuarios interactúan con la plataforma desde diversos dispositivos, como computadoras de escritorio, portátiles, tabletas y teléfonos inteligentes, lo que les brinda flexibilidad y conveniencia para acceder al servicio en cualquier momento y lugar.

Además, el entorno del usuario está influenciado por la competitividad del mercado y las tendencias en las tasas de cambio de divisas digitales. Los usuarios están atentos a las fluctuaciones en los precios y las tasas de cambio, buscando obtener el mejor valor para sus transacciones en un mercado dinámico y en constante cambio.

1. Perfiles de los interesados
- Cliente Individual: Este perfil representa a los usuarios finales que utilizan la plataforma. Buscan un servicio seguro, conveniente y eficiente, así como tasas de cambio competitivas y una amplia variedad de divisas disponibles.
- Inversionista: Los inversionistas son aquellos que han invertido capital en la Casa de Cambio en Línea y tienen un interés financiero en su éxito. Están interesados en obtener retornos sobre su inversión y en el crecimiento y la rentabilidad a largo plazo de la empresa.
- Regulador: Los reguladores son entidades gubernamentales o autoridades regulatorias responsables de supervisar y regular las operaciones de la Casa de Cambio en Línea. Su objetivo es garantizar el cumplimiento de las leyes y regulaciones financieras, así como proteger los intereses y la seguridad de los clientes.
- Equipo de Desarrollo y Tecnología: Este perfil incluye a los responsables de diseñar, desarrollar y mantener la plataforma en línea de la Casa de Cambio. Su objetivo es garantizar que la plataforma sea segura, confiable y fácil de usar para los usuarios.
- Equipo de Atención al Cliente: Este equipo está compuesto por representantes de servicio al cliente y soporte técnico que están disponibles para ayudar a los usuarios con consultas, problemas técnicos o cualquier otra necesidad que puedan tener durante el uso de la plataforma. Su objetivo es brindar una experiencia de usuario satisfactoria y resolver cualquier problema de manera eficiente.



1. Perfiles de los Usuarios
- <a name="_30j0zll"></a>Inversionista Ocasional: Este usuario realiza inversiones en divisas digitales de forma esporádica, generalmente para diversificar su cartera o aprovechar oportunidades de mercado.
- Comerciante Activo: Este usuario se dedica a la compra y venta frecuente de divisas digitales como parte de su actividad comercial o de inversión.
- Inversionista a Largo Plazo: Este usuario tiene un enfoque de inversión a largo plazo y utiliza la Casa de Cambio en Línea para comprar y mantener activos digitales durante períodos prolongados.
- Viajero Frecuente: Este usuario utiliza la Casa de Cambio en Línea para cambiar divisas digitales antes o durante sus viajes internacionales.
- Usuario Principiante: Este usuario tiene poca o ninguna experiencia en divisas digitales y utiliza la Casa de Cambio en Línea para aprender y familiarizarse con el mercado.

  1. Necesidades de los interesados y usuarios

•	Inversionista Ocasional: Busca una plataforma fácil de usar y segura donde pueda realizar transacciones rápidas y obtener información actualizada sobre los precios y tendencias del mercado.

•	Comerciante Activo: Requiere una plataforma con herramientas avanzadas de análisis técnico y gráficos para tomar decisiones informadas. Valora la ejecución rápida de órdenes y tasas de cambio competitivas.

•	Inversionista a Largo Plazo: Prioriza la seguridad y la estabilidad de la plataforma, así como la disponibilidad de una amplia variedad de divisas digitales para diversificar su cartera.

•	Viajero Frecuente: Necesita una plataforma fácil de usar con tasas de cambio competitivas y la capacidad de realizar transacciones rápidas y seguras desde cualquier lugar.

•	Usuario Principiante: Busca una plataforma intuitiva con recursos educativos y soporte al cliente accesible para obtener orientación en sus primeras operaciones.

1. Vista General del Producto
   1. Perspectiva del producto

      Con la creciente digitalización de las transacciones financieras y la necesidad de una gestión eficiente de activos digitales, surge una demanda cada vez mayor de herramientas que simplifiquen el intercambio y la gestión de diferentes tipos de monedas digitales. Nuestra Casa de Cambio en Línea se posiciona como una solución integral que aborda estas necesidades específicas, ofreciendo una plataforma fácil de usar y eficiente que permite a los usuarios gestionar sus activos digitales de manera efectiva.


1. Resumen de capacidades

   El sistema ofrece una interfaz intuitiva y amigable que facilita la compra, venta e intercambio de una amplia variedad de monedas digitales, lo que lo convierte en una opción atractiva tanto para empresas como para usuarios individuales que buscan optimizar su experiencia en el mercado de divisas digitales. Al simplificar el proceso de intercambio y proporcionar herramientas avanzadas de análisis y seguimiento de tendencias del mercado, nuestro sistema ayuda a mejorar la productividad y la eficiencia en la gestión de activos digitales, brindando a los usuarios un mayor control sobre sus inversiones y transacciones financieras.

1. Suposiciones y dependencias

   Suponemos que la adopción continua de divisas digitales y la digitalización de las transacciones financieras seguirán creciendo en el futuro cercano. Esta suposición se basa en la tendencia actual hacia la digitalización en diversos sectores y la creciente aceptación de las criptomonedas y otras formas de dinero digital como parte del panorama financiero global.

   Dependencias:

   Tecnología de Seguridad: La efectividad y confiabilidad de nuestro sistema dependen en gran medida de la continua evolución de la tecnología de seguridad cibernética para proteger los fondos y la información de los usuarios contra amenazas y ataques en línea.

   Regulaciones y Cumplimiento: Nuestra capacidad para operar y expandirnos está sujeta al cumplimiento de las leyes y regulaciones financieras en todas las jurisdicciones en las que operamos. Esto incluye el cumplimiento de los requisitos KYC (Conozca a su Cliente) y AML (Anti Lavado de Dinero).

   Infraestructura Tecnológica: Depende de una infraestructura tecnológica robusta y escalable para garantizar la disponibilidad y el rendimiento óptimo de la plataforma, incluso en momentos de alta demanda y volatilidad del mercado.

   Adopción del Mercado: Nuestra viabilidad a largo plazo depende de la adopción continua de nuestra plataforma por parte de los usuarios y la comunidad de inversionistas, así como de nuestra capacidad para mantener y expandir nuestra base de clientes.

   Competencia en el Mercado: Estamos sujetos a la competencia en un mercado en constante evolución, lo que significa que debemos mantenernos ágiles y continuamente innovadores para diferenciarnos y mantener nuestra posición en el mercado.

   Confianza del Usuario: La confianza y la reputación son fundamentales para nuestro éxito. Depende de nuestra capacidad para proporcionar una experiencia segura, confiable y transparente que fomente la confianza y la lealtad de nuestros usuarios.

1. Costos y precios

   Costos:

   Desarrollo y Mantenimiento de la Plataforma: Incluye los costos asociados con el diseño, desarrollo y mantenimiento continuo de la plataforma en línea, así como la implementación de actualizaciones de seguridad y características adicionales.

   Infraestructura Tecnológica: Costos relacionados con la infraestructura de servidores, almacenamiento en la nube, ancho de banda y otros recursos tecnológicos necesarios para mantener la plataforma en funcionamiento de manera eficiente y confiable.

   Seguridad y Cumplimiento: Inversión en medidas de seguridad cibernética, cumplimiento normativo y protección de datos para garantizar la seguridad y la privacidad de los fondos y la información de los usuarios.

   Soporte al Cliente: Costos asociados con la contratación y capacitación de personal para proporcionar soporte al cliente receptivo y eficiente a través de diversos canales de comunicación, como chat en vivo, correo electrónico y teléfono.

   Marketing y Adquisición de Clientes: Gastos destinados a estrategias de marketing digital, publicidad en línea, relaciones públicas y promociones para aumentar la visibilidad de la plataforma y adquirir nuevos clientes.

   Precios:

   Comisiones por Transacción: La plataforma puede cobrar una comisión por cada transacción realizada por los usuarios, que puede ser un porcentaje del monto de la transacción o una tarifa fija por operación.

   Tarifas de Cambio: Se pueden aplicar tarifas de cambio para convertir una moneda digital en otra, que pueden variar según el tipo de moneda y las condiciones del mercado en ese momento.

   Tarifas de Depósito y Retiro: Pueden existir tarifas asociadas con el depósito y retiro de fondos en la plataforma, que pueden variar según el método de pago utilizado y la moneda involucrada.

   Tarifas Premium: La plataforma puede ofrecer servicios premium o características adicionales a cambio de una tarifa mensual o anual, que proporcionan beneficios exclusivos a los usuarios.

1. Licenciamiento e instalación

   En lugar de licenciar software para instalación local, la Casa de Cambio en Línea ofrecería acceso a su plataforma a través de un modelo de suscripción. Los usuarios pueden registrarse en la plataforma y crear una cuenta gratuita o elegir entre diferentes planes de suscripción que ofrecen diferentes niveles de funcionalidad y características adicionales.

   El licenciamiento en este contexto implicaría que los usuarios acepten los términos y condiciones de uso de la plataforma al registrarse, lo que establecería los derechos y responsabilidades de ambas partes en relación con el uso de los servicios proporcionados.

1. Características del producto

Interfaz Intuitiva y Amigable: Una interfaz de usuario fácil de usar que permite a los usuarios realizar transacciones de manera rápida y sencilla, independientemente de su nivel de experiencia en divisas digitales.

Seguridad Avanzada: Implementación de tecnologías de seguridad de última generación, como cifrado de extremo a extremo y autenticación de múltiples factores, para proteger los fondos y datos de los usuarios contra amenazas cibernéticas.

Amplia Variedad de Divisas Digitales: Ofrece acceso a una amplia gama de criptomonedas y otras divisas digitales populares, permitiendo a los usuarios diversificar sus carteras y realizar intercambios entre diferentes activos digitales.

Transparencia y Claridad: Proporciona información detallada sobre precios, tarifas y políticas de transacción para garantizar una experiencia de usuario transparente y sin sorpresas desagradables.

1. Restricciones

Límites de Transacción: El sistema puede tener restricciones en el monto máximo o mínimo de las transacciones que los usuarios pueden realizar en un período de tiempo determinado. Esto ayuda a controlar el flujo de fondos y minimizar el riesgo de fraude o actividad sospechosa.

Horarios de Operación: Pueden establecerse restricciones en los horarios de operación del sistema, limitando los períodos en los que los usuarios pueden realizar transacciones. Esto puede ser necesario para permitir el mantenimiento del sistema o para cumplir con los requisitos regulatorios en diferentes regiones.

Compatibilidad de Dispositivos: El sistema puede tener restricciones en cuanto a los dispositivos o navegadores compatibles que los usuarios pueden utilizar para acceder a la plataforma. Esto se hace para garantizar una experiencia de usuario consistente y segura en todos los dispositivos.

Requisitos de Autenticación: Se pueden establecer restricciones en los métodos de autenticación que los usuarios deben seguir para acceder al sistema. Esto puede incluir la verificación de identidad de dos factores o el uso de hardware de seguridad para proteger las cuentas de usuario.

Políticas de Privacidad y Seguridad: El sistema puede imponer restricciones estrictas sobre cómo se manejan y protegen los datos de los usuarios, incluidas las políticas de privacidad y seguridad que deben cumplir los usuarios al utilizar la plataforma.

Requisitos de Edad: El sistema puede requerir que los usuarios cumplan con un requisito mínimo de edad para registrarse y utilizar la plataforma. Esta restricción ayuda a garantizar que los usuarios tengan la capacidad legal para participar en transacciones financieras y cumplir con las regulaciones pertinentes. Por ejemplo, el sistema puede establecer que los usuarios deben tener al menos 18 años de edad para registrarse y utilizar los servicios ofrecidos. Esta restricción ayuda a garantizar la legalidad y la responsabilidad de las transacciones realizadas en la plataforma.

1. Rangos de calidad

Seguridad: "Nuestra plataforma se enorgullece de ofrecer un nivel de seguridad excepcional. Implementamos medidas avanzadas, como cifrado de extremo a extremo y autenticación de dos factores, para garantizar la máxima protección de los fondos y la privacidad de nuestros usuarios. Además, llevamos a cabo auditorías de seguridad regulares para garantizar el cumplimiento de las mejores prácticas de la industria."

Experiencia del Usuario: "La experiencia del usuario es una prioridad para nosotros. Nuestra interfaz de usuario intuitiva y fácil de usar garantiza una navegación suave y sin complicaciones para todos nuestros usuarios, independientemente de su nivel de experiencia en el mercado de divisas digitales. Además, ofrecemos características adicionales, como herramientas de análisis avanzadas y recursos educativos, que agregan valor y mejoran aún más la experiencia del usuario."

Fiabilidad del Sistema: "Nos esforzamos por proporcionar un sistema altamente confiable y disponible en todo momento. Con tiempos de inactividad mínimos y mantenimiento planificado que no afecta la operatividad del servicio, nuestros usuarios pueden confiar en que podrán acceder y realizar transacciones de manera consistente y sin interrupciones. La fiabilidad es un pilar fundamental de nuestro compromiso con la excelencia en el servicio que ofrecemos."

1. Preferencia y Prioridad

En el sistema de Casa de Cambio en Línea, la priorización de operaciones se refiere al orden en que se ejecutan las transacciones y procesos financieros dentro del sistema. Esto es fundamental para garantizar la coherencia y la precisión en las operaciones realizadas. La priorización operativa se establece de la siguiente manera:

Realización de Transacciones: La ejecución de transacciones financieras tiene la máxima prioridad operativa, ya que constituye la función principal del sistema. Se realiza de manera inmediata y eficiente para satisfacer las necesidades de los usuarios.

Gestión de Cuentas de Usuario: La gestión de cuentas de usuario e inicio de sesión, tiene una prioridad operativa menor en comparación con las transacciones financieras. Se realiza de manera oportuna para garantizar la seguridad y la precisión de los datos de los usuarios.

Esta priorización operativa asegura un funcionamiento eficiente del sistema de Casa de Cambio en Línea, priorizando las operaciones críticas para brindar una experiencia fluida y segura a los usuarios durante sus transacciones financieras en línea.



1. Otros requerimientos del producto

   1. Estándares legales

      Para el sistema de Casa de Cambio en Línea, es imperativo asegurar el cumplimiento total de las leyes y regulaciones relacionadas con la protección de datos, privacidad y propiedad intelectual en todas las jurisdicciones donde opere el sistema. Esto implica adherirse estrictamente a normativas como el GDPR y cualquier otra legislación de protección de datos aplicable. Garantizar la confidencialidad y seguridad de la información del usuario es una prioridad fundamental, así como proteger los derechos de propiedad intelectual y cumplir con los estándares legales establecidos para mantener la integridad y la confianza en el servicio de casa de cambio en línea.


   1. Estándares de comunicación


      Para el sistema de Casa de Cambio en Línea, es esencial cumplir con los estándares de comunicación establecidos para asegurar una óptima interoperabilidad con otros sistemas y servicios financieros. Esto implica adherirse a protocolos.  La capacidad de intercambiar datos de manera eficiente y segura con otros sistemas es crucial para ofrecer una experiencia fluida y confiable a los usuarios, así como para garantizar el correcto funcionamiento de las transacciones monetarias en línea.


   1. Estándares de cumplimiento de la plataforma

      Para el sistema de Casa de Cambio en Línea, es fundamental cumplir con los estándares de la plataforma en la que se despliega, ya sea en entornos web, móviles o de escritorio. Esto implica seguir rigurosamente las directrices y recomendaciones de diseño específicas de cada plataforma, así como garantizar la plena compatibilidad con las versiones más recientes de los sistemas operativos y navegadores utilizados por los usuarios. Adaptarse a estos estándares asegura una experiencia de usuario consistente y optimizada, además de brindar confiabilidad y estabilidad al sistema de casa de cambio en línea en todas las plataformas disponibles.


1. Estándares de calidad y seguridad

   Para el sistema de Casa de Cambio en Línea, es esencial cumplir con estándares reconocidos de calidad y seguridad en la industria del software. Esto implica seguir buenas prácticas de desarrollo de software, como el uso de metodologías ágiles y la aplicación de principios de diseño robusto y modular. Además, se deben realizar pruebas exhaustivas de calidad y seguridad para identificar y corregir posibles fallos y vulnerabilidades antes de la puesta en producción. Asimismo, se debe asegurar la confidencialidad de la información del usuario en todo momento mediante el uso de técnicas de cifrado y acceso seguro a la base de datos. Cumplir con estos estándares garantiza un sistema de casa de cambio en línea robusto, seguro y confiable para los usuarios.




























1. Conclusiones

En conclusión, el sistema de Casa de Cambio en Línea se beneficia enormemente al cumplir con estándares de calidad y seguridad reconocidos en la industria del software. Al seguir buenas prácticas de desarrollo, realizar pruebas exhaustivas de calidad y seguridad, e implementar medidas de protección contra amenazas cibernéticas, se garantiza la integridad y confidencialidad de los datos del usuario en todo momento. Esto no solo fortalece la confianza de los usuarios en el sistema, sino que también asegura una experiencia segura y satisfactoria en el proceso de cambio de divisas en línea.

En conclusión, al aplicar los patrones de diseño Singleton, Factory Method y Builder en el desarrollo de una Casa de Cambio en Línea, se logra mejorar la organización, la flexibilidad y la eficiencia del sistema. Esto se traduce en una experiencia más fluida y efectiva para los usuarios durante sus transacciones en línea, lo que contribuye a optimizar su utilización y satisfacción.



1. Recomendaciones

En el desarrollo del proyecto de Casa de Cambio en Línea, es crucial priorizar la seguridad y la privacidad de los datos de los usuarios. Implementar medidas de seguridad sólidas, como el cifrado de datos y la autenticación de dos factores, garantizará la protección de la información confidencial contra posibles amenazas cibernéticas. Además, es fundamental cumplir con las regulaciones de protección de datos, como el GDPR, para asegurar la privacidad de los usuarios y evitar cualquier riesgo legal asociado con el manejo inadecuado de la información personal.

La usabilidad y la experiencia del usuario juegan un papel fundamental en el éxito del sistema de Casa de Cambio en Línea. Diseñar una interfaz de usuario intuitiva y fácil de usar permitirá a los usuarios realizar transacciones de manera rápida y sin complicaciones. Realizar pruebas de usabilidad periódicas con usuarios reales ayudará a identificar áreas de mejora y a optimizar continuamente la experiencia del usuario, lo que aumentará la satisfacción y la fidelidad del cliente.

















1. Bibliografía

Polatova, Z., Bukenov, G. y Bukenova, I. (2022). DESARROLLO DE UNA APLICACIÓN DE INFORMACIÓN DE UNA OFICINA DE CAMBIO EN LÍNEA DE CRIPTOMONEDAS. Periódico KazATK . <https://doi.org/10.52167/1609-1817-2022-123-4-183-190> .



1. Webgrafía

<https://kambista.com/economia/que-es-una-casa-de-cambio/> 
<https://www.rextie.com/blog/como-funciona-una-casa-de-cambio-online/> 

<https://elperuano.pe/noticia/134166-el-e-commerce-y-las-casas-de-cambio-online#google_vignette> 

<https://ebitdaec.com/seguridad-en-plataformas-virtuales/> 

<https://www.geotab.com/es/blog/15-recomendaciones-seguridad-para-plataforma-telematica/> 




2

