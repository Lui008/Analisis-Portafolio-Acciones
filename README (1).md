# 📊 Análisis de Portafolio de Acciones Españolas

> **Análisis completo de riesgo y retorno** de 5 acciones del IBEX 35 con visualizaciones interactivas en Excel

---

## 📋 Descripción del Proyecto

Este proyecto analiza el comportamiento de **5 empresas españolas líderes** en sus respectivos sectores durante los últimos 2 años, evaluando oportunidades de inversión desde la perspectiva de análisis financiero cuantitativo.

**Acciones analizadas:**
- 🏭 **INDITEX** (Sector: Retail/Moda) - Zara, Pull & Bear, Massimo Dutti
- 🏦 **BBVA** (Sector: Banca) - Banco Bilbao Vizcaya Argentaria
- 🏦 **SANTANDER** (Sector: Banca) - Banco Santander
- 📱 **TELEFÓNICA** (Sector: Telecomunicaciones)
- ✈️ **AMADEUS** (Sector: Tecnología/Viajes)

---

## 🎯 Objetivo

Evaluar el **riesgo y retorno** de cada acción, analizar las **correlaciones** entre ellas, y proporcionar una **evaluación de diversificación** óptima para un portafolio equilibrado.

---

## 📊 Metodología

### **1. Análisis de Rendimiento**
- **Retorno Anual**: Tasa de cambio porcentual en 12 meses
- **Volatilidad**: Desviación estándar anualizada (medida de riesgo)
- **Sharpe Ratio**: Relación retorno/riesgo (cuánto ganas por cada unidad de riesgo asumido)

### **2. Análisis de Correlación**
- Matriz de correlaciones (-1 a 1)
- Evaluación de diversificación (correlaciones bajas = mejor diversificación)

### **3. Construcción del Portafolio**
- Distribución equidistribuida: **20% en cada acción** (5,000€ simulados)
- Análisis de riesgo sistemático y específico

---

## 📈 Resultados Principales

### **Métricas Clave por Acción**

| Acción | Retorno Anual | Volatilidad | Sharpe Ratio | Recomendación |
|--------|---------------|-------------|-------------|---------------|
| **INDITEX** | 42.5% | 18.3% | 2.32 | ⭐⭐⭐ Alto Potencial |
| **BBVA** | 28.4% | 22.1% | 1.28 | ⭐⭐ Moderado |
| **SANTANDER** | 35.2% | 20.5% | 1.71 | ⭐⭐ Moderado |
| **TELEFÓNICA** | 12.3% | 15.7% | 0.78 | ⭐ Bajo Retorno |
| **AMADEUS** | 55.8% | 28.9% | 1.93 | ⭐⭐⭐ Alto Riesgo/Retorno |

### **Matriz de Correlaciones**
- INDITEX ↔ BBVA: **0.35** (Moderada) - Buena diversificación
- INDITEX ↔ AMADEUS: **0.42** (Moderada) - Buena diversificación
- BBVA ↔ SANTANDER: **0.68** (Alta) - Mala diversificación (ambos bancos)
- TELEFÓNICA: **Baja correlación** con todas (Excelente diversificador)

### **Conclusión de Diversificación**
Correlación promedio: **0.42** - ✅ Portafolio bien diversificado

---

## 🎨 Visualizaciones Incluidas

El archivo Excel contiene **6 gráficos profesionales**:

### 1. **Evolución de Precios (Últimos 2 Años)**
- Líneas de tendencia para cada acción
- Identifica patrones y volatilidad visual

### 2. **Retorno Anual Comparativo**
- Gráfico de barras ordenadas
- Visualiza claramente cuál acción tuvo mejor desempeño

### 3. **Volatilidad por Acción**
- Comparativa de riesgo
- Identifica acciones "seguras" vs "volátiles"

### 4. **Análisis Riesgo vs Retorno (Scatter Plot)**
- Relación entre volatilidad y rentabilidad
- Identifica oportunidades en la "frontera eficiente"

### 5. **Matriz de Correlaciones (Heatmap)**
- Colores de rojo (-1) a azul (1)
- Visualiza fácilmente qué acciones se mueven juntas

### 6. **Composición del Portafolio (Pie Chart)**
- Distribución del 20% en cada acción
- Visualiza el peso de cada posición

---

## 💡 Interpretaciones y Hallazgos

### **1. Mejor Retorno: AMADEUS (55.8%)**
- Sector tecnológico con alto crecimiento
- Mayor volatilidad (28.9%) - Riesgo más alto
- **Ideal para**: Inversores tolerantes al riesgo con horizonte largo

### **2. Menor Volatilidad: TELEFÓNICA (15.7%)**
- Empresa estable, sector maduro
- Retorno moderado (12.3%)
- **Ideal para**: Inversores conservadores, generador de dividendos

### **3. Mejor Balance Retorno/Riesgo: INDITEX (Sharpe: 2.32)**
- Retorno sólido (42.5%) con volatilidad contenida (18.3%)
- **Mejor oportunidad de inversión** según Sharpe Ratio
- Modelo de negocio robusto

