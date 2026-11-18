# SIGELL
Sistema de Gestión Legal de Litigios

# Sistema de Gestión de Litigios Masivos, Provisión Contable de Contingencias y Procuración Judicial (Proyecto #22)

Plataforma corporativa para la administración integral de expedientes judiciales masivos, cálculo automatizado de plazos fatales multijurisdiccionales, valoración de provisiones contables bajo norma NIC 37 / IFRS y gestión de acuerdos transaccionales.

## Arquitectura del Sistema
* **Frontend:** Next.js + Tailwind CSS
* **Backend:** Node.js / Supabase
* **Base de Datos:** PostgreSQL
* **Automatización:** n8n (Alertas de plazos fatales y reportes periódicos)
* **Inteligencia Artificial:** [Nombre del modelo elegido] (Clasificación de riesgo procesal y resumen de actuaciones)
* **Despliegue:** Vercel

## Equipo de Desarrollo (UNEG - Ingeniería de Software I)
* **Eliuber Gonzalez** – Líder de Proyecto, Integración de IA y Documentación (`feature/ia-documentacion`)
* **Manuel Jaimes** – Desarrollo Frontend UI/UX (`feature/frontend-ui`)
* **Soriannys Lugo** – Desarrollo Backend y Base de Datos (`feature/backend-db`)
* **Orlando Cabrera** – Automatización n8n y DevOps (`feature/automatizacion-devops`)

## Guía de Instalación (Setup)

1. Clonar el repositorio:
   \`\`\`bash
   git clone https://github.com/TU-USUARIO/proyecto-22-litigios-masivos.git
   cd proyecto-22-litigios-masivos
   \`\`\`
2. Instalar dependencias:
   \`\`\`bash
   npm install
   \`\`\`
3. Configurar variables de entorno:
   Duplicar el archivo `.env.example` como `.env.local` y completar las credenciales de Supabase, API de IA y Webhooks de n8n.
4. Ejecutar en entorno local:
   \`\`\`bash
   npm run dev
   \`\`\`

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
