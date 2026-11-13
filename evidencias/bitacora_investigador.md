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
* **Facturación Bruta (Sin filtrar):** `42.430 €`
* **Facturación Neta Real (Solo Completadas):** `29.905 €`
* **Fuga Financiera (Canceladas + Devueltas):** `37.705 €`
* **Conclusión de Negocio:** ¿Por qué no debemos tomar decisiones con la facturación bruta?

---

## 5. 🔮 Auditoría Final e IA Generativa (Puerta 6 - Jupyter & Prompting)
* **Número de duplicados exactos eliminados:** `...`
* **Respuesta de la LLM tras enviar el Prompt Estructurado:**
  > [Pegar aquí la síntesis generada por la IA]
* **Verificación de Factualidad y Sesgos (Guardrails):**
  - ¿La IA inventó algún dato que no estuviera en el contexto? (Sí/No y detalle):
  - ¿El lenguaje utilizado es neutro y libre de sesgos de culpabilidad?

---

## 🏁 Semáforo de Autoevaluación Individual
* **Piloto:** 🟢 Verde / 🟡 Amarillo / 🔴 Rojo — *Comentario:*
* **Copiloto:** 🟢 Verde / 🟡 Amarillo / 🔴 Rojo — *Comentario:*