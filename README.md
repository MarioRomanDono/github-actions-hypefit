# Hypefit-GitHub-Actions

Este proyecto tenía como objetivo automatizar el proceso de despliegue en un VPS de la aplicación web Hypefit, [disponible aquí](https://github.com/Hypefit/hypefit). Para ello, desarrollé un *workflow* usando GitHub Actions que ejecutase los pasos necesarios, es decir: conectarse a la VPN de la UCM, crear un túnel SSH con un hop server y, finalmente, enviar los archivos del repositorio al VPS.

No pudo ser terminado completamente debido a que, en ocasiones, el proceso de despliegue no se llegaba a ejecutar correctamente. Tras la entrega del proyecto principal, perdí el acceso al VPS y no pude debuggear el *workflow* para encontrar el fallo.

Aun así, considero que fue de gran utilidad para mí debido a que pude aprender sobre el funcionamiento de GitHub Actions, comprender conceptos de *Continuous Deployment* y aplicar soluciones DevOps para mejorar la eficiencia de nuestro trabajo. [En mi página web](https://marioromandono.github.io/hypefit-github-actions) explico con más detalle cómo llevé a cabo este proyecto.

Por si pudiera ser de utilidad, todo el código del repositorio se encuentra bajo la licencia del MIT. 
