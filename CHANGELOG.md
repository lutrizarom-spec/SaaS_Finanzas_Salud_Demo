# Changelog

Todos los cambios relevantes de **SaaS Finanzas & Salud** se registran aquí.

## [1.0.1-demo] - 2026-11-03

### Cambiado

- `in_jornada_habitos`: los KPIs de vida del dashboard ahora se calculan con fórmulas en vez de valores fijos:
  - `AD8` Horas Sueño Promedio: promedio de (Hora Despertar − Dormir Meta).
  - `AD17` Cadena de Victoria: conteo de días con protocolo cumplido.
  - `AD18` Horas Estudio Acumuladas: suma de las horas de estudio registradas.
  - `AD19` Proficiencia Académica: nivel según el promedio de la proficiencia diaria.
- Alinea el comportamiento de la demo con la versión completa v2.0.

## [1.0.0-demo] - 2026-11-03

### Agregado

- Demo pública `demo/SaaS_Finanzas_Salud_Demo.xlsx` con datos ficticios.
- Hoja `LICENCIA` con condiciones de uso de la demo.
- Documentación legal: `LICENSE`, `EULA.md`, `TERMS.md`, `PRIVACY.md`, `DISCLAIMER.md`, `TRADEMARKS.md`, `CONTRIBUTING.md` y `SECURITY.md`.
- `demo/README.md` con alcance, requisitos y límites de la demo.
- `.gitignore` para evitar publicar libros privados.

### Cambiado

- `calc_finanzas!D37` corregido: usa `CHAR(10)` y `DATE(YEAR(TODAY()),12,31)`.
- La demo tiene las 10 hojas protegidas y `calc_finanzas` oculta.
- Formatos de horas de `in_jornada_habitos` corregidos en la demo.
- README actualizado para separar demo pública y producto completo privado.

### No publicado

- El libro completo con datos reales no forma parte de este repositorio.
- La demo no contiene datos financieros ni personales reales.
