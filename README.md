# agentee_funcional

# 🤖 Agente Funcional con LangChain

**Autor:** Ignacio Calderón  
**Asignatura:** ISY0101 - Optativo Ingeniería de Soluciones con IA  
**Fecha de entrega:** 29 de octubre de 2025  

---

## 📘 Descripción General

Este proyecto implementa un **agente funcional automatizado** desarrollado con el framework **LangChain Agents**, diseñado para simular un entorno organizacional inteligente.  
El agente integra módulos de **consulta**, **razonamiento**, **memoria contextual** y **generación de reportes automáticos**, demostrando capacidades de planificación, toma de decisiones adaptativa y continuidad conversacional.

---

## ⚙️ Características Principales

- 🔍 **Consulta de datos simulados:** Acceso a información a través de una API local.  
- 🧠 **Razonamiento lógico:** Aplicación de reglas condicionales para la toma de decisiones.  
- 📝 **Generación de reportes:** Creación automática de resúmenes y reportes internos.  
- 💬 **Memoria de conversación:** Mantiene el contexto y coherencia en interacciones prolongadas.  
- 🧾 **Planificación de tareas:** Estructura secuencial para recopilar datos, analizar métricas y producir informes.  

---

## 🧩 Arquitectura y Componentes

| Componente | Descripción | Justificación |
|-------------|-------------|----------------|
| **LangChain Core** | Framework base modular para agentes con herramientas y cadenas lógicas. | Soporte nativo para integración con APIs y memoria contextual. |
| **Memoria de conversación** | Guarda el historial de interacciones. | Permite continuidad en flujos conversacionales. |
| **Vector Store (FAISS)** | Búsqueda semántica eficiente de información previa. | Mejora la recuperación contextual. |
| **Agente funcional** | Orquesta los módulos de razonamiento, consulta y escritura. | Simula un flujo organizacional automatizado. |

---

## 🧠 Ejemplos de Lógica Implementada

- Si la base de datos no responde, el agente **reintenta tres veces** y **genera una alerta** al usuario.  
- Si el reporte semanal detecta valores anómalos, el agente **crea un ticket automático** de revisión técnica.  

---

## 🏗️ Requisitos de Instalación

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/usuario/agente-funcional-langchain.git
   cd agente-funcional-langchain
