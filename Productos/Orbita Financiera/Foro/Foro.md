
## Estructura

### Motivos
El foro se divide en motivos, que son decisiones de diseño adoptadas en la plataforma. Por ejemplo:
- Como saldrías de la crisis ?
- Es necesaria la inflación ?

### Categorías
Luego, las divisiones de segundo orden se definen por las categorías. Por ejemplo:
- Macroeconomía
- Finanzas
- Contabilidad
- Economía internacional

#### Definición
##### Categorías

| Campo | Tipo   |
| ----- | ------ |
| id    | string |
| name  | string |
### Hilos
Los elementos principales son los posts y los hilos. Los hilos son un único post y todas sus intervenciones relacionadas.

#### Definición
##### Posts

| Campo    | Tipo         |
| -------- | ------------ |
| id       | string       |
| title    | string       |
| content  | string       |
| category | `Categorias` |
| author   | `Usuarios`   |
|          |              |
