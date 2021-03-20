<!-- Encabezados -->
# my title
## my title h1
### h3
#### my title h4
##### my title h5
###### my title h6

<!-- Texto en itálica -->
This is an *italic* text

<!-- Texto en negrita -->
this is an **strong** text

<!-- Texto tachado -->
this is a ~~strikethrough~~ text

<!-- Listas desordenadas -->
* apple
  * green apple
* orange
  * little pink orange
  * big orange
* peach
* etc...

<!-- Listas ordenadas -->
1. apple
2. orange
   1. little pink orange
   2. big orange
3. peach
4. etc....

<!-- Enlaces -->
[github.com](https://www.github.com)

[github.com](https://www.github.com "Enlace a Github")

<!-- Cita -->
> Esto es una cita 

<!-- Lineas horizontales -->
---
____
 
<!-- Introducimos una línea de código -->
`console.log('hello world')`

<!-- Para introducir bloques de código, especificando el lenguaje -->

```sql
DROP DATABASE IF EXISTS lamp_db;
CREATE DATABASE lamp_db CHARSET utf8mb4;
USE lamp_db;

CREATE TABLE users (
  id int(11) NOT NULL auto_increment,
  name varchar(100) NOT NULL,
  age int(3) NOT NULL,
  email varchar(100) NOT NULL,
  PRIMARY KEY (id)
) ENGINE=InnoDB DEFAULT CHARSET=utf8;
```
```php
<?php
namespace PHPMailer\PHPMailer;
class Exception extends \Exception
{
    public function errorMessage()
    {
        return '<strong>' . htmlspecialchars($this->getMessage()) . "</strong><br />\n";
    }
}
?>
```
```html

<html>
    <body>
    <script language="javascript">
    document.write("Resolución de pantalla: ");
    document.write(screen.width + "*" + screen.height);
    document.write("&lt;br&gt;");
    document.write("Area visible disponible: ");
    document.write(screen.availWidth + "*" + screen.availHeight);
    document.write("&lt;br&gt;");
    document.write("Resolución de color: ");
    document.write(screen.colorDepth);
    document.write(" bits&lt;br&gt;");
    </script>
    </body>
</html>
```

```r
set.seed(173)
edades <- rnorm(n = 1500, mean = 15, sd = .75)
```

<!-- Esto es una tabla -->

| Tablas      | Alineaciones            |   Cómo queda    |
|-------------|:-----------------------:|----------------:|
| col 3 está  | Alineada a la derecha   | €1600           |
| col 2 es    | Centrada                | €12             |
| col 1       | Alineada a la izquierda | €1600           |


![visual studio code logo](vstudiocode.png "VS Code Logo")

<!--GitHub Markdown-->

* [x] Tarea 1
* [ ] Tarea 2
* [ ] Tarea 3 
