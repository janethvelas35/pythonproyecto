# Sudoku - Juego de Números

Un juego interactivo de Sudoku desarrollado en Python. Resuelve acertijos de Sudoku de distintos niveles de dificultad con una interfaz amigable.

## 📋 Descripción

Este es un juego de Sudoku implementado en Python que permite a los jugadores:
- Jugar partidas de Sudoku en diferentes niveles de dificultad
- Validar soluciones automáticamente
- Recibir pistas cuando sea necesario
- Registrar el progreso del juego

## ✨ Características

- 🎮 **Interfaz interactiva** - Juego en línea de comando fácil de usar
- 📊 **Múltiples niveles de dificultad** - Fácil, Medio, Difícil
- ✓ **Validación en tiempo real** - Comprueba si tus números son válidos
- 💡 **Sistema de pistas** - Obtén ayuda cuando la necesites
- 📈 **Contador de movimientos** - Sigue tu progreso
- 🔄 **Reinicio de juego** - Vuelve a empezar cuando quieras

## 🛠️ Requisitos

- Python 3.7 o superior
- No se requieren dependencias externas

## 📦 Instalación

1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/tuusuario/sudoku-python.git
   cd sudoku-python
   ```

2. **Verificar que Python esté instalado**
   ```bash
   python --version
   ```

## 🚀 Cómo usar

Ejecuta el juego con el siguiente comando:

```bash
python Miproyecto.py
```

### Instrucciones del juego

1. Se mostrará un tablero de Sudoku con algunos números ya colocados
2. Ingresa los números del 1 al 9 para completar el tablero
3. El juego validará automáticamente tus movimientos
4. Completa todo el tablero respetando las reglas del Sudoku:
   - Cada fila debe contener números del 1 al 9 sin repetición
   - Cada columna debe contener números del 1 al 9 sin repetición
   - Cada subcuadrícula 3x3 debe contener números del 1 al 9 sin repetición

## 📁 Estructura del Proyecto

```
sudoku-python/
├── Miproyecto.py          # Archivo principal del juego
├── README.md              # Este archivo
└── tableros/              # Tableros predefinidos
    ├── facil.txt
    ├── medio.txt
    └── dificil.txt
```

## 🎮 Ejemplo de uso

```
Sudoku - ¡Bienvenido!
====================

Ingresa la fila (1-9): 1
Ingresa la columna (1-9): 2
Ingresa el número (1-9): 5

¡Movimiento válido! Continúa...
```

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Para cambios importantes:

1. Fork el proyecto
2. Crea una rama para tu característica (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📝 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## 👤 Autor

Desarrollado como proyecto educativo de Python Fundamentos.

## 📞 Soporte

Si encuentras problemas o tienes sugerencias, por favor abre un [issue](https://github.com/tuusuario/sudoku-python/issues).

---

**¡Disfruta resolviendo Sudokus!** 🎯

