# Analisis-de-control-en-twitter

La problemática presentada tiene que ver con un control de acceso a las publicaciones realizadas dentro de la red social Twitter, como quien tiene permiso de ver y reenviar dichos twitts.

Por otro lado también se requiere implementar un dashboard que presente un análisis respecto a los twitts, como puede ser el número de vistas y de reenvios, por ejemplo.

---

## Integrantes

- Carlos López Carreño - 20162021295
- Jairo Murcia - 20162020047
- Cristian Gutierrez - 20172020046

---

## Análisis
Si se quiere tener un control sobre el acceso a publicaciones de ciertas cuentas , quien tiene acceso a estas y los permisos sobre estas se pueden manejar a traves de una base de datos sql.Las cuentas y  sus twits podrian ser tablas con sus atributos correspondientes, despues tendriamos que tenerun atributo que diga si una cuenta es privada o publica, pero tambien en un futuro sería posible que otra forma de administrar la cuenta sea agregada, por lo que este atributo deberia ser una tabla por separado. Despues tendriamos que resolver el problema de que a veces un usuario no quiere que ciertos usuarios vean sus publicaciones , por lo que tendriamos otra tabla para esos usuarios bloqueados.Una primera version de diseño teniendo en cuenta solo el manejo de las visibilidad de menjo de publicaciones podria ser la siguiente

