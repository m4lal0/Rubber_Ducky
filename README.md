# Rubber Ducky
Es un hardware creado por Hak5, el cual, simula ser un pendrive normal, pero en realidad es una herramienta que inyecta pulsaciones de teclas (es un teclado camuflado). En este repositorio mantendre Scripts para la Rubber Ducky que pueden ser utiles para diferentes actividades.

### Ducky Script

El Rubber Ducky trabaja con un lenguaje de programación llamado Ducky Script, en el cual, cada comando es una instrucción de teclas a presionar.

La sintaxis de este lenguaje es el siguiente:

| SINTAXIS  | DESCRIPCIÓN  |
| ------------ | ------------ |
| `REM` | Comentarios, código que no será procesado |
| `DEFAULT_DELAY` / `DEFAULTDELAY` | Se debe definir un valor entre 0 y 10000 (milisegundos), el cual establecerá un delay a todas las secuencias de comandos |
| `DELAY` | Define un valor entre 0 y 10000 (milisegundos), el cual establecerá un delay entre secuencias de comandos |
| `STRING` | Permite inyectar cadenas de caracteres: a-z A-Z 0-9 !-) `~ += _- “‘ :; <, >. ?/ \ |
| `WINDOWS` / `GUI` | Equivale a la tecla Windows o la tecla cmd en MacOS |
| `APP` / `MENU` | Equivale a la combinación de teclas SHIFT F10 de windows (clic derecho) |
| `SHIFT` | Simula la tecla SHIFT, y esta se puede combinar con: DELETE, HOME, INSERT, PAGEUP, PAGEDOWN, WINDOWS, GUI, UPARROW, DOWNARROW, LEFTARROW, RIGHTARROW, TAB |
| `ALT` | Simula la tecla ALT, y esta se puede combinar con: END, ESC, ESCAPE, F1-F12, caracteres simples (ejemplo: f, s), SPACE, TAB |
| `CONTROL` / `CTRL` | Simula la tecla CTRL, y esta se puede combinar con: BREAK, PAUSE, F1-F12, ESCAPE, ESC, caracteres simples |
| `DOWNARROW` / `DOWN` | Simulan las teclas de dirección |
| `LEFTARROW` / `LEFT` | Simulan las teclas de dirección |
| `RIGHTARROW` / `RIGHT` | Simulan las teclas de dirección |
| `UPARROW` / `UP` | Simulan las teclas de dirección |
| `BREAK` / `PAUSE` | Equivale a la combinación CTRL BREAK |
| `CAPSLOCK` | Es la tecla que permite escribir en mayúsculas o minúsculas |
| `DELETE` | Simula la tecla suprimir |
| `END` | Tecla que permite ir al final de algo (página web, documento, etc.) |
| `ESC` / ESCAPE | Tecla de escape |
| `HOME` | En español equivale a la tecla inicio |
| `INSERT` | Simula la tecla inserta |
| `NUMLOCK` | Tecla para bloquear o desbloquear los numerales en los teclados |
| `PAGEUP` | Simula la tecla Page Up |
| `PAGEDOWN` | Simula la tecla Page Down |
| `PRINTSCREEN` | Tecla para tomar screenshots |
| `SCROLLLOCK` | Simula la tecla Scroll Lock |
| `SPACE` | Tecla espacio |
| `TAB` | Tecla de tabulación |
| `REPEAT` | Repite la cantidad de veces que le indiquemos lo ya ejecutado |