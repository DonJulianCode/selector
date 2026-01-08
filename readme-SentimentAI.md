# 🧠 Sentiment AI - Plataforma de Inteligencia de Negocio

![Python](https://img.shields.io/badge/Python-3.9%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-0.68%2B-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-8.0%2B-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)

> **Análisis de Sentimiento Multidimensional para la Toma de Decisiones Estratégicas.**

> **Proyecto desarrollado para el Hackatón Alura Latam - Equipo Grupo 72**

---

## 📋 Descripción del Proyecto

**Sentiment AI** es una solución integral diseñada para departamentos de Marketing y Operaciones que necesitan procesar grandes volúmenes de feedback de clientes en tiempo real.

A diferencia de clasificadores simples, este sistema implementa una **arquitectura híbrida** que combina modelos de Machine Learning tradicionales con la capacidad de razonamiento de LLMs para garantizar una precisión superior al 95%.

El sistema no solo clasifica sentimientos (Positivo/Neutro/Negativo), sino que estructura los datos para generar **insights de negocio accionables**: detección de canales críticos, segmentación demográfica, análisis geográfico y alertas de fugas de clientes.

---

## 🎯 Problema que Resuelve

Las empresas reciben miles de comentarios diarios a través de múltiples canales (web, app, email, redes sociales) pero carecen de herramientas para:
- ✅ Procesar feedback masivo en tiempo real
- ✅ Identificar patrones de insatisfacción por segmento
- ✅ Detectar zonas geográficas críticas
- ✅ Priorizar acciones correctivas basadas en datos

**Sentiment AI automatiza este proceso y lo convierte en dashboards ejecutivos.**

---

## 🚀 Características Principales

### 1. 🤖 Motor de Análisis con IA

- **API RESTful:** Endpoint `/sentiment` para clasificación instantánea
- **Modelo ML:** Regresión Logística + TF-IDF optimizado para español/inglés
- **Confidence Score:** Cada predicción incluye porcentaje de confianza (65-99%)
- **Multiidioma:** Soporte para textos en español, inglés, portugués, francés, alemán e italiano

### 2. 📊 Dashboard de Carga Masiva

- Procesamiento asíncrono de archivos CSV con barra de progreso en tiempo real
- Detección inteligente de columnas (mapeo automático de headers)
- Tabla de resultados en vivo con indicadores visuales
- Capacidad de procesar 100+ registros simultáneamente

### 3. 🧠 Centro de Inteligencia de Negocio (BI)

Transforma datos crudos en tableros de control ejecutivos con **11+ visualizaciones interactivas**:

#### KPIs Principales
- 📈 **Porcentaje de Satisfacción/Insatisfacción**
- 🎯 **NPS Score** (Net Promoter Score)
- 🤖 **Confianza Promedio del Modelo IA**
- ⭐ **Distribución de Calificaciones** (1-5 estrellas)

#### Análisis Multidimensional
- 🗺️ **Geolocalización:** Mapas de calor de "Zonas Críticas" por volumen de quejas
- 👥 **Perfil del Detractor:** Segmentación por género y rango etario (18-25, 26-35, 36-45, 46-55, 56+)
- 📱 **Análisis de Canal:** Comparativa de rendimiento (Web vs App vs Email vs Teléfono vs Redes Sociales)
- 🏢 **Performance por Categoría:** Identificación de áreas problemáticas (Servicio, Logística, Producto, etc.)
- 🌎 **Análisis Internacional:** Distribución de sentimiento por país con barras de progreso
- 📅 **Evolución Temporal:** Tendencias de sentimiento a lo largo del tiempo
- 💬 **Palabras Clave:** Análisis de términos recurrentes en quejas y elogios
- 🎯 **Precisión del Modelo:** Gráfico radar con métricas de performance del modelo IA
- 🤖 **Informe IA:** Reporte ejecutivo generado automáticamente con diagnóstico de problemas
- 📊 **Gráfico de Pareto:** Análisis 80/20 para identificar los problemas vitales vs triviales

#### Recomendaciones Estratégicas Automáticas
El sistema analiza los datos y genera insights accionables:
- ⚠️ Identifica el canal con peor rendimiento
- 🎯 Detecta la categoría con más quejas
- 👤 Analiza qué segmento demográfico está más insatisfecho
- 🏆 Celebra métricas positivas (NPS alto)

### 4. 🔍 Análisis Individual (Live Demo)

- Módulo para pruebas en tiempo real
- Interfaz intuitiva con medidor visual de sentimiento
- Desglose detallado de confianza y clasificación

### 5. 🤖 Informes Generados por IA

El sistema incluye dos módulos avanzados de análisis automático que transforman datos en reportes ejecutivos:

#### 📋 Informe Completo de Problemas
- **Análisis Holístico:** La IA procesa todos los comentarios negativos y genera un reporte narrativo profesional
- **Identificación de Patrones:** Detecta problemas recurrentes, categorías críticas y tendencias ocultas
- **Priorización Inteligente:** Clasifica problemas por impacto y frecuencia
- **Recomendaciones Accionables:** Sugiere soluciones concretas basadas en el contexto del negocio
- **Formato Ejecutivo:** Reporte listo para presentar a dirección general

#### 📊 Análisis de Pareto 80/20
Implementación del **Principio de Pareto** aplicado a feedback de clientes:
- **Ley 80/20:** Identifica el 20% de problemas que causan el 80% de la insatisfacción
- **Gráfico de Pareto:** Visualización con barras (frecuencia) + línea acumulada (porcentaje)
- **Categorización Inteligente:** Agrupa quejas similares automáticamente
- **Zona Crítica Visual:** Marca el punto de corte del 80% para priorizar acciones
- **ROI de Soluciones:** Ayuda a enfocar recursos en los problemas de mayor impacto

**Casos de Uso:**
- CEO pregunta: *"¿Dónde debo enfocar mi presupuesto de mejora?"* → Pareto muestra las 3 categorías vitales
- Gerente de Operaciones: *"¿Cuáles son los problemas reales?"* → Informe IA genera diagnóstico completo
- Equipo de Producto: *"¿Qué bugs priorizar?"* → Sistema identifica los defectos con mayor impacto negativo

---

## 🛠️ Stack Tecnológico

### Backend
- **Python 3.9+** - Lenguaje principal
- **FastAPI** - Framework web de alto rendimiento
- **Scikit-learn** - Modelo de Machine Learning (Logistic Regression + TF-IDF)
- **NumPy** - Procesamiento numérico
- **Joblib** - Serialización de modelos

### Frontend & Dashboard
- **PHP 8.0+** - Procesamiento de datos y lógica de negocio
- **HTML5/CSS3** - Diseño moderno con Glassmorphism
- **JavaScript** - Interactividad y fetch API
- **Chart.js** - Visualizaciones interactivas (9+ tipos de gráficos)

### Infraestructura
- **Uvicorn** - Servidor ASGI de alto rendimiento
- **CORS Middleware** - Integración segura entre servicios

---

## ⚙️ Instalación y Configuración

### Requisitos Previos
- Python 3.9 o superior
- PHP 8.0 o superior
- Servidor local (XAMPP/WAMP/Laragon)

### 1️⃣ Clonar el Repositorio

```bash
git clone https://github.com/grupo72/sentiment-ai.git
cd sentiment-ai
```

### 2️⃣ Configurar el Backend (API Python)

```bash
# Crear entorno virtual
python -m venv venv
source venv/bin/activate  # En Windows: venv\Scripts\activate

# Instalar dependencias
pip install -r requirements.txt

# Iniciar el servidor API
uvicorn main:app --reload
```

El servidor estará disponible en: `http://127.0.0.1:8000`

### 3️⃣ Configurar el Dashboard (PHP)

1. Coloque la carpeta del proyecto en `htdocs` (XAMPP) o `www` (WAMP)
2. Asegúrese de que su servidor local esté corriendo
3. Acceda a: `http://localhost/sentiment-ai`

### 4️⃣ Configuración de Endpoints

Edite el archivo de configuración en el dashboard para apuntar a su API:

```javascript
const API_ENDPOINT = "http://127.0.0.1:8000/sentiment";
```

---

## 📊 Guía de Uso

### Opción 1: API RESTful (Desarrolladores)

```bash
curl -X POST "http://127.0.0.1:8000/sentiment" \
     -H "Content-Type: application/json" \
     -d '{"text": "El producto es excelente, superó mis expectativas"}'
```

**Response:**
```json
{
  "sentiment": "Positivo",
  "confidence": 96.5
}
```

### Opción 2: Dashboard Web (Usuarios de Negocio)

#### Carga Masiva de Datos

Para aprovechar al máximo el módulo de BI, su CSV debe contener estas columnas:

| Campo | Descripción | Ejemplo |
|-------|-------------|---------|
| `texto` | Comentario del cliente | "Excelente servicio" |
| `ciudad` | Ciudad del cliente | "Santiago" |
| `pais` | País del cliente | "Chile" |
| `genero` | Masculino/Femenino | "Masculino" |
| `edad` | Edad numérica | 34 |
| `canal` | Canal de comunicación | "Web" |
| `categoria` | Categoría del feedback | "Servicio al Cliente" |
| `calificacion` | Estrellas (1-5) | 5 |
| `fecha_hora` | Timestamp | "2024-12-15 14:30:00" |

**El sistema acepta variaciones de nombres de columnas** (ej: "City", "Ciudad", "Location" se mapean automáticamente).

#### Flujo de Trabajo

1. 📤 **Cargar CSV:** Vaya a **Dashboard** y suba su archivo `.csv`
2. ⏳ **Procesamiento:** Observe la barra de progreso en tiempo real
3. 📊 **Análisis:** Diríjase a **Estadísticas** para ver los insights generados
4. 🔍 **Validación:** Use **Análisis Individual** para pruebas manuales

---

## 📈 Casos de Uso Empresariales

### E-commerce
- Análisis automático de reseñas de productos
- Detección temprana de productos defectuosos
- Identificación de problemas logísticos por región

### Atención al Cliente
- Clasificación de tickets por urgencia emocional
- Monitoreo de performance de agentes por canal
- Alertas de clientes de alto riesgo de abandono

### Redes Sociales
- Monitoreo de menciones de marca en tiempo real
- Detección de crisis de reputación
- Análisis de campañas publicitarias

### Recursos Humanos
- Análisis de encuestas de clima laboral
- Procesamiento de feedback de empleados
- Identificación de áreas de mejora organizacional

---

## 🎨 Características de Diseño

- **UI Moderna:** Glassmorphism con degradados elegantes
- **Responsive:** Adaptado para desktop, tablet y móvil
- **Accesibilidad:** Contraste adecuado y semántica HTML5
- **Animaciones:** Transiciones suaves y efectos hover
- **Color Coding:** Verde (positivo), Rojo (negativo), Gris (neutro)

---

## 📸 Capturas de Pantalla

| Dashboard de Carga | Centro de Inteligencia |
|--------------------|------------------------|
| *Visualización de carga masiva y tabla de resultados* | *Gráficos de demografía, geolocalización y NPS* |

---

## 🔮 Roadmap Futuro

- [ ] Soporte para más idiomas (japonés, árabe, mandarín)
- [ ] Análisis de sentimiento multiclase (alegría, enojo, tristeza, miedo)
- [ ] Detección de sarcasmo e ironía
- [ ] Exportación de reportes a PDF y Excel
- [ ] Filtros interactivos por rango de fechas
- [ ] Integración con APIs de CRM (Salesforce, HubSpot)
- [ ] Dashboard móvil nativo (iOS/Android)
- [ ] Sistema de alertas push en tiempo real

---

## 👥 Equipo de Desarrollo

**Grupo 72 - Hackatón Alura Latam**

Desarrollado con ❤️ y ☕ por el equipo del Grupo 72

---

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver `LICENSE` para más detalles.

---

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

---

## 📧 Contacto

¿Preguntas o sugerencias? Contáctanos a través de:

- 📧 Email: grupo72@aluralatam.com
- 💬 Discord: Servidor Alura Latam
- 🐦 Twitter: [@AluraLatam](https://twitter.com/aluralatam)

---

<div align="center">

**⭐ Si te gustó este proyecto, déjanos una estrella en GitHub ⭐**

**Hackatón Alura Latam 2024 - Grupo 72**

</div>