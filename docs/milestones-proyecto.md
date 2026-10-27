# Milestones

## M0. Problema de la HU1 en código

### Producto

Código incorporado al repositorio que expresa el problema de la HU1 con los
mismos términos que usa la HU1, sin implementar ningún comportamiento.
Es la base sobre la que el M1 añadirá la lógica y sus tests.

### Validez

- La HU1 se analiza siguiendo el método DDD, y cada problema que surge
  del análisis se plantea en un issue enlazado a la HU1.
- Cada cambio responde a uno de esos issues, y cada commit referencia el issue
  que trata. Se comprueba en el historial del repositorio.
- El pull request lo revisa el autor del problema, como product manager, y lo
  acepta solo si con ese código se puede expresar el caso de Pablo descrito en
  la HU1, incluida la pareja de Análisis Funcional rechazada, sin añadir nada
  que la HU1 no recoja.

## M1. Lógica de la HU1 con tests

### Producto

Código incorporado al repositorio que, sobre la base del M0, ofrece una
primera solución para el problema de la HU1, junto con los tests que la
comprueban.

### Validez

- Cada cambio responde a un issue enlazado a la HU1, y cada commit referencia el
  issue que trata. Se comprueba en el historial del repositorio.
- Los tests se ejecutan automáticamente y deben pasar todos. Se basan en el
  caso de Pablo descrito en la HU1.
- Los tests incluyen parejas de asignaturas reales, sacadas de las guías que
  cita la HU1: unas claramente equivalentes y otras sin relación, y comprueban
  que se distinguen correctamente.
