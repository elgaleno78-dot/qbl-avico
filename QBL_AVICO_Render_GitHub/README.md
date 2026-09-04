# QBL Obstétrico AVICO® — Render/GitHub

Aplicación web/PWA responsive para teléfono, tablet y laptop.

## v5
- QR público corregido y botón Compartir (Web Share API) + copiar enlace.
- Sangrado pesado/cuantiﬁcado: captura cada material uno por uno con hora, cantidad, peso seco, peso húmedo y QBL individual; acumulado automático y borrado de errores.
- Guardado local de pacientes en el navegador/dispositivo.
- Cargar o eliminar registros guardados.
- Descarga de base de pacientes en CSV y respaldo completo JSON.
- Tapiz AVICO, impresión/PDF y PWA offline.

## Render
Root Directory: `QBL_AVICO_Render_GitHub`
Build Command: vacío
Publish Directory: `.`

> Prototipo de apoyo clínico. El almacenamiento local del navegador no sustituye un sistema institucional seguro ni un expediente electrónico validado.


## v10
Tema AVICO rojo, tapiz de marca visible, autoría reforzada en móvil y acceso privado del autor a expedientes/exportación Excel (CSV) mediante clave local configurada en el primer acceso. Los usuarios pueden guardar pacientes, pero no ven la lista de registros guardados mientras el acceso del autor esté bloqueado.


## v12
Corrige el layout roto en escritorio: las tarjetas ahora usan IDs estables en vez de `nth-of-type`. El QR y Pacientes ocupan ancho completo. Se añade un tapiz AVICO repetido y sutil para evitar el logotipo central sobredimensionado.


## v13 PC PRO
Rediseño específico para PC/laptop: sidebar AVICO más elegante, contenido máximo 1500 px, tarjetas mejor distribuidas, Pacientes y Compartir/QR en columnas 7/5, tapiz visible pero discreto, mejor jerarquía visual y controles más amplios. No modifica la lógica clínica ni el diseño móvil.
