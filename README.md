Juan Esteban Henao Echavarria
GitHub es sistema de control de versiones creado en 2025 usado princpalmente para el desarrollo de software debido a que guarda un historial de todos los camnios guardados en un codigo fuentes y permite a los desarrolladores revetir cualquier cambio en el tiempo y tenerlos guardados en un repertorio ademss de llevar un seguimiento de los cambios realizados y permitir una mayor colaboracion con otros desarrolladores permite crear y trabajar en ramas independientes al codigo principal que permite desarrollar nuevas funciones o corregur errores sin afectar el codigo principalGit es un sistema de control de versiones distribuido, creado por Linus Torvalds en 2005, que se utiliza principalmente para el desarrollo de software.
 Permite a los desarrolladores llevar un seguimiento de los cambios realizados en el código fuente a lo largo del tiempo y colaborar de manera más eficiente con otros desarrolladores.
 Control de versiones: Git guarda un historial completo de todos los cambios realizados en el código fuente, lo que permite a los desarrolladores ver y revertir cualquier cambio en el tiempo.
 Ramas y fusiones: Git permite a los desarrolladores crear y trabajar en ramas independientes del código principal. Esto es útil para el desarrollo de nuevas funciones o para corregir errores sin afectar el código principal. Las ramas se pueden fusionar de nuevo en el código principal una vez que los cambios han sido probados y aprobados.
 Distribuido: A diferencia de los sistemas de control de versiones centralizados, cada copia del repositorio Git es un repositorio completo con toda su historia y sus funciones. Esto significa que los desarrolladores pueden trabajar sin conexión y seguir teniendo acceso a todas las versiones y cambios.
 Fernanda: Colaboración: Git facilita la colaboración entre desarrolladores, permitiendo a múltiples personas trabajar en diferentes partes del proyecto al mismo tiempo. Los cambios se pueden combinar y revisar antes de ser incorporados al código principal.
 Fernanda: Integración con servicios y herramientas: Git se integra fácilmente con diversas plataformas y servicios, como GitHub, GitLab y Bitbucket, que ofrecen funcionalidades adicionales como la gestión de proyectos, la revisión de código y la integración continua.
 las diferencias entre Git y otros sistemas de control de versiones (SCV):

| Característica     | Git                                | Otros SCV (SVN, CVS)               |
|--------------------|------------------------------------|------------------------------------|
| **Modelo**         | Distribuido                        | Centralizado                       |
| **Rendimiento**    | Rápido (operaciones locales)       | Más lento (dependiente del servidor) |
| **Ramas**          | Ligeras y fáciles de manejar       | Más pesadas y difíciles de manejar |
| **Modelo de datos**| Basado en instantáneas (snapshots) | Basado en diferencias (deltas)     |
| **Seguridad**      | Hashes criptográficos (SHA-1)      | Variable, generalmente menos robusto |
| **Trabajo sin conexión** | Completo (copia completa del repositorio) | Limitado (requiere conexión al servidor) |



git init: Inicializa un nuevo repositorio Git en el directorio actual.

git clone <url>: Clona un repositorio remoto a tu máquina local.

git add <archivo>: Agrega cambios de archivos al área de preparación (staging).

git commit -m "<mensaje>": Guarda los cambios en el repositorio local con un mensaje descriptivo.

git status: Muestra el estado de los archivos en el directorio de trabajo y el área de preparación.

git push: Sube los cambios locales a un repositorio remoto.

git pull: Trae los cambios de un repositorio remoto y los fusiona con tu rama local.

git fetch: Descarga los cambios desde un repositorio remoto sin fusionarlos automáticamente.

git branch: Muestra las ramas locales del repositorio.

git checkout <rama>: Cambia a una rama específica.

git merge <rama>: Fusiona los cambios de una rama en la rama actual.

git log: Muestra el historial de confirmaciones del repositorio.

git remote -v: Muestra las URL de los repositorios remotos asociados.

git reset <archivo>: Elimina los archivos del área de preparación sin eliminarlos del directorio de trabajo.

git rm <archivo>: Elimina un archivo del repositorio y del área de preparación.

git rebase <rama>: Reaplica las confirmaciones de la rama actual sobre otra rama, para mantener un historial más limpio.

git diff: Muestra las diferencias entre los archivos modificados y los confirmados.

git stash: Guarda temporalmente los cambios no confirmados para poder trabajar en otras cosas.

git tag: Crea una etiqueta en un commit específico para marcar versiones o puntos importantes del proyecto.

git config: Configura opciones globales o locales de Git, como el nombre de usuario o el correo electrónico.
