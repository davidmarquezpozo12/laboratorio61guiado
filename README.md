# Control por Voz - AssemblyAI + Tkinter

Aplicación de reconocimiento de voz en tiempo real usando AssemblyAI y interfaz gráfica con Tkinter.

## Requisitos

- Python 3.8+
- Micrófono
- Conexión a internet
- API key de AssemblyAI

## Instalación

1. Clonar el repositorio:
```bash
git clone https://github.com/alelorenzo085/control_voz_assemblyai.git
```

2. Crear archivo `.env` con la API key:
```
AAI_API_KEY=mi_clave_aqui
```

3. Instalar dependencias:
```bash
pip install -r requirements.txt
```

## Uso

Ejecutar la aplicación:
```bash
$env:AAI_API_KEY="tu_key"
python main.py
```

### Comandos de Voz

- **"Enciende motor"** - Enciende el motor (cambia a ON)
- **"Apaga motor"** - Apaga el motor (cambia a OFF)
- **"Salir"** - Cierra la aplicación

## Estructura del Proyecto

- `main.py` - Clase principal de la aplicación
- `modules/audio_manager.py` - Grabación y transcripción
- `modules/gui_manager.py` - Interfaz gráfica
- `modules/command_processor.py` - Procesamiento de comandos
- `api_key.env` - API KEY que no se sube a Github

