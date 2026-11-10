
# CONTEXT.md — Nexova

## 1. Identidad de la empresa

- Nombre: Nexova.
- Industria: Consultoría de recursos humanos y adquisición de talento.
- Fundación: 2011.
- Sede principal: Valencia, España.
- Oficina de expansión: Miami, Florida, Estados Unidos.
- Empleados: Aproximadamente 120.
- Facturación anual: Aproximadamente 8 millones de USD.
- Stakeholder: Carmen Ruiz, Head of Marketing.
- Departamento responsable: Marketing y Comunicaciones.

## 2. Descripción del negocio

Nexova es una consultora de recursos humanos especializada en ayudar a empresas medianas a encontrar, seleccionar, desarrollar y gestionar talento.

Opera principalmente con clientes de los siguientes sectores:

- Tecnología.
- Retail.
- Servicios financieros.

Sus tres líneas principales de negocio son:

### Headhunting Ejecutivo
- Búsqueda y selección de perfiles ejecutivos y mandos medios.
- Procesos personalizados.
- Garantía de reemplazo.

### Outsourcing de Atención al Cliente
- Equipos especializados para empresas tecnológicas.
- Formación continua.
- Supervisión dedicada.

### Formación Corporativa
- Programas de soft skills y liderazgo.
- Cursos presenciales y en línea.
- Formación adaptada a cada organización.

## 3. Objetivo del proyecto

Construir un nuevo sitio web público para Nexova que:

- Modernice su presencia digital.
- Presente profesionalmente sus servicios.
- Transmita confianza, experiencia y profesionalismo.
- Facilite el contacto con clientes potenciales.
- Permita registrar candidatos mediante un formulario estructurado.
- Mejore la accesibilidad, velocidad y posicionamiento SEO.

## 4. Alcance del sitio web

### Página principal — index.html

Debe incluir, en este orden:

1. Header con logo y navegación: Inicio, Servicios, Talento y Contacto.
2. Hero con el titular:
   "Construimos equipos excepcionales para empresas en crecimiento".
3. Subtítulo corporativo indicado en BRIEFING.md.
4. Botón de acción: "Únete a nuestro banco de talento".
5. Tres tarjetas de servicios.
6. Sección "Por qué Nexova".
7. Contacto de Valencia y Miami.
8. Footer con redes sociales.

### Página de registro — application.html

Debe permitir que profesionales interesados en oportunidades laborales registren sus datos.

Campos obligatorios:
- Nombre completo: mínimo dos palabras.
- Email: formato válido.
- Teléfono: código internacional y número.
- País de residencia: España, Estados Unidos u Otro.
- Años de experiencia: entre 0 y 50.
- Sector de interés: Tecnología, Retail, Servicios Financieros, Consultoría u Otro.
- Nivel de inglés: Básico, Intermedio, Avanzado o Nativo.
- Disponibilidad: Inmediata, 1 mes, 2-3 meses o Solo explorando.
- Aceptación de política de datos.

Campos opcionales:
- LinkedIn: URL válida.
- Comentarios adicionales: máximo 500 caracteres.

## 5. Reglas de negocio del formulario

- El formulario está destinado exclusivamente a candidatos.
- No debe utilizarse para solicitar servicios empresariales.
- Las empresas interesadas en contratar servicios deben recibir este mensaje:

  "¿Eres una empresa buscando talento? Escríbenos a contacto@nexova.com"

- El nombre debe contener al menos nombre y apellido.
- El email debe contener un formato válido y un dominio.
- El teléfono debe comenzar con + y contener el código de país.
- La experiencia debe estar entre 0 y 50.
- LinkedIn debe ser una URL válida cuando se proporcione.
- Los comentarios no pueden superar 500 caracteres.
- La política de datos debe aceptarse para enviar el formulario.
- El envío será simulado; no se debe afirmar que los datos se almacenan en un servidor.

Los mensajes de error y el mensaje de éxito deben respetar exactamente los definidos en BRIEFING.md.

## 6. Información de contacto

- Email: contacto@nexova.com
- Valencia: +34 960 123 456
- Miami: +1 305 555 0191

Redes sociales:
- LinkedIn: https://linkedin.com/company/nexova
- Instagram: https://instagram.com/nexova

## 7. Identidad visual

Dirección visual aprobada:

- Azul marino: color principal.
- Blanco: fondos y espacios limpios.
- Gris claro: fondos secundarios.
- Turquesa: color de acento.
- Tipografía moderna y elegante.
- Fotografías profesionales relacionadas con equipos de trabajo, liderazgo y recursos humanos.
- Tarjetas con bordes suaves y sombras discretas.
- Diseño limpio, corporativo y responsive.

Paleta propuesta:
- Azul marino: #142B46
- Blanco: #FFFFFF
- Gris claro: #F1F5F9
- Turquesa: #20B8B0

## 8. Requisitos técnicos

- Utilizar Tailwind CSS para el diseño.
- Utilizar HTML semántico.
- Garantizar accesibilidad y navegación mediante teclado.
- Implementar validaciones con JavaScript.
- Mostrar errores individuales y accesibles.
- Incluir contador visible de 500 caracteres.
- Implementar confirmación de envío simulado.
- Añadir metadatos SEO.
- Incorporar Schema.org de tipo Organization en la landing page.
- Adaptar el sitio a móviles, tabletas y computadores.
- Mantener el español como idioma principal.
- Dejar la estructura preparada para incorporar inglés posteriormente.

## 9. Restricciones y fuentes de información

- Trabajar dentro del repositorio existente.
- No crear un repositorio nuevo.
- No modificar BRIEFING.md.
- Consultar BRIEFING.md como fuente principal de requisitos.
- No inventar datos corporativos, servicios, direcciones o información de contacto.
- Mantener coherencia entre los textos de la página principal y el formulario.
- No implementar funcionalidades de IA, CRM o automatización comercial como parte del Hito 1, salvo que se soliciten expresamente en otro hito.