### **4. Diversificación Recomendada**
```
Portafolio Sugerido (modificado):
├── 25% INDITEX    (Alto retorno, bajo riesgo)
├── 20% AMADEUS    (Crecimiento)
├── 20% SANTANDER  (Exposición financiera)
├── 15% BBVA       (Reducir duplicidad)
└── 20% TELEFÓNICA (Estabilidad)
```

---

## 🛠️ Tecnologías Utilizadas

- **Excel**: Análisis de datos, tablas dinámicas, gráficos
- **Python**: Descarga de datos, cálculos estadísticos
- **Pandas**: Manipulación de datos
- **NumPy**: Análisis numérico
- **Matplotlib & Seaborn**: Visualizaciones avanzadas

---

## 📁 Estructura del Proyecto

```
Analisis_Portafolio_Luka/
│
├── Analisis_Portafolio_Luka.xlsx
│   ├── Hoja 1: Precios Históricos (500 datos)
│   ├── Hoja 2: Resumen Estadístico
│   ├── Hoja 3: Matriz de Correlaciones
│   ├── Hoja 4: Análisis de Portafolio
│   ├── Hoja 5: Recomendaciones
│   └── [6 Gráficos Profesionales]
│
├── README.md (Este archivo)
└── ANALISIS_DETALLADO.txt (Interpretaciones)
```

---

## 🔍 Cómo Usar Este Análisis

### **Para Estudiantes de Economía/Finanzas:**
1. Abre el archivo Excel
2. Revisa la hoja "Resumen Estadístico"
3. Analiza los gráficos
4. Lee las conclusiones
5. Adapta el análisis a otras acciones

### **Para Recrutadores/Inversores:**
1. Visualiza los 6 gráficos
2. Lee las métricas clave
3. Revisa la matriz de correlaciones
4. Considera la cartera sugerida
5. Evalúa el análisis del riesgo

---

## 📊 Métricas Técnicas Explicadas

### **Retorno Anual (%)**
```
Fórmula: [(Precio Final - Precio Inicial) / Precio Inicial] × 100
Interpretación: Ganancia o pérdida en un año (%)
Ejemplo: 42.5% = Si invertiste 100€, ganaste 42.5€
```

### **Volatilidad (%)**
```
Fórmula: Desviación Estándar Diaria × √252
Interpretación: Medida de riesgo (oscilaciones del precio)
Mayor volatilidad = Mayor riesgo y mayor potencial
```

### **Sharpe Ratio**
```
Fórmula: (Retorno - Tasa Libre de Riesgo) / Volatilidad
Interpretación: Retorno por cada unidad de riesgo
Valores > 1: Buena relación retorno/riesgo
```

### **Correlación**
```
Rango: -1 a 1
-1 = Se mueven opuestas (diversificación perfecta)
0 = No hay relación (diversificación buena)
1 = Se mueven igual (diversificación pobre)
```

---

## ⚠️ Disclaimers

- ✋ **Este análisis es educativo**, no es recomendación de inversión
- 💰 **No invertir basándose únicamente en estos datos**
- 📉 **El rendimiento pasado no garantiza rendimiento futuro**
- 🔮 **Factores geopolíticos, económicos y empresariales pueden cambiar**

---

## 📚 Aprendizajes Clave

### **¿Qué aprendí del proyecto?**

1. ✅ **Análisis de datos financieros reales** usando herramientas profesionales
2. ✅ **Evaluación de riesgo y retorno** con métricas cuantitativas
3. ✅ **Estadística aplicada** a decisiones de inversión
4. ✅ **Visualización de datos** para comunicar insights
5. ✅ **Diversificación de carteras** y teoría de portafolios

### **Habilidades Demostradas**

| Habilidad | Evidencia |
|-----------|-----------|
| **Excel Avanzado** | Análisis estadístico, gráficos, tablas dinámicas |
| **Análisis de Datos** | Procesamiento de 500+ datos históricos |
| **Estadística** | Retorno, volatilidad, correlación, Sharpe Ratio |
| **Finanzas Cuantitativas** | Valoración de riesgo, construcción de portafolios |
| **Comunicación Visual** | 6 gráficos profesionales, interpretaciones claras |

---

## 🚀 Extensiones Futuras

Posibles mejoras al proyecto:

- [ ] Incluir análisis de dividendos
- [ ] Backtesting de estrategias de trading
- [ ] Optimización de Markowitz
- [ ] Análisis de fundamental (P/E, ROE, etc.)
- [ ] Predicción con Machine Learning
- [ ] Dashboard interactivo (Power BI / Tableau)

---

## 👨‍💼 Sobre el Análisis

**Autor**: Luka Simsive  
**Estudiante**: 3er año Economía, Universidad de Barcelona  
**Fecha**: 2024  
**Contacto**: luka.simsive18@gmail.com  
**Especializaciones**: Finanzas y Estadística

---

## 📞 Contacto

¿Preguntas sobre el análisis?  
📧 **Email**: luka.simsive18@gmail.com  
📱 **Teléfono**: 631 855 722  
🔗 **LinkedIn**: [Tu perfil]  
💻 **GitHub**: [Tu GitHub]

---

## 📜 Licencia

Este proyecto es de uso educativo y libre.  
Puedes usar, modificar y compartir el análisis con atribución.

---

**¡Espero que este análisis sea útil para tu carrera en finanzas!** 🎯💰
