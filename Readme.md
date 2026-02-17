# Secure Password Generator

Generador de contraseñas aleatorias criptográficamente seguras desarrollado en Python.

## Descripción
Este programa genera contraseñas utilizando el módulo `secrets` de Python, asegurando una aleatoriedad apta para fines de seguridad. Permite personalizar la longitud de la cadena resultante.

## Requisitos
* Python 3.x

## Instalación y Uso

1. Clonar el repositorio:
   git clone https://github.com/Equiliibrium/Generator-Password.git

2. Ejecutar el script principal:
   python main.py

3. Funcionamiento:
   El programa solicitará una longitud. Si no se ingresa un valor (presionando Enter), se asignará una longitud de 16 caracteres por defecto.

## Pruebas
Para ejecutar las pruebas unitarias y verificar el funcionamiento del generador:

python Test_password_create.py

## Estructura del Proyecto
* main.py: Lógica del generador y punto de entrada.
* Test_password_create.py: Suite de pruebas unitarias.
* .gitignore: Archivos excluidos del repositorio.