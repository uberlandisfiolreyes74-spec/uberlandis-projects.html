# Uberlandis Fiol Reyes — Decision Science & AI Research

Investigador independiente en ciencia de decisiones, predicción de irreversibilidad, aprendizaje por refuerzo y sistemas autónomos.

---

## 🔒 LockGuard AI — Framework unificado

Plataforma de inteligencia de decisiones que integra predicción de lock‑in, optimización de utilidad ajustada por riesgo y gobernanza temporal con puertas de entropía.

| Métrica | Valor |
|---------|-------|
| **Accuracy** | 89% (AUC=0.90) |
| **Decisiones validadas** | 138 casos reales |
| **Cohen's κ (IRR)** | 0.78 |
| **Extensión de reversibilidad** | 150‑200% |

### Componentes principales

- **SMA-03 v3 — II‑Score**  
  Modelo predictivo de irreversibilidad con 13 variables. El metaprograma **R** (suposición de realidad) y la percepción de crisis **F<sub>D</sub>** explican el 84% de la varianza del lock‑in.

- **MSCA v6 — Utilidad ajustada por riesgo**  
  Evaluador de utilidad penalizado por varianza:  
  `U(a) = E[R(a)] - 2·Var[R(a)]`. Integrado con simulación Monte Carlo.

- **EGDS — Sistema de ejecución con puerta de entropía**  
  Gobernanza temporal con checkpoints en los días 7,30,60,90. La puerta de entropía (`θ_max = 1.2 nats`) suprime acciones irreversibles.

- **Dream Mode & Reality Gate**  
  Simulación pre‑ejecución de cuatro variantes de escenario (optimista, pesimista, altamente reversible, propenso a lock‑in) con memoria ponderada (peso 0.3 para los sueños). La Reality Gate recalibra el metaprograma R cuando la simulación diverge de la realidad observada.

---

## 📄 Publicaciones y envíos

| Estado | Revista / Destino | Notas / DOI |
|--------|------------------|--------------|
| **En revisión** | SN Computer Science (Springer) | Manuscrito SNCS‑D‑26‑03323 · correcciones completadas |
| **En revisión** | PeerJ Computer Science | Enviado en mayo de 2026 |
| **Preprint / Código** | Zenodo (RL+Transformer para ejecución de mercado + LockGuard) | [10.5281/zenodo.19961420](https://doi.org/10.5281/zenodo.19961420) |
| **Working paper** | The Simulation Imperative (marco conceptual) | Desacoplamiento perceptual, consolidación selectiva, reestructuración del campo psicológico |

---

## 🧠 Innovaciones clave

- **Metaprograma R** (0 = hipotético, 1 = real): modula la irreversibilidad y las puertas de ejecución.
- **Puerta de entropía EGDS**: suprime acciones cuando la entropía de la política > 1.2 nats.
- **Dream Mode**: simulación Monte Carlo pre‑ejecución de 4 variantes con memoria ponderada.
- **Reality Gate**: recalibración dinámica de R cuando la discrepancia entre simulación y realidad > 0.25.
- **Protocolo de fiabilidad entre evaluadores (IRR)**: Cohen's κ = 0.78 sobre 138 decisiones.

---

## 💻 Código y reproducibilidad

Todo el código fuente (encoder Transformer, entrenamiento PPO, adaptador de Binance, suite de visualización) está disponible en Zenodo:  
[**doi.org/10.5281/zenodo.19961420**](https://doi.org/10.5281/zenodo.19961420)

---

## 🌐 Enlaces

- [Landing page de LockGuard AI](https://lockguardai.carrd.co)
- [Portafolio personal](https://uberlandisfiolreyes74-spec.github.io/uberlandis.github.io/)
- [ResearchGate](#) (pendiente de actualizar)
- [GitHub](#) (este repositorio)

---

© 2026 Uberlandis Fiol Reyes — Licencia CC BY 4.0 para el código, derechos reservados para el contenido.
