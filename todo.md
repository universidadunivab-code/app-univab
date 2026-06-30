# UNIVAB Mobile App - TODO

## Formulario de Preinscripción

### Estructura de Datos
- [x] Crear archivo de carreras (careers.ts)
- [x] Crear archivo de departamentos y municipios de Bolivia (boliviaData.ts)
- [x] Validar datos de los 9 departamentos y sus municipios

### Base de Datos
- [x] Actualizar esquema drizzle para tabla preInscriptions (eliminar cedula, email, message)
- [x] Generar y aplicar migración SQL

### Frontend - Formulario
- [x] Eliminar campo Cédula de Identidad
- [x] Eliminar campo Correo Electrónico
- [x] Eliminar campo Mensaje Opcional
- [x] Implementar campo Nombre Completo
- [x] Implementar campo Teléfono
- [x] Implementar menú desplegable Carrera de Interés
- [x] Implementar menú desplegable Departamento (9 departamentos de Bolivia)
- [x] Implementar menú desplegable Municipio (dependiente del departamento)
- [x] Implementar selector Modalidad de Estudio (Presencial, Híbrida, Virtual)
- [x] Validación de formulario (solo 6 campos requeridos)

### Backend - Sincronización Google Sheets
- [x] Actualizar procedimiento syncToGoogleSheets (eliminar cedula, email, message)
- [x] Actualizar mapeo de columnas: 'Nombre Completo', 'Teléfono', 'Carrera', 'Departamento', 'Municipio', 'Modalidad'
- [x] Validar integración con credenciales GOOGLE_SHEETS_CREDENTIALS
- [x] Verificar función ensureHeadersInSheets con nuevas columnas

### Backend - Redirección WhatsApp
- [x] Implementar lógica de redirección a wa.me/59178211414
- [x] Incluir datos del estudiante en mensaje pre-cargado
- [x] Validar formato del mensaje

