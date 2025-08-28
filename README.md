# 🧭 RPG Adventure Game (Python + Flet)

Este es un juego RPG de aventura por texto con interfaz gráfica, desarrollado en Python usando [Flet](https://flet.dev/). El jugador puede explorar un pequeño mundo con lugares conectados, recoger objetos, interactuar con personajes y moverse libremente mediante comandos escritos.

---

## 🎮 Características

- Interfaz gráfica sencilla con Flet.
- Exploración de un mapa: bosque, aldea, cueva, etc.
- Comandos para moverse (`ir`), recoger objetos, hablar con personajes y ver el inventario.
- Mundo inicial con objetos, personajes y descripciones.
- Código modular, ideal para expandir.

---

## 📁 Estructura del proyecto

```bash
rpg-Python/
│
├── juego.py # Interfaz gráfica, entrada del juego, lógica principal del juego y comandos
├── juego_web.py # Interfaz web
├── lugar.py # Clase Lugar: escenarios conectados
├── objeto.py # Clase Objeto: objetos recolectables
├── personaje.py # Clase Personaje: NPCs con diálogo
├── jugador.py # Clase Jugador: inventario y movimiento
├── requirements.txt # Dependencias (incluye flet)
└── .gitignore # Archivos ignorados por Git
└── README.md
```

---

## 🚀 Instrucciones de instalación y ejecución

1. Clona el repositorio:

```bash
git clone https://github.com/EstefanyRodriguezP/rpg-Python.git
cd rpg-Python
```

2. Crea y activa un entorno virtual:

```bash
python -m venv rpg
source rpg/bin/activate        # Linux/macOS
.\rpg\Scripts\activate         # Windows
```

3. Instala las dependencias:

```bash
pip install -r requirements.txt
```

4. Ejecuta el juego:

```bash
python main.py
```

## 🕹️ Comandos disponibles en el juego

- mirar: ver descripción del lugar, objetos, personajes y salidas.

- ir [dirección]: moverse a otro lugar (norte, sur, este, oeste).

- recoger [objeto]: recoger un objeto del lugar.

- hablar [personaje]: hablar con un NPC presente.

- inventario: ver objetos recolectados.

- limpiar: limpiar la pantalla de texto.

## 🧠 Ideas para mejorar

- Añadir combate por turnos.

- Implementar historia y misiones.

- Crear más tipos de personajes y objetos.

- Guardar y cargar progreso.

- Añadir música o efectos visuales con Flet.

## 🛠️ Requisitos

- Python 3.10 o superior

- Flet (pip install flet)

---

💻 Desarrollado por [Estefany Rodríguez P.](https://github.com/EstefanyRodriguezP)
