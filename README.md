# JuntIA

La comunicación interna de tu asociación, sin esfuerzo. Aplicación web de un solo fichero.

**Usar la app:** https://fborrasumh.github.io/juntia/

**Idiomas:** español (por defecto), catalán, euskera, gallego, inglés, portugués; selector en la barra superior (o `?lang=ca`, `?lang=eu`, `?lang=gl`, `?lang=en` o `?lang=pt` en la URL). Las traducciones al catalán, euskera y gallego están pendientes de revisión por hablantes nativos.

## Qué hace

Ayuda al voluntariado y al personal de las asociaciones de pacientes con su comunicación interna, en tres pasos:

1. **Tu asociación.** Perfil breve (nombre, ámbito, misión, tono, expresiones que se evitan). Se descarga en un archivo `.json` con el formato común `perfil-asociacion-pacientes` (el mismo que DifundIA, SubvencIA y EncuestIA) y se sube en las demás apps del curso. Incluye el logo, los colores, la web y el correo de la asociación, que salen en el Word y en el correo. Al descargarlo se conservan los campos que JuntIA no usa (redes, hashtags y eslogan). También lee los perfiles del formato anterior de JuntIA (`propatiens-perfil/1`) y el expediente de AsociacIA.
2. **¿Qué necesitas?** Acta de una reunión, convocatoria, comunicado a socios o voluntariado, o boletín interno. Se suben los documentos que haya (Word, PDF, PowerPoint, texto, fotos de notas, grabaciones de audio) y se escribe la idea en una frase.
3. **Revisa y envía.** El documento sale listo para editar, copiar, descargar en Word (con cabecera de logo y nombre, colores de la asociación y «Página X de Y» al pie) o enviar por correo: abre Gmail, Outlook.com, Outlook de Microsoft 365 o el programa de correo con el asunto puesto y copia el cuerpo con formato (logo, colores y pie) para pegarlo. Guarda en el navegador los últimos ocho documentos.

Lo que comprueba el código (no la IA): que cada acuerdo, fecha o dato del resultado aparezca literalmente en los documentos o en la idea (lo que no aparece se marca); las cifras que no estaban en el material; los huecos `[COMPLETAR]`; y las expresiones que la asociación evita. Al editar el texto, los avisos se recalculan.

Incluye un ejemplo con una asociación ficticia que funciona sin clave de IA.

## Cómo se usa la IA

Con la propia clave de OpenAI, Google Gemini o Anthropic Claude. La clave se guarda solo en el navegador. No hace falta servidor.

## Privacidad

El perfil, los documentos y los resultados se guardan solo en el navegador. Al pulsar «Hacerlo», la idea y el texto de los documentos salen hacia el proveedor de IA elegido con correos, teléfonos, DNI e IBAN enmascarados; antes del primer envío de cada sesión se muestra lo que sale. Las grabaciones (transcritas con OpenAI o Gemini) y las fotos de notas (leídas por la IA) no se pueden enmascarar: la app lo avisa y pide confirmación. No deben subirse historias clínicas, listados de socios ni datos de salud de personas concretas.

## Límites

- La IA puede equivocarse: todo documento debe leerlo y revisarlo una persona antes de enviarlo.
- La comprobación de citas detecta datos que no están en el material, pero no si un dato que sí está se ha interpretado mal.
- Los documentos muy largos se recortan (unos 80.000 caracteres en total).
- No envía correos por sí misma: abre el correo de quien la usa y copia el texto con formato, que hay que pegar en el cuerpo (Ctrl+V o Cmd+V). Si el navegador no deja copiar con formato, el texto va sin formato en el cuerpo.
- Probada con IA simulada en los tres proveedores; la transcripción de audio no se ha probado en el entorno de pruebas.

## Autoría

Fernando Borrás Rocher (Universidad Miguel Hernández de Elche).

Desarrollada para la Cátedra del Paciente de la Universidad Miguel Hernández e Instituto ProPatiens.

ORCID: Fernando Borrás Rocher [0000-0002-5519-4573](https://orcid.org/0000-0002-5519-4573)

## Cómo citar

Borrás Rocher, F. (2026). *JuntIA* (v1.2.0) [Software]. (DOI en trámite)

## Licencia

MIT. Véase [LICENSE](LICENSE).
