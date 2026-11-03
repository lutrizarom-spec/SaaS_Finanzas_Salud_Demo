# Changelog

Todos los cambios relevantes de **SaaS Finanzas & Salud** se registran aquí.

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
