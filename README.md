# flow
Graficos ontológicos inteligentes con IA
# 📘 Proyecto: Ontología y Revisión Semántica sobre Crecimiento Económico

## 🔍 Descripción general

El objetivo es construir una base de conocimiento interoperable que sirva tanto para el análisis académico como para aplicaciones web semánticas, científicas.

- Revisión de literatura científica (última década)
- Identificación y modelado de relaciones entre conceptos clave: *Economic Agent*, *Financier*, *Bank*
- Representaciones gráficas y ontológicas (draw.io, RDF/XML, JSON-LD)
- Herramientas para visualización, vinculación y análisis semántico


---

## 🧠 Estructura conceptual
Ejemplo:
[ECONOMIC AGENT]
|
+-- [FINANCIER] (subclase)
|
+-- [BANK] (subclase o tipo específico de Financier)
Jerarquía de clases:

Economic Agent └── Financier └── Bank


Relaciones ontológicas modeladas:

- `Financier → EconomicGrowth` (*supports*)
- `Bank → CentralBank` (*isRegulatedBy*)

---

## 📂 Contenido del repositorio

/docs └── revision_literatura.md ← Revisión académica (Scopus, WoS, etc.) /ontology ├── economic_growth.rdf ← Ontología RDF/XML ├── economic_growth.jsonld ← Ontología JSON-LD └── economic_growth.drawio ← Diagrama visual (importable en draw.io) /visualizations └── economic_growth.png ← Imagen del mapa conceptual README.md

---

## 🔧 Tecnologías y herramientas utilizadas

- 🧩 [draw.io / diagrams.net](https://app.diagrams.net)
- 💡 [Protégé](https://protege.stanford.edu/) (para extensión OWL/RDF)
- 🌐 RDFa, JSON-LD (marcado semántico para web)
- 📚 Scopus, Web of Science, Google Scholar (para revisión de literatura)
- 📊 GitHub (para versionado y documentación)

---

## ✍️ Contribuciones y seguimiento

Este proyecto es resultado de un proceso de colaboración continua entre el autor y [ChatGPT](https://openai.com/chatgpt), en donde se han integrado capacidades de procesamiento académico, modelado semántico y escritura científica.

📌 **Para continuar la colaboración**:
- Vincular nuevos papers o términos a la ontología.
- Ampliar la revisión académica con nuevas fuentes o hipótesis.
- Desplegar la ontología en endpoints SPARQL u otras plataformas semánticas.

---

## 📄 Licencia

Este repositorio se encuentra bajo una licencia abierta Creative Commons (CC BY 4.0), permitiendo su uso y adaptación con atribución.

---

## 🙌 Créditos

Desarrollado por [CyTA] junto a ChatGPT (OpenAI)  
Con el soporte semántico y visual de herramientas libres y estándares de la Web Semántica.

