INSTRUCCIONES DE EJECUCIÓN

Herramienta: Apache JMeter 5.x
Java Version: 17+

PASOS PARA REPRODUCIR:
1. Clonar este repositorio.
2. Abrir Apache JMeter.
3. Cargar el archivo del plan de pruebas: 'FakeStore_LoadTest.jmx'.
4. IMPORTANTE: Asegurarse de que el archivo 'data.csv' se encuentre en la misma carpeta que el script .jmx, o actualizar la ruta en el elemento "Configuración del CSV Data Set".
5. Ejecutar la prueba presionando el botón de "Iniciar" (Play).

ARCHIVOS INCLUIDOS:
- FakeStore_LoadTest.jmx: Script principal de JMeter.
- data.csv: Datos de prueba (usuarios y contraseñas).
- conclusiones.txt: Análisis de los resultados obtenidos.