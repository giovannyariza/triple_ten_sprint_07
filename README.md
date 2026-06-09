# ConnectaTel Sprint 7 - Análisis de Clientes y Uso

## 🚀 Resumen del Proyecto
Este proyecto entrega un análisis completo de los clientes de ConnectaTel, con especial foco en su comportamiento de uso, calidad de datos y segmentación estratégica. A partir de los datasets `users_latam.csv`, `usage.csv` y `plans.csv`, se construyó un perfil de usuario que permite identificar segmentos de valor y recomendaciones accionables para mejorar la oferta comercial.

## 🎯 Objetivos
- Explorar y limpiar los datos de clientes y uso real.
- Detectar problemas de calidad en `age`, `city` y las fechas de uso.
- Generar métricas agregadas por usuario para entender consumo de mensajes, llamadas y minutos.
- Crear segmentos por edad y nivel de uso.
- Identificar outliers que representan clientes intensivos y oportunidades de plan.
- Presentar un análisis ejecutivo claro para stakeholders.

## 📊 Qué encontrarás en el notebook
- Limpieza y validación de variables clave.
- Análisis de distribución por plan para variables como edad, mensajes y llamadas.
- Segmentación de clientes en `Bajo uso`, `Uso medio` y `Alto uso`.
- Perfil de edad: `Joven`, `Adulto Joven` y `Adulto Mayor`.
- Detección de outliers con boxplots e interpretación de su impacto comercial.
- Recomendaciones para diseñar mejores planes y migraciones de clientes de alto uso.

## 🧩 Resultados más relevantes
- Se identificaron 55 registros de edad inválidos (`-999`) y 96 valores de ciudad con `?`.
- El segmento más numeroso es `Adulto Joven` (~49% de la base).
- El 41% de los usuarios pertenece al segmento `Alto uso`, con clientes intensivos en llamadas y mensajes.
- El plan `Básico` concentra más usuarios de alto uso en valor absoluto, lo que indica oportunidades de mejora en la oferta.
- Los outliers de uso alto se consideran casos reales de alto consumo y no errores de registro.

## 📁 Estructura del repositorio
- `S7-Project-ConnectaTel.ipynb`: Notebook principal con todo el análisis.
- `datasets/users_latam.csv`: Información de clientes y planes.
- `datasets/usage.csv`: Registros de uso de llamadas y mensajes.
- `datasets/plans.csv`: Detalle de planes disponibles.

## 🛠️ Cómo usarlo
1. Abre el notebook `S7-Project-ConnectaTel.ipynb`.
2. Ejecuta las celdas en orden para reproducir el análisis.
3. Revisa la sección final de `Paso 7` para el insight ejecutivo y las recomendaciones.

## 💡 Recomendaciones comerciales
- Diseñar una oferta de migración para clientes `Básico` de alto uso.
- Evaluar un plan con más minutos y mensajes incluidos para reducir churn.
- Mejorar la calidad de los datos en `age` y `city` para futuros análisis estratégicos.

## ✅ Conclusión
Este repositorio demuestra cómo ConnectaTel puede transformar datos de uso en decisiones de negocio, con una segmentación sólida y recomendaciones específicas para impulsar retención y optimizar planes.
