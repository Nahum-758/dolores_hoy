# dolores_hoy

🔴 ROJO: escribe la prueba (debe FALLAR)

<img width="919" height="555" alt="image" src="https://github.com/user-attachments/assets/b1c4fb5a-1883-4604-adf3-f6a9dfd4d2a5" />
 <img width="919" height="150" alt="image" src="https://github.com/user-attachments/assets/cce91264-0bf1-4437-a184-f41077ce9999" />
 

Paso 2.3 ·  🟢 VERDE: implementar el guardia

$ flutter test test/cliente_seguro_test.dart
<img width="806" height="131" alt="image" src="https://github.com/user-attachments/assets/7f0cdd22-3a55-4360-981c-244e1fc24d0d" />

 
Ciclo 3.1 · 🔴 ROJO: las pruebas

 <img width="845" height="253" alt="image" src="https://github.com/user-attachments/assets/c4cd0eeb-bbc0-4dfb-8de0-66f93b53f902" />
<img width="845" height="140" alt="image" src="https://github.com/user-attachments/assets/aacef345-f837-4f46-b4a2-eb6688772dc3" />
 

Ciclo 3.2 · 🟢 VERDE: el modelo

<img width="697" height="164" alt="image" src="https://github.com/user-attachments/assets/c4fd9ad5-b3bf-4ecb-bcb9-c76a67912e26" />
 

Ciclo 3.3 · 🟢 VERDE: el servicio

<img width="670" height="113" alt="image" src="https://github.com/user-attachments/assets/68ed1b96-87c5-4df1-aa35-1d1e1a79f82d" />
 

Ronda 4 · API 2: Tipo de cambio (Frankfurter)

<img width="799" height="270" alt="image" src="https://github.com/user-attachments/assets/b7d80d55-b209-453e-8133-d0015919d476" />
<img width="799" height="111" alt="image" src="https://github.com/user-attachments/assets/a4092915-9493-40c9-9af0-a9272d0a512c" />

  
Ciclo 4.2 · 🟢 VERDE

<img width="697" height="131" alt="image" src="https://github.com/user-attachments/assets/cd5f4bae-3799-4520-ab70-8c44daa97977" />
 
<img width="697" height="131" alt="image" src="https://github.com/user-attachments/assets/74fdb63a-99e0-4f50-b40a-caace26b8301" />


Ronda 5 · API 3: Días festivos (Nager.Date)
Ciclo 5.1 · 🔴 ROJO

<img width="681" height="248" alt="image" src="https://github.com/user-attachments/assets/f778a40c-fd4a-4d0c-8be7-60905eedd263" />
<img width="679" height="138" alt="image" src="https://github.com/user-attachments/assets/c24e4139-18a7-4f94-a9c0-d84e393b28ae" />


Ciclo 5.2 · 🟢 VERDE

<img width="673" height="113" alt="image" src="https://github.com/user-attachments/assets/f98256bd-1b2a-453b-8e3f-f55d2abf73d5" />


Ronda 6 · API 4: Wikipedia y la entrada del usuario
Ciclo 6.1 · 🔴 ROJO

  <img width="734" height="294" alt="image" src="https://github.com/user-attachments/assets/4873b8b9-4449-4b79-9dbe-f8ca7e6f50a3" />
<img width="736" height="120" alt="image" src="https://github.com/user-attachments/assets/d70cb211-a22b-4d19-864f-d91da8fcec71" />

   
Ciclo 6.2 · 🟢 VERDE

 <img width="677" height="123" alt="image" src="https://github.com/user-attachments/assets/ba66562a-1044-4ab5-b86e-b159b3924f0f" />


Ronda 7 · API 5: NASA y el manejo seguro de claves
7.1 · ¿Dónde se filtran las claves?
•	En el código fuente: String clave = "abc123"; y luego el código va a GitHub.
•	En el repositorio: un archivo .env o secrets subido por accidente.
•	Dentro de la app instalada: cualquiera puede descomprimir un .apk (es un .zip) y leer los textos.
•	En los logs: print(url) cuando la URL lleva la clave.
•	En los mensajes de error que se muestran en pantalla o se mandan a servicios de reportes.
•	En capturas de pantalla y chats: "mira, no me funciona" con la clave visible.

7.3 · 🔴 Ciclo ROJO: pruebas de seguridad

<img width="733" height="243" alt="image" src="https://github.com/user-attachments/assets/1e9b3a76-d588-419b-bc0e-2ec0247acfae" />
<img width="733" height="104" alt="image" src="https://github.com/user-attachments/assets/614db8db-9861-4810-b8d5-fbaacb32778e" />

 
7.4 · 🟢 VERDE: las claves entran al compilar

<img width="675" height="117" alt="image" src="https://github.com/user-attachments/assets/0d513656-1f75-4a24-b370-1870dc3776a8" />


7.5 · Ciclo 🔴 ROJO y 🟢 VERDE del servicio NASA

 <img width="759" height="301" alt="image" src="https://github.com/user-attachments/assets/3ef963a2-0d25-449e-b945-c762fd8525ed" />
<img width="814" height="170" alt="image" src="https://github.com/user-attachments/assets/68e24392-a805-4c45-a0ea-a74f7a53ee4e" />


<img width="845" height="164" alt="image" src="https://github.com/user-attachments/assets/ffe3ae86-dcfa-489c-8b7f-8f1925d61ea6" />


