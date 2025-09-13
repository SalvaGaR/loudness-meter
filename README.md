# 🎚️ Medidor de Nivel y Dinámica (LUFS / True Peak)

Medidor de sonoridad y dinámica conforme a **ITU-R BS.1770-4 / EBU R128**, ideal para análisis de mezclas, másteres y contenidos broadcast/streaming.  

## ✨ Características
- **LUFS integrado (I)** con gating ITU-R.
- **Momentary (M, 400 ms)** y **Short-term (S, 3 s)** con máximos y tiempos.
- **Loudness Range (LRA)** en LU.
- **True Peak (dBTP)** estimado por oversampling 4×.
- **PLR (Peak-to-Loudness Ratio)** y rango dinámico aproximado (P95-P5 de LUFS-S).
- **CLI** para análisis rápido y exportación a JSON/CSV.
- **App Streamlit** con métricas y gráficas interactivas.
- Soporta WAV, FLAC, AIFF, remuestreo y mezcla a mono opcional.
- Licencia **MIT**.

## 🚀 Instalación
```bash
git clone https://github.com/SalvaGaR/loudness-meter.git
cd loudness-meter
pip install -r requirements.txt
