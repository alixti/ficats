# FiCats Manager
Sistema orientado a la gestión de la veterinaria ficticia "FiCats".

# Contexto
Este sistema fue desarrollado como nuestro proyecto de título. Dicho esto, no está 100% terminado puesto que faltan ciertas configuraciones de seguridad y para los archivos estáticos para producción. Originalmente el proyecto usaba MySQL y whitenoise, pero para que sea más fácil de compartir el repositorio y demostrar el uso de la plataforma se usará SQLite y se eliminó el requisito de whitenoise.

# Manuales e informes del desarrollo
Adicionalmente realizamos distintos manuales e informes de todo el desarrollo que se encuentra [aquí](https://inacapmailcl-my.sharepoint.com/:f:/g/personal/diego_munoz179_inacapmail_cl/EgZVzIea4e1Gsi8_J1VsTgkBT5wMCoShqfUnB_iNIHZbCQ).

# Instalación
1. Crear ambiente virtual `python -m venv .venv`
2. Instalar dependencias con `pip install -r requirements.txt`
3. Correr los comandos de más abajo.

# Comandos
- Realizar migraciones BD: `python manage.py migrate`
- Crear superusuario rápido: `python manage.py createsuperuser --noinput`
- Configurar grupos, permisos, etc.: `python manage.py configurar_permisos`
- Correr servidor de desarrollo: `python manage.py runserver`

# Creditos
- Diego Muñoz (todo lo demás)
- Luis Navarrete (logo, formularios, modelos)
- Josué Coloma (frontend)