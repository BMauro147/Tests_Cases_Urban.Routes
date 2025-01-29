# Tests_Cases_Urban.Routes
# Proyecto de Pruebas de Funcionalidad - Compartir un Automóvil

## Descripción del Proyecto

Este proyecto se centra en la prueba de la funcionalidad de la aplicación de reserva de automóviles compartidos. El objetivo es garantizar que la interfaz de usuario y las interacciones funcionen correctamente en dos navegadores web principales: **Google Chrome** y **Firefox**, en diferentes resoluciones de pantalla (800x600 para Chrome y 1920x1080 para Firefox).

El proyecto tiene como objetivo evaluar el flujo de reserva de un automóvil en línea, que incluye la selección de tarifa, la visualización de vehículos en el mapa y la interacción con diversas ventanas emergentes durante el proceso de reserva.

## Objetivos de las Pruebas

Durante las pruebas, se buscaron verificar los siguientes aspectos:

1. **Interacción con la interfaz de usuario**: Evaluar la correcta visualización y funcionalidad de los elementos del formulario de reserva, como la elección de la tarifa, la introducción de los datos de pago y la selección del automóvil en el mapa.
2. **Ventanas emergentes**: Asegurar que las ventanas emergentes aparecieran en los momentos adecuados, como la confirmación de la reserva, la cancelación del viaje y la actualización del estado de la reserva.
3. **Validación de campos**: Comprobar que los campos de entrada de datos (como la tarjeta bancaria y la licencia de conducir) solo permitieran los valores válidos y cumplían con las restricciones establecidas.
4. **Verificación de detalles del vehículo**: Validar que la información del automóvil, como la marca, descripción y tiempo de espera, fuera precisa y coincidiera con los requisitos de diseño.

## Tipo de Pruebas Realizadas

Se realizaron diferentes tipos de pruebas para evaluar distintos aspectos del sistema:

1. **Pruebas Funcionales**:
   - Estas pruebas se centraron en verificar si las funciones principales de la aplicación, como la selección de tarifas, la visualización de los vehículos en el mapa, y la interacción con las ventanas emergentes, funcionaban como se esperaba.
   - También se verificó la correcta integración de los campos obligatorios, como la licencia de conducir y el método de pago.

2. **Pruebas de Compatibilidad entre Navegadores**:
   - Se realizaron pruebas para asegurarse de que la aplicación funcionara correctamente en los navegadores **Google Chrome** y **Mozilla Firefox**, ambos en diferentes resoluciones de pantalla (800x600 y 1920x1080 respectivamente).
   - Se comprobaron aspectos como la visualización de la interfaz y la correcta interacción con los elementos de la página en estos entornos.

3. **Pruebas de Interfaz de Usuario (UI)**:
   - Estas pruebas se enfocaron en asegurarse de que la interfaz fuera intuitiva y los elementos de la página se visualizaran correctamente según los requisitos del diseño.
   - Se validaron los elementos visuales, como los iconos de los vehículos, la disposición de los formularios y la apariencia de las ventanas emergentes.

4. **Pruebas de Validación de Datos**:
   - En esta fase, se comprobaron las restricciones de los campos de entrada, como la tarjeta bancaria y la licencia de conducir.
   - Se evaluaron las validaciones para asegurarse de que solo se permitieran valores válidos en los campos correspondientes.

5. **Pruebas de Usabilidad**:
   - Se realizaron pruebas para asegurar que el flujo de trabajo fuera sencillo y fácil de seguir para el usuario final. Esto incluyó la prueba de la selección de tarifa, la elección de vehículo en el mapa, y la interacción con los botones de las ventanas emergentes.

## Resultados de las Pruebas

Durante la ejecución de las pruebas, los resultados fueron los siguientes:

- **Pruebas aprobadas**:
    - Funciones básicas como la selección de tarifas ("Casual", "Camping", "De lujo"), la correcta visualización del título "Urban.Routes" y la presencia de los botones de borrado en los campos de dirección fueron aprobadas sin problemas en ambos navegadores.
    - Las ventanas emergentes que notifican el estado del automóvil reservado, así como las relacionadas con la cancelación del viaje, también se comportaron correctamente en la mayoría de las pruebas.
    - Los iconos de los vehículos en el mapa y la funcionalidad para seleccionar un automóvil se probaron y funcionaron según lo esperado.
  
- **Problemas detectados**:
    - **Ortografía y descripción**: Hubo inconsistencias en la ortografía y en las descripciones que no coincidían completamente con los requisitos establecidos.
    - **Visualización de vehículos**: En algunos casos, los vehículos disponibles no se mostraron correctamente en el mapa o no se pudo seleccionar el automóvil deseado.
    - **Ventanas emergentes de cancelación**: No todas las ventanas emergentes relacionadas con la cancelación del viaje y la confirmación de la acción aparecieron en los momentos correctos.
    - **Restricciones de tarjetas bancarias**: En algunas pruebas, el sistema no detectó correctamente la falta de una tarjeta bancaria, lo que impidió la reserva en ciertos escenarios.

## Conclusión

Este proyecto ha permitido identificar diversas áreas de mejora en la funcionalidad de la aplicación de reserva de automóviles compartidos. A pesar de que la mayoría de las pruebas se aprobaron satisfactoriamente, se detectaron varios errores relacionados con la visualización de los vehículos, las ventanas emergentes y las restricciones de los campos de pago.

Es recomendable que se aborden estos problemas antes de lanzar la aplicación para asegurar una experiencia de usuario fluida y sin inconvenientes. Las correcciones específicas se encuentran documentadas en los informes detallados.


