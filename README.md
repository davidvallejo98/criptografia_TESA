# criptografia_TESA
Deber Final de Criptografía Segundo Semestre
# Web de Cifrados Clásicos

Aplicación web públicamente accesible que permite **cifrar y descifrar texto** utilizando algoritmos de **criptografía clásica**, desarrollada con fines académicos.

URL pública

**Aplicación desplegada en:**
`critptografia-david-vallejo.infinityfreeapp.com`
Algoritmos implementados

La aplicación incluye los siguientes métodos de cifrado y descifrado:

1. **Cifrado César**

   * Tipo: Sustitución monoalfabética
   * Parámetro: Desplazamiento numérico

2. **Cifrado Vigenère**

   * Tipo: Sustitución polialfabética
   * Parámetro: Palabra clave

3. **Cifrado Atbash**

   * Tipo: Sustitución simple (alfabeto invertido)
   * Parámetro: No requiere clave

4. **Cifrado por Transposición Columnar**

   * Tipo: Transposición
   * Parámetro: Número de columnas

## Tecnologías utilizadas

* **HTML5** – estructura de la aplicación
* **Bootstrap 5** – diseño responsivo e interfaz gráfica
* **JavaScript (Vanilla)** – lógica de cifrado y descifrado

## Manual de uso
1. Seleccione el **algoritmo de cifrado** desde el menú desplegable.
2. Ingrese el **texto** a cifrar o descifrar.
3. Ingrese la **clave o parámetro** correspondiente (si aplica).
4. Presione el botón:

   * **Cifrar** para obtener el texto cifrado.
   * **Descifrar** para recuperar el texto original.

## Ejecución local (XAMPP)

Para ejecutar la aplicación en su equipo local utilizando **XAMPP**:

1. Instale XAMPP desde el sitio oficial y asegúrese de que **Apache** esté en ejecución.

2. Copie la carpeta del proyecto dentro del directorio:

   ```
   C:\xampp\htdocs\
   ```
   (en Linux: `/opt/lampp/htdocs/`)

3. La estructura quedará, por ejemplo:

   ```
   htdocs/
     └── Criptografia/
         └── index.html
   ```

4. Abra su navegador web y acceda a:

   ```
   http://localhost/Criptografia
   ```
5. La aplicación estará lista para usarse localmente.


## Contexto académico

Este proyecto fue desarrollado como parte de una actividad académica para reforzar los conceptos de **criptografía clásica**, **seguridad de la información** y **desarrollo web básico**.
## Autor

**David Vallejo**

