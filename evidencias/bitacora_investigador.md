# 📝 Bitácora de Investigación - Gran Hotel Olimpo
**Equipo Auditor:** [Bethsabe Balza] & [Tania Graff]  
**Fecha:** [13/11/2026]

---

## 1. 🔑 Hallazgo Inicial (Puerta 1 - Git Bash)
* **Comando utilizado para encontrar la credencial oculta:** 
cat .llave_maestra.txt
* **Código de la Llave Maestra:** `GH-OLIMPO-DATA-2026-KEY`
* **Primera anomalía detectada en el servidor:**  
  Revisando la carpeta `data/reservas_raw.csv`, hemos descubierto que el atacante 
  introdujo 10 FILAS TOTALMENTE DUPLICADAS e intencionadamente dejó celdas 
  vacías (NaN) en precios y noches.

---

## 2. 🛡️ Registro de Control de Versiones (Puerta 2 - Git & GitHub)
* **Comando para preparar archivos (Staging):** `git status`
* **Mensaje del primer commit local:** `Completamos Bitácora con Llave Maestra`
* **URL del repositorio público en GitHub:** `https://github.com/TaniaGraff/gran-hotel-data-escape.git`

---

## 3. 🗺️ Arquitectura y Entorno (Puerta 4 - VS Code & Dependencies)
* **Versión de Python detectada:** `3.11.5`
* **Comando utilizado para instalar `requirements.txt`:** `pip install -r`
* **Diferencia entre Ruta Absoluta y Ruta Relativa (explicación breve):**
La ruta absoluta es la dirección completa del archivo desde la raíz del ordenador. La ruta relativa, es una parte de la ruta, una de las carpetas. 

---

## 4. ⚙️ Conciliación Financiera (Puerta 5 - Python CLI)
* **Facturación Bruta (Sin filtrar):** `56.090 €`
* **Facturación Neta Real (Solo Completadas):** `29.055 €`
* **Fuga Financiera (Canceladas + Devueltas):** `27.035 €`
* **Conclusión de Negocio:** ¿Por qué no debemos tomar decisiones con la facturación bruta?
Porque la facturación bruta solo dice cuánto se vende, sin tener en cuenta las devoluciones o mermas.

---

## 5. 🔮 Auditoría Final e IA Generativa (Puerta 6 - Jupyter & Prompting)
* **Número de duplicados exactos eliminados:** `10`
* **Respuesta de la LLM tras enviar el Prompt Estructurado:**
  > Síntesis ejecutiva: Gran Hotel Olimpo
Base de datos depurada: de los 100 registros brutos iniciales se han eliminado 10 duplicados. El análisis se apoya ahora en 90 registros únicos, una base fiable para la toma de decisiones.
Facturación real identificada: la facturación neta real, que corresponde únicamente a las reservas completadas, asciende a 29.055,00 €. Fuga cuantificada y aislada: las reservas canceladas o devueltas suman 27.035,00 €. Al separarlas de las completadas, la Dirección puede distinguir con claridad los ingresos efectivos de los que no llegaron a materializarse.
* **Verificación de Factualidad y Sesgos (Guardrails):**
  - ¿La IA inventó algún dato que no estuviera en el contexto? (Sí/No y detalle): No, especificó que solo usó las cifras del contexto, sin porcentajes ni métricas derivadas, y ha pasado los importes al formato español (punto para los miles, coma para los decimales). 
  - ¿El lenguaje utilizado es neutro y libre de sesgos de culpabilidad? Podría ser más neutro, la IA hace una interpretación de los datos.

---

## 🏁 Semáforo de Autoevaluación Individual
* **Piloto:** 🟢 Verde / 🟡 Amarillo / 🔴 Rojo — *Comentario:*
* **Copiloto:** 🟢 Verde / 🟡 Amarillo / 🔴 Rojo — *Comentario:*