### Estilos Visuales
- [x] Aplicar paleta de colores: Guindo (#7B1034), Azul Oscuro (#1A237E), Blanco (#FFFFFF)
- [x] Actualizar index.css con variables CSS de la paleta
- [x] Aplicar colores consistentes en toda la interfaz
- [x] Diseñar página de contacto/preinscripción con paleta

### Pruebas
- [x] Crear pruebas unitarias para validación de formulario
- [x] Crear pruebas para sincronización con Google Sheets
- [x] Crear pruebas para redirección a WhatsApp
- [x] Ejecutar suite de pruebas (pnpm test)

### Configuración
- [x] Solicitar credenciales de Google Sheets al usuario
- [x] Configurar variable de entorno GOOGLE_SHEETS_CREDENTIALS
- [x] Validar funcionamiento end-to-end (pruebas de Google Sheets creadas)

### Logotipo e Integración Visual
- [x] Subir logotipo de UNIVAB a almacenamiento
- [x] Crear componente Header con logotipo y animación fade-in
- [x] Integrar Header en página de contacto
- [x] Integrar Header en página de inicio
- [x] Aplicar paleta de colores consistente en todo el sitio

### Carreras Unificadas
- [x] Expandir lista de carreras a 13 opciones
- [x] Actualizar formulario con 13 carreras
- [x] Mostrar 13 carreras en página de inicio

### Página de Inicio Mejorada
- [x] Crear landing page con logotipo UNIVAB
- [x] Sección hero con call-to-action
- [x] Sección de características
- [x] Sección de carreras con grid responsivo
- [x] Sección CTA final
- [x] Footer con información de contacto

### Finalización
- [x] Ejecutar todas las pruebas (11 pruebas pasando)
- [x] Verificar responsive design
- [x] Preparar proyecto para publicación final

## Completado
- [x] Proyecto inicializado con webdev_init_project
- [x] Estructura de datos de carreras y municipios
- [x] Esquema de base de datos actualizado
- [x] Formulario frontend con 6 campos exactos
- [x] Backend con sincronización a Google Sheets
- [x] Redirección a WhatsApp con mensaje pre-cargado
- [x] Paleta de colores aplicada (guindo, azul oscuro, blanco)
- [x] Pruebas unitarias creadas y ejecutadas
- [x] Logotipo UNIVAB integrado con animación fade-in
- [x] 13 carreras unificadas en el sistema
- [x] Página de inicio profesional y completa
- [x] Proyecto finalizado y listo para publicación


## Ajustes Finales - Instrucción Final Completados

### Correcciones de Diseño
- [x] Z-index de menús desplegables corregido (z-50)
- [x] Etiqueta "Carrera de Interés" cambiada a "Carrera"
- [x] Botón "Iniciar Sesión" reemplazado por "Propuesta Académica" con scroll automático

### Catálogo Informativo Profundo
- [x] Componente CareerDetailModal creado
- [x] Vistas detalladas con 4 pestañas: Perfil, Campo Laboral, Modalidad, Malla
- [x] Perfiles académicos profesionales para cada carrera
- [x] Campos laborales nacionales e internacionales
- [x] Modalidades de estudio (Presencial, Híbrida, Virtual)
- [x] Mallas curriculares modernas año/semestre con titulación intermedia

### Nuevo Orden Institucional (13 Carreras)
- [x] Medicina (Anual, 5 años) - Posición 1
- [x] Enfermería (Semestral, Técnico Medio) - Posición 2
- [x] Fisioterapia y Kinesiología (Semestral, Técnico Superior) - Posición 3
- [x] Ingeniería de Sistemas - Posición 4
- [x] Ingeniería Biomédica - Posición 5
- [x] Ingeniería en AgroBiotecnología - Posición 6
- [x] Ingeniería Agropecuaria - Posición 7
- [x] Ingeniería Civil - Posición 8
- [x] Ingeniería en Gestión Empresarial - Posición 9
- [x] Ingeniería en Energías Renovables - Posición 10
- [x] Psicopedagogía - Posición 11
- [x] Turismo - Posición 12
- [x] Técnico Superior en Gastronomía - Posición 13 (Final)

## Reestructuración Definitiva - Instrucción Maestra

### Identidad Institucional
- [x] Cambiar nombre a "Universidad Nacional de la Integración del Valle Bajo (UNIVAB)"
- [x] Actualizar lema: "Propuesta Académica para la Nueva Universidad Pública de Cochabamba"
- [x] Cambiar frase de bienvenida: "Apoya la creación de la nueva universidad pública de Cochabamba"
- [x] Eliminar referencias a "universidad virtual de américa"

### Mallas Curriculares y Perfiles
- [x] Medicina: Plan ANUAL, 5 años, con Informática Médica, Telemedicina, Genética Clínica, Simulación
- [x] Enfermería: Licenciatura con titulación intermedia (Técnico Universitario Medio) al 2do año
- [x] Técnico Superior en Gastronomía: Plan 3 años, alta cocina, innovación alimentaria
- [x] Turismo: Semestral con titulación intermedia (Técnico Universitario Superior) al 3er año
- [x] Fisioterapia y Kinesiología: Semestral con titulación intermedia
- [x] Psicopedagogía: Semestral con titulación intermedia
- [x] Ingeniería de Sistemas: Semestral con titulación intermedia, IA, Ciencia de Datos
- [x] Ingeniería Biomédica: Semestral con titulación intermedia
- [x] Ingeniería en AgroBiotecnología: Semestral con titulación intermedia
- [x] Ingeniería Agropecuaria: Semestral con titulación intermedia
- [x] Ingeniería Civil: Semestral con titulación intermedia
- [x] Ingeniería en Gestión Empresarial: Semestral con titulación intermedia
- [x] Ingeniería en Energías Renovables: Semestral con titulación intermedia

### Modelo Educativo UNIVAB
- [x] Reemplazar sección "Por qué elegir UNIVAB" con nuevo texto
- [x] Implementar bloque de modelo educativo con 6 pilares
- [x] Crear componente interactivo para mostrar mallas curriculares
- [x] Agregar perfiles profesionales para cada carrera
- [x] Agregar campos laborales para cada carrera

### Identidad Visual
- [x] Verificar paleta de colores: Azul marino oscuro, Guindo, Blanco
- [x] Actualizar encabezado con logotipo y animación fade-in
- [x] Aplicar colores consistentemente en toda la interfaz

### Sincronización Google Sheets
- [x] Configurar credenciales para universidadunivab@gmail.com
- [x] Verificar mapeo de columnas exactas
- [x] Probar sincronización end-to-end

### Flujo WhatsApp
- [x] Actualizar número de WhatsApp correcto
- [x] Verificar mensaje de confirmación con carrera y modalidad
