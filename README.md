# Calculadora de fundaciones para postes de media tensión

Página web que dimensiona y verifica la fundación (bloque de hormigón) de postes de hormigón armado simples y dobles para líneas aéreas de media tensión (13,2 y 33 kV).

**Usarla online:** https://panchog11.github.io/calculadora-fundaciones-postes-mt/

## Qué hace

- Cargas según AEA 95301 (zona de referencia: Chaco), en tres modos:
  - calculadas desde la línea (conductores, vanos, viento, tipo de estructura);
  - fuerzas directas aplicadas en el poste;
  - reacciones en la base (N, V, M por poste), incluido el par de axiles en postes dobles.
- Verificación del poste (carga equivalente a 0,25 m de la cima, IRAM).
- Fundación por el método de Sulzberger, con dimensionado automático o verificación de medidas.
- Memoria de cálculo con el desarrollo de las fórmulas, exportable a Word (.docx).

## Archivos

- `index.html`: versión para GitHub Pages (la que se abre en el link).
- `Calculo_Fundaciones_Postes_MT.html`: archivo fuente. Para generar `index.html` se le agrega el encabezado HTML estándar.

## Advertencia

Los valores por defecto (velocidad de viento, factores de ráfaga, coeficiente del suelo, datos de postes y conductores) son de referencia. Verificalos con la normativa vigente, el estudio de suelos y los datos del fabricante antes de usar los resultados.
