# Tratamiento de Audio — Experiencia SONIDO

**Asignatura:** Percepción Computacional  
**Autores:** Juan Diego Walteros Cortes y Julian Esteban Ballesteros  
**Docente:** Mónica María Fonseca Vigoya

## Objetivo
Implementar un flujo reproducible en Python para analizar una señal de voz, visualizarla en tiempo y frecuencia, reducir ruido mediante sustracción espectral y detectar actividad de voz mediante energía RMS.

## Archivos
- `Tratamiento_Audio_SONIDO.ipynb`: notebook ejecutado, compatible con Google Colab.
- `audio_entrada_ruidoso.wav`: señal usada como entrada del experimento reproducible.
- `audio_tratado.wav`: señal después de reducción de ruido.
- `audio_tratado_recortado.wav`: región útil detectada por VAD.
- `Informe_Resultados_Tratamiento_Audio_Walteros_Ballesteros.pdf`: informe final.

## Uso en Google Colab
1. Subir `Tratamiento_Audio_SONIDO.ipynb` a Google Drive o abrirlo desde GitHub.
2. Ejecutar las celdas en orden.
3. Mantener `MODO = "demo"` para reproducir exactamente los resultados del informe.
4. Cambiar a `MODO = "upload"` para cargar una grabación propia y aplicar el mismo flujo.

## Resultados principales del modo demo
- Frecuencia de muestreo: 16 kHz.
- Duración de entrada: 11,73 s.
- SNR antes: 0,17 dB.
- SNR después: 7,61 dB.
- Mejora de SNR: 7,44 dB.
- Región útil detectada: 10,23 s.
