# 📚 TI Documentation

Repositorio centralizado de documentación técnica y operativa de sistemas empresariales.

---

# 🎯 Objetivo

Centralizar procedimientos técnicos, troubleshooting, validaciones operativas, incidencias y documentación funcional relacionada con:

- Facturación electrónica
- SUNAT
- SQL Server
- Db2
- Procesos batch
- Integraciones
- Administración de personal
- Validaciones operativas
- Monitoreo de servicios

---

# 🏢 Empresas Documentadas

| Empresa | Área               | Descripción                          |
| ------- | ------------------ | ------------------------------------ |
| SIGNIA  | Facturación        | Procesos SUNAT, bajas y validaciones |
| HREPS   | Facturación        | Cuadres, retenciones y correcciones  |
| KURA    | Facturación / RRHH | Facturación, EFILE y procesos ADAM   |

---

# 📂 Índice General

## SIGNIA

- [Proceso de baja de sistemas](docs/signia/baja-sistemas.md)
- [Error 2128 - ResponseCode](docs/signia/error-2128-responsecode.md)
- [Otros casos](docs/signia/otros-casos.md)

---

## HREPS

- [Cuadre de facturas](docs/hreps/cuadre-facturas.md)
- [Anulación de retenciones](docs/hreps/anulacion-retenciones.md)
- [Descuadre de facturas - Error 3307](docs/hreps/descuadre-facturas-3307.md)
- [Proceso de baja de sistemas](docs/hreps/baja-sistemas.md)
- [Otros casos](docs/hreps/otros-casos.md)

---

## KURA

- [Facturas en estado 1](docs/kura/facturas-estado-1.md)
- [Notas de crédito estado 9](docs/kura/notas-credito-estado-9.md)
- [Proceso de baja de sistemas](docs/kura/baja-sistemas.md)
- [Eliminación de trabajadores](docs/kura/eliminacion-trabajadores.md)
- [Recarga EFILE](docs/kura/recarga-efile.md)
- [Procesos encolados](docs/kura/procesos-encolados.md)
- [Otros casos](docs/kura/otros-casos.md)

---

# 🧩 Procedimientos Generales

- [Estados SUNAT](docs/procedimientos-generales/estados-sunat.md)
- [Validaciones](docs/procedimientos-generales/validaciones.md)
- [Troubleshooting](docs/procedimientos-generales/troubleshooting.md)
- [Logs y monitoreo](docs/procedimientos-generales/logs-y-monitoreo.md)

---

# 🗄 SQL y Base de Datos

- [Stored Procedures](docs/sql/stored-procedures.md)
- [Queries útiles](docs/sql/queries-utiles.md)
- [Validaciones DB](docs/sql/validaciones-db.md)

---

# 🖥 Infraestructura y Servidores

- [Rutas de logs](docs/servidores/rutas-logs.md)
- [Servicios](docs/servidores/servicios.md)
- [Accesos](docs/servidores/accesos.md)

---

# ⚠️ Consideraciones

- Validar siempre estados SUNAT antes de reiniciar documentos.
- Documentar cualquier intervención manual.
- Mantener respaldo de XML y CDR.
- No ejecutar DELETE/UPDATE en producción sin validación previa.

---

# 🚀 Tecnologías

- Git
- GitHub Pages
- MkDocs
- Material for MkDocs
- Markdown

---

# 👨‍💻 Autor

Repositorio mantenido por el área TI.
