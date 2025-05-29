# SQL-Analisis-Empresa
# 📊 Análisis SQL de Smart Desk: Ingresos Postventa por Industria

Este proyecto es un caso práctico de análisis de bases de datos relacionales mediante SQL. Se ha desarrollado como trabajo para la asignatura de Bases de Datos SQL, y utiliza datos simulados de la empresa **Smart Desk**, dedicada a la fabricación y venta de mobiliario ergonómico de oficina.

## 🎯 Objetivo

El análisis busca identificar **qué industrias generan más beneficios a largo plazo**, no solo por la venta directa de productos, sino también a través de los **servicios postventa** (mantenimiento y soporte). El objetivo final es **segmentar industrias prioritarias** y detectar oportunidades de negocio.

---

## 📚 Contenido

- 📁 `IagoPadilha_TareaSQL.pdf`: Documento con el análisis completo, hipótesis, resultados, segmentación y conclusiones.
- 📄 `Queries_IagoPadilha_TareaSQL.txt`: Conjunto de consultas SQL utilizadas para extraer, agrupar, segmentar y analizar los datos.
- `Dataset.zip`: Un archivo zip donde están los datasets usados

---

## 🧠 Hipótesis

> Smart Desk genera una parte significativa de sus ingresos gracias a servicios postventa. Estos ingresos varían según la industria del cliente. Por tanto, puede ser más eficiente enfocar los esfuerzos comerciales hacia industrias con **mayores ingresos postventa por unidad vendida**, aunque el volumen total no sea el más alto.

---

## 🛠️ Herramientas utilizadas

- Lenguaje: **SQL estándar**
- Entorno: Compatible con PostgreSQL / BigQuery / Snowflake
- No requiere visualización externa ni scripts adicionales.

---

## 🔍 Principales análisis realizados

1. **Análisis exploratorio general**
   - Clientes, pedidos, beneficios, unidades vendidas
   - Rango temporal de operaciones

2. **Agregaciones por industria**
   - Total de beneficios postventa y de ventas
   - Cálculos por unidad y por pedido

3. **Creación de vistas**
   - Vistas con medias y totales por industria
   - Vistas con beneficios por unidad

4. **Segmentación de industrias**
   - Categorización en Alta / Media / Baja importancia
   - Uso de percentiles para establecer umbrales

5. **Detección de oportunidades internas**
   - Análisis de acuerdos abiertos o sin iniciar
   - Priorización de industrias clave para nuevos contratos

---

## 📌 Resultados destacados

- Las industrias más rentables a largo plazo no son necesariamente las que más compran.
- Cuatro industrias clave (Biotecnología, Legal, Hotelera y Servicios de Hogar) generan **altos ingresos postventa por unidad vendida**.
- Se propone una estrategia dual:
  - **Externa**: fidelización personalizada y servicios postventa adaptados
  - **Interna**: priorización de acuerdos abiertos en industrias clave

---

## ✅ Conclusión

Este trabajo demuestra cómo el uso estratégico de SQL puede transformar datos operativos en **conocimiento accionable para la toma de decisiones comerciales**. La combinación de indicadores financieros y segmentación permite orientar esfuerzos hacia relaciones más rentables para la empresa.

---

## ✍️ Autor

**Iago Padilha Gómez**  
Trabajo académico para la asignatura de Bases de Datos SQL  
(Máster en Data Science / Business Analytics)

