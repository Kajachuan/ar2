# Aprendizaje por refuerzo en `highway-v0`

Este repositorio contiene el trabajo final de Aprendizaje por Refuerzo II aplicado al entorno `highway-v0` de `highway-env`. El objetivo es entrenar agentes capaces de conducir en una autopista con tráfico, maximizando la recompensa por avanzar a buena velocidad y evitando colisiones.

Se comparan tres enfoques:

- PPO con acciones discretas.
- PPO con acciones continuas.
- SAC con acciones continuas.

## Contenido

- `train-highway-*.ipynb`: notebooks de entrenamiento de cada agente.
- `grafico-*.ipynb`: notebooks usados para generar los gráficos de convergencia.
- `video-*.ipynb`: notebooks usados para grabar los videos de evaluación.
- `highway-v0-PPO-D/`, `highway-v0-PPO-C/`, `highway-v0-SAC/`: resultados de cada experimento, incluyendo logs, modelos entrenados, gráficos y videos.

## Resultados

Los tres agentes aprenden políticas funcionales, pero las acciones continuas permiten un control más fino del vehículo. En los experimentos realizados, SAC obtuvo la mayor recompensa final, seguido por PPO con acciones continuas y luego PPO con acciones discretas.
