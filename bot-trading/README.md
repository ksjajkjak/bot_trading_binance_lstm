# Bot de Trading Real para Binance Futures

Este bot opera con una estrategia basada en tendencia + confirmación técnica + modelo IA (LSTM).

## Archivos principales:
- `main.py`: ejecuta el bot
- `strategies/simple_lstm_strategy.py`: estrategia profesional
- `model/model_5m.tflite`: modelo IA entrenado
- `config.py`: configura tus claves API y parámetros

## Para desplegar en Render o Railway:
1. Crea un nuevo Web Service.
2. Sube esta carpeta completa.
3. Añade los secretos de entorno según config.py.
4. Ejecuta automáticamente cada X minutos.
