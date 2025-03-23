# partial3_Alvarado
La presente aplicación es la implementación de la librería flask-login para protección de rutas y control de acceso a la misma, la cuál se desarrolló sobre la aplicación "Examen" que originalmente funje como registro de ventas de una pizzeria, registra, tamaños, sabores, nombre del cliente y fecha de la compra.

Tecnologías Utilizadas:
Backend: Flask (Python)
Frontend: HTML, CSS, TailwindCss
Base de Datos: MySQL
Servidor de Desarrollo: Flask con un servidor local

Requisitos Previos:
Para ejecutar la aplicación en un entorno local, es necesario tener instalado:
Python 3.10
Virtualenv (opcional pero recomendado)
Flask y las librerías necesarias (definidas en requirements.txt)

Instalación y Configuración:
Clonar el repositorio:
git clone https://github.com/IDGS-801-22001042/partial3_Alvarado.git
cd Examen

Crear un entorno virtual desde CMD:
py -m venv .env
Examen/.env/scripts/activate

Instalar dependencias:
pip install -r requirements.txt

Ejecutar la aplicación en CMD:
py app.py
La aplicación estará disponible en http://127.0.0.1:5000/

Uso de la Aplicación:
Pedido de Pizzas
Los usuarios pueden:
Ingresar su información personal.
Seleccionar el tamaño de la pizza y sus ingredientes.
Agregar el pedido.
Ver el detalle del pedido antes de confirmar.
Quitar pizzas del pedido

Consulta de ventas:
Seleccionar busqueda por día o por mes
Ingresar fecha específica en caso de requerir la información de las ventas.