Ronda 8 · El tablero: 5 APIs, cero dependencias entre ellas

Ciclo 8.1 · 🔴 ROJO

<img width="769" height="272" alt="image" src="https://github.com/user-attachments/assets/666595d4-d7d7-4de8-8e4b-a2b4a678b14b" />
<img width="769" height="99" alt="image" src="https://github.com/user-attachments/assets/e3f47456-9229-46e8-9d13-4a102adb8d3b" />


Ciclo 8.2 · 🟢 VERDE
$ flutter test}
 <img width="419" height="127" alt="image" src="https://github.com/user-attachments/assets/ad46291f-f9c1-4585-a9fd-e74b4e518f1f" />


Ronda 9 · La pantalla y la prueba final
Paso 9.3 · Prueba de fuego
21.	Ejecuta: flutter run --dart-define-from-file=secrets.json
 <img width="838" height="384" alt="image" src="https://github.com/user-attachments/assets/0533429e-017b-459d-817e-4e70705d4beb" />

22.	Deberías ver las 5 tarjetas llenarse casi al mismo tiempo.
 <img width="494" height="387" alt="image" src="https://github.com/user-attachments/assets/de08f9ed-3f80-483d-98b1-5b6d5c7c6e04" />


Cierre · Lo que lograste
Checklist de seguridad (revisa antes de entregar)
•	Ninguna clave está escrita en el código ni en el repositorio (git status limpio, secrets.json ignorado).
•	Todas las peticiones usan https y el cliente rechaza http.
•	Toda petición tiene timeout y límite de tamaño de respuesta.
•	Las direcciones se construyen con Uri.https / pathSegments, no con texto pegado.
•	Toda entrada del usuario se valida (vacío, longitud, caracteres de control).
•	Toda salida del servidor se valida (tipos, media_type, URLs https).
•	Los logs usan redactar(); ConfigClaves no imprime la clave completa.
•	Los errores inesperados muestran un mensaje genérico al usuario.
•	Una API caída no afecta a las demás.
•	La clave tiene el menor privilegio posible y se puede revocar.
Preguntas para discutir en clase
27.	¿Por qué --dart-define no es suficiente protección para una clave que cuesta dinero? ¿Qué harías en su lugar? Porque --dart-define incrusta el valor directamente en el binario compilado de la aplicación. Implementaría un servidor backend o proxy intermediario
28.	Un compañero sube su secrets.json a GitHub. ¿Qué pasos sigue, en orden, para reparar el problema? Primero sería revocar la clave, ir inmediatamente al portal del proveedor y revocar/invalidar la clave comprometida para detener cualquier uso malicioso, luego borrar el archivo del repositorio y limpiar el historial de commits con git filter-repo y después un git push –force; después sería asegurar el .gitignore verificando que el secrets.json esté correctamente añadido al archivo .gitignore para evitar que se suba y finalmente sería generar una nueva clave y configurarla localmente en el archivo secrets.json.
29.	¿Qué ventaja tiene que TODAS las APIs pasen por una sola clase (ClienteSeguro)? Que permite aplicar políticas de seguridad transversales en toda la aplicación como obligar estrictamente el uso de HTTPS, configurar timeouts globales, limitar el tamaño máximo de las respuestas para evitar ataques de denegación de servicio, y redactar automáticamente información sensible en los registros o logs sin duplicar código en cada servicio.
30.	¿Por qué validamos la respuesta del servidor si "la NASA es confiable"? Porque ningún sistema externo es 100% infalible. Los servidores pueden comprometerse, sufrir modificaciones inesperadas en sus esquemas de datos, o la red puede verse afectada por ataques de intermediario (Man-in-the-Middle). Validar la respuesta garantiza que la aplicación no falle y evitando excepciones no controladas o comportamientos erróneos en la interfaz ante datos corruptos o inesperados.
31.	Si la API de Wikipedia cambia el nombre del campo "extract", ¿qué ve el usuario? Ningún sistema externo es 100% infalible. Los servidores pueden comprometerse, sufrir modificaciones inesperadas en sus esquemas de datos, o la red puede verse afectada por ataques de intermediario (Man-in-the-Middle). Validar la respuesta garantiza que la aplicación no falle de forma abrupta (evitando excepciones no controladas o comportamientos erróneos en la interfaz) ante datos corruptos o inesperados.
¿Y qué prueba te avisaría primero? Las pruebas unitarias de los servicios/modelos (test/servicios_test.dart), específicamente la prueba que simula la respuesta de Wikipedia con el JSON esperado, ya que fallaría al intentar parsear el campo modificado.
Retos finales por equipos
•	Caché de 1 hora: guarda la última respuesta de cada API en memoria y úsala si la petición falla (modo sin conexión).
•	Reintento con backoff exponencial para errores 429 y de red (1 s, 2 s, 4 s) con pruebas primero.
•	Servidor proxy: reutiliza la API local en Node de la práctica anterior para que la clave de la NASA viva en el servidor y la app ya no la contenga.
•	Guarda el último tema buscado con flutter_secure_storage y escribe la prueba con un doble.
•	Agrega una sexta API gratuita de tu elección (por ejemplo, PokeAPI o Open Library) aplicando TODO el checklist.
🏅 INSIGNIA DESBLOQUEADA: Desarrollador de apps conectadas y seguras
Recuerda: la seguridad no es un archivo que se agrega al final; es un hábito en cada línea. ¡Éxito en tu tablero!
