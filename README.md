# 🎓 Instituto Physics — Sistema de Evaluación Vocacional

Plataforma web gratuita de orientación vocacional para bachillerato, basada en instrumentos psicométricos validados en Ecuador.

## ⚡ Uso rápido (GitHub Pages)

1. Haz fork de este repositorio
2. Ve a **Settings → Pages → Branch: main → / (root)**
3. Accede a `https://[tu-usuario].github.io/[repositorio]/`

## 📋 Estructura de la evaluación (160 ítems)

| Módulo | Ítems | Tiempo | Tipo |
|--------|-------|--------|------|
| RIASEC — Intereses vocacionales | 40 | ~10 min | Likert 1-5 |
| CHASIDE — Áreas profesionales | 56 | ~18 min | Likert 1-5 |
| DAT Verbal | 15 | ~12 min | Opción múltiple |
| DAT Numérico | 15 | ~14 min | Opción múltiple |
| DAT Abstracto | 12 | ~10 min | Opción múltiple |
| DAT Espacial | 12 | ~10 min | Opción múltiple |
| Control (distribuido) | 10 | integrado | Mixto |
| **TOTAL** | **160** | **~75 min** | |

## 📦 Bancos de preguntas (626 ítems totales — ratio 4:1)

Todos los ítems son de **autoría original del Instituto Physics** — riesgo legal nulo.

## 💾 Archivos de salida

- `resultado_[ID]_[FECHA].json` — Datos completos para procesamiento Python
- `resultado_[ID]_[FECHA].csv` — Registro plano para la secretaría

## 🐍 Procesamiento Python (Google Colab)

Próximamente: notebook `colab/generar_informes.ipynb`

## 📁 Agregar preguntas al banco

Edita cualquier archivo en `/data/banco_*.json` y agrega ítems siguiendo la estructura existente. El sistema los detecta automáticamente.

---
Instituto Physics — Quito, Ecuador — 2026
