# Trabajo_1
## 1. Integrantes
- María Fernanda Solis Castro
- Lorena Salcedo Montiel
- Anny Sofia Meneses Ardila

**Descripción:** Proyecto para la gestión y control de vehiculos en el parqueadero LMA Parking Lott.
## 2. Vínculos Académicos y Descripción
- María Fernanda: Soy estudiante de Ingenieria Industrial, actualmente curso mi 5 semestre. Me destaco por mi capacidad para colaborar de manera efectiva, tanto en proyectos individuales como en grupos. Mi enfoque se basa en la comunicación abierta, el respeto por las ideas de los demás y la capacidad de escuchar activamente. Mis principales fortalezas y habilidades son: Comunicación efectiva, capacidad para adaptarme, trabajo en equipo, responsabilidad y compromiso. 
- Lorena: Soy estudiante de Ingeniería Industrial, me caracterizo por tener una excelente disposición para aprender y enfrentar nuevos retos. Poseo habilidades para trabajar de manera autónoma o en equipo y me distingo por una actitud orientada al crecimiento continuo y a la búsqueda de soluciones innovadoras.
- Anny:
  
![WhatsApp Image 2025-04-27 at 8 49 33 PM](https://github.com/user-attachments/assets/51e1028c-1a97-434a-b7ab-b6e774a02c1f)
## 3. Nombre del Proyecto y Detalles. 
El parqueadero "LMA Parking Lott" es un espacio que presta su servicio a vehículos del sector de la Universidad de Antioquia. Este solo permite el ingreso de automóviles, el ingreso de motos no es aceptado. El parqueadero "LMA Parking Lott" requiere de sus habilidades como un equipo de programación de la respetada y bien ponderada Universidad de Antioquia para crear un software de consola en Python para poder gestionar usuarios, generar cobros, facturas, reportes y algo más. 
El parqueadero "LMA Parking Lott" cuenta con tres personas que trabajan turnos de 6 horas para atender a los usuarios que ingresan a usar el servicio y no presentar interrupciones ni contratiempos en el horario de 6:00 a.m. a 12:00 p.m. en jornada continua. El programa debe registrar usuarios, ingresar y retirar vehículos y generar reportes administrativos. 
Para solucionar este problema los estudiantes en grupos de tres integrantes deberán crear un programa que se encargue gestionar el parqueadero "LMA Parking Lott", en donde mediante entregas programadas y detalladas se pueda alcanzar el propósito de desarrollo. El programa debe ser entregado en un repositorio de GitHub en donde el líder del equipo será el encargado de crear y gestionar el espacio de desarrollo. 

## *El parqueadero "LMA Parking Lott"*
El parqueadero tiene una disponibilidad de 64 espacios de parqueo disponibles, los cuales son de libre elección por parte de los usuarios. El parqueadero registra manualmente la llegada de los usuarios en un papel y entrega un recibo con un sello al usuario con la hora y minuto de llegada. Al llegar al parqueadero se recibe el papel con el sello y se calcula el valor a pagar por hora y fracción. El parqueadero al momento no genera factura ni algún documento que certifique el pago de este.

## 4. Licencia del Software
El software *LMA Parking Lott* ha sido registrado bajo la licencia **CC0 1.0 Universal (Creative Commons)**.  
Esto implica que los autores (Mafe, Lorena y Anny) han renunciado a todos sus derechos sobre el software, permitiendo que cualquier persona pueda usar, copiar, modificar y distribuir la obra sin restricciones, incluso para fines comerciales.  

Más información: [https://creativecommons.org/publicdomain/zero/1.0/](https://creativecommons.org/publicdomain/zero/1/)
<p xmlns:cc="http://creativecommons.org/ns#" >Esta obra está marcada con <a href="https://creativecommons.org/publicdomain/zero/1.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC0 1.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/zero.svg?ref=chooser-v1" alt=""></a></p>

## 5. Reporte de visión
LMA Parking Lott es una aplicación desarrollada con el fin de gestionar de manera eficiente los espacios de estacionamiento en el parqueadero, Este sistema permitira a los usuarios registrar, buscar y reservar espacios, como tambien llevar un control de entradas y salidas de vehículos, generación de reportes y exportación de datos en tiempo real.

**Objetivos:**
- Optimizar el uso de los espacios de estacionamiento.
- Reducir el tiempo de búsqueda de parqueadero para los usuarios.
- Facilitar la administración de entrada, salidad y reservas.

**Beneficios:**
- Ahorro de tiempo y disminución del tráfico en el parqueadero.
- Mejora de la experiencia del usuario al brindar información actualizada.
- Mejora la eficiencia administrativa del parqueadero.

## 6. Especificación de requisitos
**Requisitos Funcionales:**
- Registrar usuarios con validación de datos personales y placa.
- Permitir el ingreso y salida de vehículos registrados, generando recibos de entrada y salida.
- Calcular el cobro del parqueadero automáticamente.
- Acceso para administrador con generación de reportes.
- Exportación de datos a archivos.

**Requisitos No Funcionales:**
- Rendimiento: El sistema debe manejar hasta 64 vehículos sin afectar la experiencia del usuario, con tiempos de respuesta rápidos (menos de 3 segundos para acciones básicas y menos de 10 segundos para reportes).
- Seguridad: Los datos del administrador deben ser protegidos mediante cifrado de contraseñas y validación de credenciales antes de acceder a la administración. La confidencialidad de los datos personales debe ser garantizada.
- Usabilidad: La interfaz debe ser intuitiva, con menús claros y mensajes de error fáciles de entender, permitiendo entradas eficientes de texto y números.
- Fiabilidad: El sistema debe ser estable y operar sin interrupciones durante 6 horas continuas, manejando hasta 64 vehículos sin generar errores.
- Compatibilidad:El sistema debe ser compatible con plataformas Windows y Linux, sin requerir configuraciones adicionales, y funcionar en computadoras de escritorio y laptops.

## 7. Plan de proyecto
- Reunión Inicial: Definición de roles, normas de trabajo y expectativas.
- Creación del repositorio GitHub y documentación: Escribir README.md, documentar su uso incluyendo instrucciones de instalación, ejecución.
- Análisis de requerimientos: Asesoria con el profesor o monitor para definir detalles del sistema y aclarar dudas.
- Diseño de la estructura del software: Diseño de menús, la estructura general de clases, los métodos principales y la lógica del sistema, estableciendo una arquitectura clara y modular.
- Programación de registro de usuarios: Desarrollo de módulo implementando validaciones estrictas para nombres, documentos de identidad y placas de vehículos.
- Programación de ingreso/retiro de vehículos: Desarrollo de módulos de ingreso y retiro, cálculo de cobros.
- Programación del módulo de administrador:	Desarrollar funcionalidades para la generación de reportes administrativos, incluyendo estadísticas de vehículos, pagos realizados y tiempos de estancia promedio.
- Implementación de exportación a CSV: Exportar datos (usuarios, vehículos, reportes) facilitando el análisis externo de los datos.
- Implementación del log de eventos: Registrar actividades del sistema en archivo de log (fecha, hora, acción, tiempo).
- Pruebas del sistema: Validar todas las funcionalidades del sistema y corregir errores, flujo completo, reportes.

**Diagrama de Gantt**
![WhatsApp Image 2025-04-27 at 10 46 39 PM (1)](https://github.com/user-attachments/assets/ca53bee3-d5dc-43e7-bbf6-89f743c9794f)

**Presupuesto del proyecto**
Modalidad de Pago: El proyecto no será remunerado en dinero, se reconocerá como tiempo de práctica de formación profesional.
Datos generales:
-Número de estudiantes: 3
-Horas invertidas por cada estudiante: 50 horas.
-Total de horas grupo: 150 horas.
Salario mínimo 2025 (SMLV): $1.423.500
Horas estándar de práctica por mes: 240 horas
Valor hora de práctica: 1.423.500/240 = 5.931 precio hora.
Cálculo del presupuesto del proyecto: 150 horas × 5.931 ≈ 889.650.
-El valor equivalente del proyecto en tiempo de práctica es: 889.650 pesos.

**Nota:** En este proyecto no se recibirá un pago monetario, ya que su finalidad principal es académica y formativa. Sin embargo, se va a obtener experiencia práctica, fortalecerán sus habilidades profesionales y aplicarán los conocimientos adquiridos en su proceso de formación.

## 8.Plan de versionado




