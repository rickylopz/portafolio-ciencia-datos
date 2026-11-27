# 04. Mi primer commit

## En una línea cada uno: qué hacen `status`, `add`, `commit` y `push`
* **`git status`:** Revisas qué cambios se han realizado en tu carpeta de trabajo.
* **`git add`:** Prepara todos los cambios que hubo dentro de la carpeta o proyecto para ser guardados.
* **`git commit`:** Guardas la “foto” de lo que estuviste trabajando y le pones un nombre descriptivo.
* **`git push`:** Sube tu commit o trabajo al repositorio remoto en GitHub.

## En una línea cada uno: qué hacen `log`, `checkout` y `revert`
* **`git log`:** Miras el historial de cambios y movimientos que ha habido en el proyecto.
* **`git checkout`:** Permite volver o moverte a un commit anterior (o rama) que desees revisar.
* **`git revert`:** Si en tu commit actual algo está mal, genera un nuevo commit que deshace esos cambios volviendo al estado anterior, pero manteniendo el historial sin eliminar el commit erróneo.

## Un párrafo: qué archivo de tu trabajo versionarías con Git y por qué
Versionaría los archivos de documentación, flujos y configuraciones de conexión que se le realizan a un agente de IA durante la etapa de *testing*. Esto permitiría llevar un control exacto de qué *prompts*, reglas o parámetros funcionaron mejor en cada prueba y regresar fácilmente a una versión estable si algún ajuste rompe el comportamiento esperado.