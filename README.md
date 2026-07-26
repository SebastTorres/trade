# trade — journal de análisis de velas horarias

Repositorio de trabajo para las rutinas automatizadas de análisis intradía
(MU, TSLA, META, MSFT, SPY, QQQ, GOOGL, COIN). Genera ideas especulativas de
entrada (PUT/CALL) con fines informativos y de seguimiento — **no es
recomendación de inversión**. El desempeño pasado no garantiza resultados
futuros.

## Estructura

```
analysis/
  YYYY-MM-DD/
    hour1.md        # Tarea 1 — vela 6:30-7:30am PT
    hour2.md        # Tarea 2 — vela 7:30-8:30am PT, compara vs hour1
  weekly/
    YYYY-MM-DD.md    # Tarea 3 — resumen del viernes (fecha = viernes de esa semana)
```

Cada archivo debe incluir fecha, hora de generación y el rango exacto de la
vela usada, para que las tareas posteriores puedan recuperarlo con precisión.

## Tickers cubiertos
MU, TSLA, META, MSFT, SPY, QQQ, GOOGL, COIN
