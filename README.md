Repositorio: 
https://github.com/laylascheli/curso-agentes-inteligentes.git

Descripción del proyecto:
Este agente consulta el clima de una ciudad ingresada por el usuario utilizando datos simulados. Se generó con un pequeño script en Python que emplea un diccionario de ciudades y sus condiciones climáticas, evitando la necesidad de usar APIs o tokens.

Lógica del agente (explicación sin código):

** El usuario escribe el nombre de una ciudad.

** El agente guarda ese valor en una variable.

** Luego, busca la ciudad en un diccionario interno con datos simulados de clima.

** Según la respuesta, muestra la temperatura y la descripción del clima, o indica que no hay información si la ciudad no está en el diccionario.

Conceptos de programación aplicados:

** Variable: guarda el nombre de la ciudad ingresada por el usuario.

** Entrada/Salida: el usuario escribe una ciudad, y el agente devuelve la información correspondiente.

** Condicionales: se usan para verificar si la ciudad existe en el diccionario y dar la respuesta adecuada.

** Función: agrupa las acciones del agente (pedir la ciudad, consultar el diccionario y responder).

Ejemplo de interacción:
🧑‍💻 Usuario: ¿Cuál es el clima en Buenos Aires?
🤖 Agente: Actualmente hay 22°C y cielo despejado en Buenos Aires.