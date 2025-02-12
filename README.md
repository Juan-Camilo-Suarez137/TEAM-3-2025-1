# TEAM-3-2025-1
Prueba en github 2.0
<<<<<<< HEAD
=======
¿Que es Arquitectura SOA? Javier

La  Arquitectura Orientada a Servicios (SOA) es un enfoque que permite la reutilización de componentes de software a través de interfaces de servicio. Estas interfaces utilizan estándares comunes y facilitan la integración en nuevas aplicaciones, evitando que los desarrolladores deban recrear funcionalidades existentes. Cada servicio ofrece una función de negocio completa y permite un acoplamiento dinámico, lo que reduce las dependencias entre aplicaciones.

Las interfaces de servicio son contratos entre el proveedor y el consumidor, y pueden implementarse en diversos lenguajes de programación. Se definen comúnmente con WSDL y se exponen mediante protocolos estándar como SOAP o RESTful HTTP. El gobierno del servicio gestiona el ciclo de vida del desarrollo y publica los servicios en un registro para su reutilización.

SOA representa un avance significativo en la integración de aplicaciones, facilitando la conexión entre sistemas sin la complejidad de integraciones punto a punto previas. Aunque SOA y la arquitectura de microservicios comparten términos similares, operan en contextos distintos.


>>>>>>> 94dda39f06e1caa44037e121a475178c2a29ef9a

Angela ¿Que es ESB?

Un ESB es un componente esencial de la SOA, o arquitectura orientada a servicios, una arquitectura de software que surgió a finales de la década de 1990. La SOA define una forma de hacer que los componentes de software sean reutilizables a través de interfaces de servicio. Estos servicios suelen utilizar interfaces estándar (es decir, servicios web) de tal manera que se pueden incorporar rápidamente en nuevas aplicaciones sin tener que duplicar la funcionalidad realizada por el servicio en nuevas aplicaciones.

Cada servicio de una SOA incorpora el código y los datos necesarios para ejecutar una función empresarial completa y discreta (p. ej. comprobar el crédito de un cliente, calcular el pago mensual de un préstamo o tramitar una solicitud de hipoteca). Las interfaces de servicio proporcionan acoplamiento dinámico, lo que significa que se pueden llamar con poco o ningún conocimiento de cómo se implementa el servicio por debajo, reduciendo las dependencias entre las aplicaciones.

Funcionalidades:
Integración: Facilita la integración de aplicaciones y servicios heterogéneos.
Orquestación: Permite la coordinación de múltiples servicios en un flujo de trabajo.
Transformación de Datos: Puede transformar datos entre diferentes formatos y protocolos.
Gestión de Mensajes: Maneja la entrega y enrutamiento de mensajes entre servicios.



# ventajas 
Guevara
    Las ventajas de la Arquitectura Orientada a Servicios (SOA) según IBM son:

1. **Mayor agilidad empresarial y una comercialización más rápida**: SOA permite a las organizaciones componer y reconfigurar aplicaciones rápidamente mediante servicios reutilizables. Esta capacidad de ensamblar servicios ya existentes para crear nuevas soluciones reduce el tiempo necesario para desarrollar nuevas aplicaciones, lo que acelera la comercialización de productos y servicios.

2. **Mejor uso de las inversiones en tecnología heredada**: Con SOA, las organizaciones pueden integrar aplicaciones y sistemas heredados con nuevas soluciones. Los servicios existentes pueden ser reutilizados, lo que extiende su vida útil y permite que los sistemas más antiguos sigan funcionando dentro de un marco moderno y flexible sin necesidad de una reestructuración total.

3. **Mejora de la colaboración entre negocio y TI**: Los servicios en SOA se definen en términos comerciales, lo que facilita la comunicación y colaboración entre los equipos de negocio y los de tecnología. Esto ayuda a garantizar que las aplicaciones se alineen mejor con los objetivos comerciales y permite una mejor adaptación a los cambios en las necesidades empresariales, mejorando la eficiencia organizacional.

4. **Escalabilidad y flexibilidad**: Al estar basado en servicios independientes y modulares, SOA facilita la escalabilidad de los sistemas a medida que crecen las necesidades del negocio. Los servicios pueden ser fácilmente modificados o ampliados sin afectar al sistema en su conjunto, proporcionando una gran flexibilidad para adaptarse a nuevos requisitos o cambios en el entorno empresarial.

5. **Optimización de los recursos y costos**: SOA permite una utilización más eficiente de los recursos informáticos, ya que los servicios pueden ser compartidos entre diversas aplicaciones. Esto reduce la duplicación de esfuerzos y costos asociados con el desarrollo de nuevas aplicaciones, y permite la reutilización de servicios existentes, lo que resulta en una mayor eficiencia operativa.


Steven **Ejemplos de SOA**
En 2010, las implementaciones de SOA estaban en plena expansión entre las empresas líderes en prácticamente todos los sectores. Por ejemplo:

Delaware Electric recurrió a SOA para integrar sistemas que antes no se comunicaban entre sí, lo que incrementó la eficiencia de desarrollo y ayudó a la organización a mantenerse solvente durante cinco años de congelamiento de las tarifas eléctricas impuesto por el estado.

Cisco adoptó SOA para asegurarse de que su experiencia en la realización de pedidos de productos fuera coherente en todos los productos y canales exponiendo los procesos de pedidos como servicios que las divisiones, las adquisiciones y los socios comerciales de Cisco pudieran incorporar a sus sitios web.

Independence Blue Cross (IBC), de Filadelfia, implementó una SOA para asegurarse de que los diferentes integrantes que se ocupan de los datos de los pacientes (los agentes del servicio al cliente de IBC, las consultas de los médicos y los usuarios del sitio web de IBC) estuvieran trabajando con el mismo origen de datos (una "única fuente de verdad").