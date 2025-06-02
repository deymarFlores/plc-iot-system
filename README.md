# 🚀 PLC IoT Dashboard

Una plataforma IoT para monitoreo y control de PLC Siemens S7-1200, con backend en **Node.js (Express)** y frontend en **Vue.js**. Integra **Node-RED** para comunicación en tiempo real.

[Ver demo](#) · [Reportar error](#) · [Solicitar función](#)

---

## 📑 Tabla de contenidos

- [Sobre el proyecto](#sobre-el-proyecto)
- [Construido con](#construido-con)
- [Empezar](#empezar)
- [Uso](#uso)
- [Licencia](#licencia)
- [Contacto](#contacto)
- [Reconocimientos](#reconocimientos)

---

## 📌 Sobre el proyecto

Este sistema busca centralizar el monitoreo de variables industriales y control remoto del PLC S7-1200 usando tecnologías modernas y web accesible.

✅ Beneficios:
- Comunicación con PLC vía Node-RED o Snap7.
- API RESTful para conectar con interfaces web o móviles.
- Dashboard con Vue.js para visualizar en tiempo real.

---

## 🛠️ Construido con

- [Node.js](https://nodejs.org/)
- [Express](https://expressjs.com/)
- [Vue.js](https://vuejs.org/)
- [Node-RED](https://nodered.org/)
- [Snap7 (opcional)](http://snap7.sourceforge.net/)
- [MQTT (opcional)](https://mqtt.org/)

---

## ⚙️ Empezar

### Prerrequisitos

- Node.js v18+
- npm v9+
- (Opcional) Node-RED instalado localmente

### Instalación

```bash
# Clonar repositorio
git clone https://github.com/deymarFlores/plc-iot-dashboard.git
cd plc-iot-dashboard/backend

# Instalar dependencias
npm install

# Iniciar servidor
npm run dev
```

---

## 🧪 Uso

Puedes probar los endpoints con herramientas como Postman o cURL.

```bash
GET http://localhost:3000/api/plc/status
```

En el frontend, se consumen los datos usando Axios y se renderizan en tiempo real.

---

## 📝 Licencia

Distribuido bajo la licencia **Creative Commons BY-NC 4.0**.  
Uso no comercial únicamente.  
Consulta el archivo [`LICENSE`](./LICENSE) para más detalles.

---

## 📬 Contacto

**Deymar Flores**  
GitHub: [@deymarFlores](https://github.com/deymarFlores)  
Correo: deymarflores127@gmail.com

---

## 🙌 Reconocimientos

- [Plantilla Best-README](https://github.com/othneildrew/Best-README-Template)
- [Node-RED Docs](https://nodered.org/docs/)
- [Snap7 Examples](https://github.com/mathiask88/node-snap7)
