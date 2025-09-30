# Seguridad en el control de versiones

* **Contraseñas y claves** (`.env`, `.secret`, etc.): se excluyen para no exponer datos sensibles.
* **Configuraciones locales** (`.vscode/`, `.idea/`): dependen de cada usuario y no sirven al resto.
* **Ficheros temporales** (`*.log`, `*.tmp`): son generados automáticamente y no tienen valor en el repositorio.
* **Binarios y compilados** (`*.exe`, `*.class`, `dist/`): se pueden regenerar a partir del código y solo hacen más pesado el proyecto.

Con esto nos aseguramos de que el repositorio sea más seguro, limpio y útil para el desarrollo.


---

## Conclusión

El archivo `.gitignore` nos ayuda a trabajar de forma más segura y ordenada porque evita que subamos cosas que no hacen falta, como contraseñas, archivos temporales o programas compilados. De esta manera, en el repositorio solo queda lo importante: el código y la documentación. Así es más fácil colaborar, se evitan problemas y mantenemos el proyecto limpio.

