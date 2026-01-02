# west-ham-coach-selection-sql
# ⚒️ El entrenador ideal para el West Ham United

## 📌 Descripción del proyecto

Este proyecto analiza, mediante **consultas SQL**, si el problema estructural del West Ham United es de **plantilla, mercado o contexto táctico**, y concluye qué **perfil de entrenador** encaja mejor para romper el bucle deportivo–económico del club.

El enfoque simula el trabajo de un **departamento de data football**, utilizando únicamente datos estructurales (plantilla, valores de mercado y transferencias), sin métricas de rendimiento en campo.

---

## 🎯 Objetivo

* Diagnosticar el estado real del West Ham United
* Identificar ineficiencias en el mercado de fichajes
* Evaluar el potencial de revalorización de la plantilla
* Traducir los resultados a un **perfil realista de entrenador**
* Simular el **impacto económico** de dicho entrenador

---

## 🗂️ Dataset utilizado

Base de datos MySQL: `football_db`

Tablas analizadas:

* `players` → información estructural de la plantilla
* `player_valuations` → evolución histórica del valor de mercado
* `transfers` → fichajes, ventas y balance económico

> ⚠️ Limitación consciente: no se utilizan estadísticas deportivas (goles, minutos, xG). El análisis se centra en **estructura, valor y estrategia**.

---

## 🧠 Metodología

El proyecto se divide en 4 bloques analíticos:

1. **Diagnóstico de plantilla**
   Edad media, distribución por posiciones y concentración de valor

2. **Análisis de desarrollo y depreciación**
   Comparación entre valor actual y máximo histórico de los jugadores

3. **Política de mercado**
   Evaluación del gasto neto por temporada y eficiencia en fichajes

4. **Simulación de impacto económico del entrenador**
   Escenarios basados en revalorización de activos y reducción de gasto

Cada conclusión está respaldada por **consultas SQL reproducibles**.

---

## 📊 Principales conclusiones

### 🔹 Diagnóstico del club

* Plantilla **madura (~30 años de media)**
* Alto valor concentrado en **mediocampo y ataque**
* Muchos jugadores **muy por debajo de su pico de mercado**
* Déficits recurrentes en el balance de fichajes

👉 El problema no es la falta de talento ni de inversión, sino el **contexto táctico**.

---

## 🧩 Perfil de entrenador ideal (data-driven)

Según los datos, el West Ham necesita un entrenador que sea:

✅ Desarrollador de talento
✅ Con sistema ofensivo reconocible
✅ Capaz de revalorizar jugadores técnicos
✅ Menos dependiente de fichajes caros

❌ No resultadista defensivo
❌ No gestor de veteranos
❌ No fútbol reactivo puro

---

## 👔 Traducción a entrenadores reales

Entrenadores que encajan con el perfil extraído:

* **Roberto De Zerbi** → máxima revalorización de activos
* **Rúben Amorim** → sistema claro + control económico
* **Unai Emery** → mejora individual y estabilidad
* **Xabi Alonso** → desarrollo táctico y valor de mercado

---

## 💰 Simulación de impacto económico

Se modelaron tres escenarios:

| Escenario     | Impacto estimado (2 temporadas) |
| ------------- | ------------------------------- |
| Resultadista  | +20–25 M€                       |
| Equilibrado   | +70–90 M€                       |
| Desarrollador | **+130–190 M€**                 |

📌 Conclusión: el cambio de entrenador es una **inversión estratégica**, no un coste.

---

## 🧪 Tecnologías

* MySQL
* SQL (queries analíticas)
* Análisis estratégico de fútbol

---

## 🚀 Cómo usar este proyecto

1. Importar las tablas en MySQL
2. Ejecutar las consultas SQL incluidas
3. Analizar los resultados por bloque
4. Comparar escenarios de entrenador

---

## 📝 Limitaciones

* Sin datos tácticos ni de rendimiento
* Supuestos explícitos en la simulación económica
* Enfoque estratégico, no predictivo

---

## 📌 Conclusión final

> *El West Ham United no necesita gastar más para competir mejor; necesita un entrenador que convierta talento existente en valor deportivo y económico.*

---

## 👤 Autor

Proyecto creado como **portfolio de data football aplicado a decisiones reales de club**.

---

Si tienes feedback o quieres ampliar el modelo (KPIs, comparativas entre clubes, scouting), este proyecto está pensado para escalar.
