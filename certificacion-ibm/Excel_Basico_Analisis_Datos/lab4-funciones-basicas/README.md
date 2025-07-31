# Laboratorio Práctico 4: Uso Simple de Funciones

** Tiempo estimado:** 30 minutos  
** Herramienta usada:** Excel para la web (versión gratuita)

---

## Objetivos del laboratorio

- Comprender los fundamentos de fórmulas y funciones en Excel.
- Aplicar cálculos simples y copiar fórmulas.
- Utilizar funciones comunes como `AVERAGE`, `MIN`, `MAX`, etc.
- Diferenciar referencias relativas, absolutas y mixtas.
- Identificar y manejar errores en fórmulas.

---

## Archivo utilizado

[`Personal_Monthly_Expenditure_Lab4.xlsx`](./Personal_Monthly_Expenditure_Lab4.xlsx)

---

## Actividades realizadas

### Ejercicio 1: Fundamentos de fórmulas

- Se sumaron los valores de la fila con:  
  `=SUM(B2:B13)`
- La fórmula se copió horizontalmente de B14 a G14.
- Se sumaron los gastos mensuales:  
  `=SUM(B2:G2)` en la columna **H**.
- Se aplicó formato de número contable ($) de B2 a H14.

---

### 🔧 Ejercicio 2: Funciones básicas y estadísticas

- Se usaron funciones comunes con rangos B2:B13 (y se copiaron hasta la columna G):

| Celda     | Fórmula utilizada           |
|-----------|-----------------------------|
| B16:G16   | `=AVERAGE(B2:B13)`         |
| B17:G17   | `=MIN(B2:B13)`           |
| B18:G18   | `=MAX(B2:B13)`           |
| B19:G19   | `=COUNT(B2:B13)`           |
| B20:G20   | `=MEDIAN(B2:B13)`          |

- Se exploraron otras funciones desde: **Autosuma > Más funciones...**

---

### Ejercicio 3: Referencias de celdas y errores

- **Referencias relativas**:  
  `=A31+A32` en B33, arrastrado hasta B40.

- **Referencias absolutas**:  
  `=$A$31+$A$32` en C33, arrastrado hasta C40.

- **Referencias mixtas**:  
  `=$A$31+A32` en D33, arrastrado hasta D40.

- **Manejo de errores**:  
  Se provocó un error `#¡VALOR!` en `=A16+A17` (celda B31).  
  Se consultó el asistente de ayuda desde el icono de advertencia.

---

## Conocimientos adquiridos

- Crear y copiar fórmulas de forma eficiente.
- Usar funciones estadísticas básicas en hojas de cálculo.
- Distinguir entre tipos de referencias en fórmulas.
- Identificar errores comunes y usar herramientas de ayuda de Excel.

---

## Notas

>  Este laboratorio fue realizado como parte de la **Certificación de Análisis de Datos de IBM**.  
>  Excel utilizado: Excel para la web (versión gratuita).
