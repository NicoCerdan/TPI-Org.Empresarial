# TPI-Org.Empresarial
Trabajo Practico Integrador

Este proyecto corresponde al **TPI de Organización Empresarial**.  
Se presenta una **simulación en consola** de un chatbot que gestiona solicitudes administrativas (ejemplo: vacaciones).  
El objetivo es mostrar cómo funcionaría el sistema, incluyendo el **camino feliz** y el **camino infeliz** (manejo de errores).

---

## 👤 Integrantes
- Nicolás Cerdán

---

# Trabajo Práctico Integrador – Organización Empresarial
## Automatización del proceso de gestión de vacaciones mediante chatbot

### 📌 Descripción
Este repositorio contiene la documentación y simulación del chatbot para la gestión de vacaciones en RRHH, desarrollado como parte del TPI-OE.

## 📂 Estructura del repositorio
- `/src/` → código fuente de la simulación (`chatbot_simulacion.py`).  
- `/documentacion/` → informe PDF con explicación del proceso y diagramas BPMN.  
- `/capturas/` → evidencia visual de la simulación (camino feliz e infeliz).  
- `/diccionario/` → diccionario de datos con restricciones y reglas de negocio.  
- `README.md` → este archivo, con instrucciones de uso.

---

## ⚙️ Requisitos
- **Python 3.10** o superior  
- No requiere librerías externas (solo funciones básicas de Python).  

---

## ▶️ Instalación
Clonar el repositorio:
```bash
git clone https://github.com/NicoCerdan/TPI-Org.Empresarial.git
cd TPI-Org.Empresarial
```

### 📂 Contenido
- **TPI.pdf** → Informe completo con análisis, BPMN, arquitectura y pruebas.
- **Modelo TPI(img).png** → Diagrama del proceso modelado en Bizagi.
- **dataset.json** → Base de datos simulada con empleados y días disponibles en archivo json.

### ⚙️ Simulación
El chatbot se plantea sobre **WhatsApp Business API** con lógica en **Python**.  
La base de datos se simula en JSON y se gestiona en **estados** que recuerda el paso actual del usuario.

### 👨‍💻 Autor
Nicolás Cerdán – Tecnicatura Universitaria en Programación

