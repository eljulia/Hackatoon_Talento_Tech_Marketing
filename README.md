# 🚀 VisualBit AI | Sistema de Inteligencia de Clientes  
### Hackathon Quindío 2025  
Solución tecnológica para la desconexión entre Marketing y Ventas.
ENLACE SOLUCION EN FOIREBASE
https://8501-firebase-api-1763743222195.cluster-dwvm25yncracsxpd26rcd5ja3m.cloudworkstations.dev/

---

## 💡 El Problema

Las agencias de marketing digital generan miles de leads, pero enfrentan una crisis de eficiencia:

- **Desperdicio:** Los equipos de ventas pierden hasta **60% del tiempo** contactando leads "fríos".  
- **Ceguera:** No saben cuánto vale realmente un cliente potencial (**LTV**).  
- **Fuga (Churn):** El **40% de los clientes** abandona antes de que la agencia detecte su insatisfacción.

---

## 🤖 Nuestra Solución: Inteligencia Híbrida

Creamos un ecosistema que integra Chatbots de Captación, Machine Learning y Reglas de Negocio para atacar el problema en **3 frentes simultáneos**:

1. **Filtrado Inteligente:** Clasificación automática de leads en tiempo real.  
2. **Retención Predictiva:** Predicción de fuga (Churn) antes de que suceda.  
3. **Valoración Monetaria:** Estimación del LTV (Valor de Vida del Cliente).

---

## 🧠 Arquitectura de Modelos (El Cerebro)

El sistema utiliza **3 modelos de Machine Learning** entrenados con datos históricos reales:

| Modelo      | Algoritmo                | Función                                          | Estado / Performance      |
|-------------|---------------------------|--------------------------------------------------|---------------------------|
| Modelo A    | Random Forest Classifier | Clasifica leads en: Caliente / Tibio / Frío     | Híbrido ML + Reglas       |
| Modelo B    | Random Forest Classifier | Predice riesgo de abandono (Churn)              | **100% Accuracy** 🌟       |
| Modelo C    | Random Forest Regressor  | Estima el valor monetario futuro (LTV)          | RMSE Optimizado           |

### 🔎 Nota Técnica  
Para el **Modelo A**, aplicamos una capa de *Inteligencia Híbrida*:  
las reglas de negocio (ej. “presupuesto alto = prioridad”) sobrescriben la predicción cuando es necesario, garantizando mayor confiabilidad en la demo.

---

## 🛠️ Stack Tecnológico

- **Frontend / UI:** Streamlit (Dashboards interactivos en minutos).  
- **Backend & Datos:** Firebase Firestore (NoSQL en tiempo real) + Pandas.  
- **Ingeniería de Datos:** Limpieza, normalización y merge de datasets.  
- **Despliegue:** Local, optimizado para una demo de hackathon.

---

## 📂 Estructura del Proyecto
<img width="842" height="424" alt="image" src="https://github.com/user-attachments/assets/9076ee84-82ca-4f2e-a8df-e5715410f707" />


---

## 🚀 Instrucciones de Ejecución (Quick Start)

Levanta el MVP completo en **menos de 2 minutos**:

### 1️⃣ Clonar el repositorio
```bash
git clone <url-del-repo>
cd hackathon_visualbit_ai
streamlit run app.py
