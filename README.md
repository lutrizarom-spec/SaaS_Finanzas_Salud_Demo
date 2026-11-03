# SaaS Finanzas & Salud

Plantilla y dashboard premium en Excel para ordenar las finanzas personales y la salud de una persona o familia. Funciona con fórmulas, tablas y gráficos: no requiere macros, complementos ni servicios externos.

## Demo pública

[Descargar la demo](demo/SaaS_Finanzas_Salud_Demo.xlsx)

La demo usa datos ficticios y sirve para evaluar la estética, los dashboards y la navegación.

- 10 hojas: 9 funcionales más `LICENCIA`.
- 2 dashboards: `dash_finanzas` y `dash_vida`.
- 8 gráficos y 4 tablas.
- Datos de ejemplo de enero a marzo de 2026.
- `calc_finanzas` oculta.
- Todas las hojas protegidas como medida disuasiva.
- Sin datos financieros ni personales reales.

La demo es de visualización. No es la versión editable que se vende.

## Versión completa

El producto completo **no está en este repositorio**. Se entrega por separado como libro editable, sin datos de ejemplo y bajo licencia personal.

Para consultas de compra o soporte: [@lutrizarom-spec](https://github.com/lutrizarom-spec) en GitHub.

## Para qué sirve

- Registrar ingresos, gastos, ahorros y saldos iniciales en una sola tabla de movimientos.
- Separar el gasto real por categoría y compararlo con los ingresos.
- Seguir hábitos diarios y objetivos de descanso, energía y bienestar.
- Definir metas y controlar su avance.
- Revisar KPIs y gráficos en dos dashboards: finanzas y vida.
- Ajustar meta de ahorro, capitales y umbrales de riesgo sin tocar fórmulas.

## Atributos de la demo

| Atributo | Detalle |
|---|---|
| Formato | `.xlsx`, sin macros ni enlaces externos |
| Hojas | 10: 9 funcionales + `LICENCIA` |
| Dashboards | 2: `dash_finanzas` y `dash_vida` |
| Gráficos | 8 |
| Tablas | 4 |
| Navegación | 6 botones con vínculo en cada dashboard |
| Protección | 10/10 hojas protegidas; disuasión, no DRM |
| Datos | Ficticios, de enero a marzo de 2026 |
| Cálculo | Gastos reales, promedios, ratios y desglose por categoría |
| Configuración | `cfg_maestros` y `cfg_parametros` |
| Idioma | Español |
| Compatibilidad | Excel de escritorio Microsoft 365 o 2021 (usa `XLOOKUP` y `MINIFS`) |

## Estructura

| Hoja | Rol |
|---|---|
| `guia` | Instrucciones de uso. |
| `dash_finanzas` | KPIs, gráficos y desglose de gastos. |
| `dash_vida` | Indicadores de hábitos, descanso y metas. |
| `in_movimientos` | Registro de transacciones (`Tabla1`). |
| `in_jornada_habitos` | Registro diario de hábitos (`Tabla3`). |
| `in_metas` | Metas y seguimiento (`Tabla5`, `Tabla6`). |
| `calc_finanzas` | Motor de cálculo: gastos reales, promedios y ratios. Oculta en la demo. |
| `cfg_maestros` | Categorías y cuentas maestras. |
| `cfg_parametros` | Meta de ahorro, capitales y umbrales. |
| `LICENCIA` | Condiciones de uso de la demo. |

## Uso rápido

1. Descarga `demo/SaaS_Finanzas_Salud_Demo.xlsx`.
2. Ábrela con Excel de escritorio Microsoft 365 o 2021.
3. Si Excel la abre en vista protegida, habilita la edición para que funcionen los botones.
4. Recorre los dashboards con los botones de navegación.
5. Revisa la hoja `LICENCIA` para conocer los límites de la demo.

La demo está protegida sin contraseña. Para auditar fórmulas: **Revisar > Desproteger hoja**. La versión completa es la que se entrega editable.

## Requisitos

- Excel de escritorio Microsoft 365 o Microsoft 2021.
- No se recomienda Excel Online, Google Sheets ni LibreOffice.
- El archivo no usa macros, por lo que no necesitas habilitar contenido activo.

## Licencia

La licencia es **propietaria**. No es un proyecto de código abierto.

- La demo se permite para visualización personal y no comercial.
- El producto completo se rige por una licencia personal (`EULA.md`).
- No se permite revender, redistribuir ni usar comercialmente sin autorización escrita.

Documentos: [LICENSE](LICENSE) · [EULA](EULA.md) · [Términos de venta](TERMS.md) · [Privacidad](PRIVACY.md) · [Aviso legal](DISCLAIMER.md) · [Marcas](TRADEMARKS.md).

## Privacidad y datos

El libro funciona localmente. No tiene macros, telemetría ni conexiones a servicios del autor. Los datos que ingreses se quedan en tu equipo.

La demo pública contiene datos ficticios. No envíes datos reales en issues, correos o mensajes de soporte.

## Estado

- Demo verificada: 0 errores de fórmula, 8 gráficos, 4 tablas, 10/10 hojas protegidas.
- `calc_finanzas!D37` corregido en la demo con `CHAR(10)` y `DATE(YEAR(TODAY()),12,31)`.
- El libro completo no se publica en este repositorio; se entrega fuera de GitHub.

---

Mantenido por [@lutrizarom-spec](https://github.com/lutrizarom-spec).
