# 🚀 PLC IoT Dashboard

Una plataforma IoT para monitoreo y control de PLC Siemens S7-1200, con backend en Python (Flask) y frontend en React.js. Integra MQTT para comunicación en tiempo real y compatibilidad con múltiples protocolos industriales.

[Ver demo](#) · [Reportar error](#) · [Solicitar función](#)

---

## 📑 Tabla de contenidos

- [📌 Sobre el proyecto](#-sobre-el-proyecto)
- [🛠️ Construido con](#️-construido-con)
- [⚙️ Empezar](#️-empezar)
- [🧪 Uso](#-uso)
- [📝 Licencia](#-licencia)
- [🙌 Reconocimientos](#-reconocimientos)

---

## 📌 Sobre el proyecto

Este sistema busca centralizar el monitoreo de variables industriales y control remoto del PLC S7-1200 usando tecnologías modernas y web accesible.

✅ Beneficios:
- Comunicación con PLC vía python-snap7, opcua y pymodbus.
- API RESTful con Flask para conectar con interfaces web o móviles.
- Dashboard en tiempo real con React.js.
- Integración con MQTT para notificaciones y control distribuido.

---

## 🛠️ Construido con

- [Python](https://www.python.org/)
- [Framework por definir](https://404/)
- [React.js](https://react.dev/)
- [Snap7 (opcional)](http://snap7.sourceforge.net/)
- [MQTT (opcional)](https://mqtt.org/)

---

## ⚙️ Empezar

### Prerrequisitos

- Python v3.7+
- pip 20+
- npm 9+ para frontend

### Instalación


#### Clonar repositorio
```bash
git clone https://github.com/deymarFlores/plc-iot-dashboard.git
cd plc-iot-dashboard/backend
```

#### Crear entorno virtual
```bash
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows
```

#### Instalar dependencias
```bash
pip install -r requirements.txt
```

#### Iniciar servidor
```bash
python app.py
```

---

## 🧪 Uso

Puedes probar los endpoints con herramientas como Postman o cURL.

```bash
GET http://localhost:5000/api/plc/status
```

En el frontend, se consumen los datos usando Axios y se renderizan en tiempo real.

---

## 📝 Licencia

Distribuido bajo la licencia **Creative Commons BY-NC 4.0**.  
Uso no comercial únicamente.  
Consulta el archivo [`LICENSE`](./LICENSE) para más detalles.

---

## 🙌 Reconocimientos

- [Plantilla Best-README](https://github.com/othneildrew/Best-README-Template)
- [Node-RED Docs](https://nodered.org/docs/)
- [Snap7 Examples](https://github.com/mathiask88/node-snap7)
