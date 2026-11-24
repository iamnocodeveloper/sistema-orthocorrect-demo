# OrthoCorrect Dental Center — demo del sistema de gestión

Demo navegable del sistema de gestión de una clínica dental y de ortodoncia en Costa Rica.
Una sola página (`index.html`, CSS y JavaScript en línea, sin backend) publicada en EasyPanel
con un `Dockerfile` de nginx.

## Qué incluye

- **Panel del día**: citas por profesional y sillón, sala de espera, tratamientos por iniciar, cobros y recordatorios.
- **Pacientes**: listado buscable y ficha con datos, edad, contacto, alergias, antecedentes, notas, citas, tratamientos, pagos y documentos.
- **Mapeo dental**: odontograma de 32 piezas con numeración FDI, dentición permanente y temporal, 5 caras por diente y 9 estados (sano, caries, obturado, sellante, corona, endodoncia, extraído, implante, prótesis), nota por pieza y resumen de hallazgos.
- **Diagnóstico y plan**: diagnósticos por diente y superficie, plan con sesiones y estados, y presupuesto con total, abonado y saldo.
- **Citas y agenda**: vista de día y de semana por profesional, alta de cita con detección de cruces y recordatorio por WhatsApp.
- **Conversaciones**: bandeja de WhatsApp con hilo, envío simulado, agendar desde el chat y crear paciente desde un número nuevo.
- **Privacidad y datos**: servidor propio de la clínica, cifrado de base y copias, accesos por rol y bitácora de accesos.
- **Informes**: citas por mes, no asistencia, ingresos por tratamiento, tratamientos frecuentes y producción por profesional.
- **Recorrido guiado** de 8 pasos con teclado (← → Esc), modo automático y vista móvil.

## Publicación

El servicio se despliega en EasyPanel desde este repositorio con el `Dockerfile` incluido
(nginx en el puerto 80).

Demo de referencia hecho por Nocodeveloper. Los datos son de ejemplo.
