# SIGELL
Sistema de Gestión Legal de Litigios

## Criterios Ágiles del Equipo (DoR y DoD)

### Definition of Ready (DoR)
Una Historia de Usuario puede pasar al Sprint Backlog únicamente cuando cumple con:
- [ ] Redacción completa bajo la estructura *Como [rol], quiero [funcionalidad], para [beneficio]*.
- [ ] Criterios de aceptación definidos en formato **Given-When-Then**.
- [ ] Estimación de esfuerzo asignada en **Story Points** (escala Fibonacci) y un integrante responsable asignado.

### Definition of Done (DoD)
Una Historia de Usuario se considera terminada (columna *Done*) cuando cumple con:
- [ ] Código implementado en su rama `feature/*` sin errores de compilación ni secretos expuestos.
- [ ] **Pull Request** abierto hacia `develop`, revisado y aprobado por al menos 1 compañero del equipo.
- [ ] Validación de entradas y manejo controlado de casos vacíos o errores básicos en la interfaz y el backend.
- [ ] Documentación técnica o evidencia visual actualizada si el cambio afecta la arquitectura o UI.
