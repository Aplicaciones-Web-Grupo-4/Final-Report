# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping
> **Segmento 1 – Mariana Rafael (Usuario – asistente a ferias)**  

| **Phases**              | **Buscar información** | **Planificar la visita** | **Asistir a la feria** | **Compartir experiencia** |
|--------------------------|-------------------------|---------------------------|-------------------------|---------------------------|
| **Doing**   |•Consulta una plataforma que tenga todas las ferias.<br> •Usa filtros por interes con fechas y ubcacion en tiempo real |•Crea trayectos personalizados. <br>•Recibe notificaciones automáticas.|•Recibe alertas de actividades en tiempo real.<br>•Utiliza mapa digital interactivo. |•Publica reseñas en la app. <br> •Comenta reseñas en la plataforma.<br> •Comparte fotos y experiencias positivas.|
| **Thinking** |•"Toda la información es clara y confiable". <br> "Puedo comparar y elegir la mejor feria".  |•"Sé que ferias me interesan". <br> "Tengo conocimineto sobre llegar y qué hacer".  |•"No me pierdo nada porque recibo notificaciones y recordatorios".    |•"Mi opinión ayuda a los demas asistentes y organizadores". "Si recomendaria esta feria". |
| **Feeling** |•Tranquilidad y confianza.<br> Motivación|•Segura y organizada con un plan caro. |•Emoción <br> Buena orientacion. |•Satisfecha y valorada. |

---

> **Segmento 2 – Carlos Garnique (Organizador de ferias)**  

| **Phases**              | **Promocionar feria** | **Gestionar inscripciones** | **Medir resultados** | **Atender imprevistos** |
|--------------------------|------------------------|------------------------------|-----------------------|--------------------------|
| **Doing**   |•Publica su feria que promueve en redes sociales. |•Recibe notificaciones automáticas en la plataforma.  |•Acceso a ventas, visitas y reseñas. |•Envía notificaciones mediante la app o SMS  a los asistentes. |
| **Thinking** |•"Estoy logrando motivar a más público." <br>•"La información extra no se pierde."|•"Puedo contabilizar de los asistentes en tiempo real."  |•"Sé como se ha llevado el evento acabo."<br> •"Puedo justificar la inversión en publicidad."  |•"Los cambios de notificaciones son inmediatos y fácil de comprensión."|
| **Feeling** |•Aliviado.  <br>•Motivado.  |•Seguro. <br>•Confiado. |•Satisfecho. <br>•Motivado para mejorar eventos futuros. |•Tranquilo por resolver los problemas de manera eficaz.|

## 3.2. User Stories
| ID   | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
|------|--------|-------------|-------------------------|----------------------------|
| EP01  | Descubrimiento de Ferias | Como visitante quiero descubrir ferias gastronómicas organizadas para poder decidir a cuáles asistir. | N/A | - |
| EP02  | Compra de entradas  | Como organizador quiero gestionar la compra y validacion de entradas de manera sencilla. | N/A | - |
| EP03  | Recomendaciones personalizadas | Como developer quiero ofrecer sugerencias basadas en sus intereses. | N/A | - |
| EP04  | Gestion de Ferias | Como organizador quiero que los emprendedores gestionen sus ferias de forma eficiente. | N/A | - |
| EP05  | Conexion de Landing Page | Como developer quiero disponer de un sitio web informativo que capte atencion de los visitantes. | N/A | - |
| EP06  | Api Restful | Como developer quiero exponer servicios que permitan la integracion del sistema. | N/A | - |
| EP07  | Administracion de PLataforma | Como organizador  quiero supervisar la calidad edl sistema. | N/A | - |
| EP08  | Descubir eventos | Como visitante quiero explorar eventos de ferias gastronomicas segun la fecha y ubicacion. | N/A | - |
| EP09  | Recibir notificaciones | Como visitante quiero recibir notificaciones sobre mis eventos y recordatorios en tiempo real. | N/A | - |
| EP10  | Experiencia turisticas | Como turista quiero encontrar ferias con traduccion basica para una facil comprension. | N/A | - |
| EP11  | Metrica para ogranizadores  | Como organizador quiero ver acceder a metricas de mis ferias para evaluar el impacto. | N/A | - |
| US01  |Busqueda de filtros   |Como visitante quiero buscar ferias por ubicacion , fecha y categoria para eventos intersantes de mi gusto . |**Dado que** un visitante accedde al buscador, **cuando** aplica los filtros de referencia, **entonces** se muestran los eventos que cumplen los criterios.| EP1 |
| US01  |Busqueda de filtros  |Como visitante quiero buscar ferias por ubicacion , fecha y categoria para eventos interesantes de mi gusto . |**Dado que** un visitante accedde al buscador, **cuando** aplica los filtros de referencia, **entonces** se muestran los eventos que cumplen los criterios.| EP1 |
| US02  |Mapa interactivo  |Como visitante quiero visualizar las ferias en un mapa para ubicarme con facilidad . |**Dado que** un visitante abre el mapa , **cuando** selecciona un evento en el mapa, **entonces**  se muestra informacion clara de ubibcacion , fecha y hora.| EP1 |
| US03  |Alertas en tiempo real  |Como visitante quiero recibir alertas en tiempo real de algunos cambios en la feria para non perderme el evento . |**Dado que** esta inscrito a un evento , **cuando** el organizador actualiza el horario o el lugar, **entonces**  se muestra una notificacion inmediata.| EP1 |
| US04  |Favoritos  |Como visitante quiero marcar ferias como favoritas para visualizar en cualquier momento . |**Dado que** un visitante visualiza un evento , **cuando** pulsa "favoritos" , **entonces**  el evento se guarda en su lista personal.| EP1 |
| US05  |Compra de entradas |Como visitante quiero comprar entradas de forma segura para asistir a una feria . |**Dado que** selecciona un evento , **cuando** confirma la compra con pago valido , **entonces**  se muestra un comprobante de pago.| EP2 |
| US06  |Validacion de entrada  |Como organizador quiero validar tickets para garantizar el acceso adecuado a un evento. |**Dado que** un organizador escanea un ticket , **cuando** es valido , **entonces** se marca como registrado y permite el ingreso .| EP2 |
| US07  |Recomendaciones por perfil  |Como visitante quiero recibir notificaciones basadas en mis compras anteriores y de mi interes. |**Dado que** un visitante tiene unn historial de compras , **cuando** accede a la seccion de recomendaciones , **entonces** se muestra eventos relacionados a su interes.| EP3 |
| US08  |Suscripcion por categorias |Como visitante quiero suscribirme a distintas categorias de ferias(gastronomica,artesanal, etc) para recibir sugerencias relevantes. |**Dado que** un visitante elige categorias de su gusto , **cuando** exista nuevos eventos , **entonces** recibe las propuestas de su gusto .| EP3 |
| US09  |Publicacion de feria  |Como organizador quiero registrar mi feria para darla a conocer al publico. |**Dado que** un organizador completa los datos de su feria , **cuando** guarda el formulario , **entonces** la feria se publica y llega a ser visible para los visitantes.| EP4 |
| US10  |Actualizar de datos  |Como organizador quiero actualizar horarios o ubicacion para mantener la informacion al dia. |**Dado que** un organizador edita los datos del evento , **cuando** guarda los cambios , **entonces** los visitantes suscritos reciben la actualizacion en tiempo real.| EP4 |
| US11  |Planes de suscripcion  |Como organizador quiero acceder a planes de suscripcion para mejorar la visibilidad de mis ferias. |**Dado que** un organizador selecciona un plan , **cuando** se confirma el pago , **entonces**su evento recibe beneficios de mayor exposicion.| EP4 |
| US12  |Compartir eventos en redes  |Como visitante quiero compartir eventos en redes sociales para invitar a mis amigos. |**Dado que** un visitante visualiza un evento, **cuando** selecciona "compartir" , **entonces** se genera un enlace para publicar en redes.| EP1 |
| US13  |Reseñas  |Como visitante quiero dejar reseñas despues de asistir a un evento para ayudar a otros usuarios. |**Dado que** un visitante asiste a un evento, **cuando** selecciona y escribe una reseña , **entonces** queda registrado y visible para todos.| EP1 |
| US14  |Descuento por compras |Como visitante quiero usar cupones de descuento en mis compras para obtener benbeficios. |**Dado que** un visitante ingresa unn codigo valido, **cuando** selecciona y aplica en comprar , **entonces** se muestra en el sistema el descuento del monto.| EP2 |
| US15  |Metodos de pago  |Como visitante quiero pagar con efectivo, tarjeta , Yape o Plin para mayor comodidad. |**Dado que** un visitante elige un metodo de pago, **cuando** completa los datos , **entonces** el sistema procesa la transaccion .| EP2|
| US16  |Plan de promociones  |Como organizador  quiero crear promociones para atraer mas público. |**Dado que** un organizador crea una promocion , **cuando** selecciona y la activa , **entonces** los usuarios lo ven aplicada al evento de su preferencia.| EP4 |
| US17  |Roles de equipo |Como organizador quiero asignar roles a mi equipo para asignar tareas en la feria. |**Dado que** un organizador agrega miembros de equipo , **cuando** asigna un rol , **entonces** cada miembro de equipo obtiene acceso limitado y tareas.| EP4 |
| US18  |Canales de soporte  |Como organizador quiero responder dudas y preguntas de los usuarios dentro de la plataforma. |**Dado que** un usuario envia una consulta , **cuando** el organizador responde , **entonces** ambos ven el historial del chat y resuelven la duda.| EP4 |
| US19  |Selecion de idioma  |Como turista quiero cambiar el idioma de la plataforma para comprender toda la informacion. |**Dado que** un usuario selecciona "idiomas" en configuracion , **cuando** actualiza la vista , **entonces** todo el contenido se muestra en el idioma elegido.| EP9 |
| US20  |Reporte de ventas  |Como organizador quiero ver un reporte de entradas vendidas por fecha. |**Dado que** un organizador ingresa a estadisticas  , **cuando** selecciona un rango de fechas , **entonces** visualiza una  cantidad de entradas vendidas.| EP10 |
| US21  |Reporte de alcance  |Como organizador quiero ver el numero de visuaslizaciones de mi evento. |**Dado que** un organizador abre el reporte de alcance  , **cuando** revisa sus eventos , **entonces**  visualiza la cantidad de visitas de su evento.| EP10 |
| TS01  |Get eventos  |Como developer quiero implementar filtros de ubicacion y fechas para entregar resultados al frontend. |**Scenario 1:Registro correcto** <br>**Dado que** un request con filtros validos  , **cuando** el backend procesa , **entonces** retorna la lista filtrada en Json. <br><br>**Scenario 2:Registro incorrecto**<br>**Dado que**un request invalido, , **cuando** el backend procesa , **entonces** retorna un error con mensaje. | EP04 |
| TS02  |Post Reseñas  |Como developer quiero un endpoiot para que los usuarios agreguen reseñas . |**Scenario 1:Usuario encontrado** <br>**Dado que** un request valido para usuarios autenticado , **cuando**  envia la reseña , **entonces** se guarda y retorna confirmacion en Json. <br><br>**Scenario 2:Usuario no encontradao**<br>**Dado que**un request sin autenticacion, , **cuando** se intenta enviar una reseña , **entonces** retorna un error con mensaje. | EP06 |
| TS03  |Post notificaciones |Como developer quiero un endpoint para enviar notificaciones a ususarios suscritos en eventos . |**Scenario 1:** <br>**Dado que** un evento valido con ID de evento , **cuando** se ejecute la peticion  , **entonces** el sistema envia notificaciones a usuarios suscritos. <br><br>**Scenario 2:**<br>**Dado que** un evento invalido  , **cuando**  se procesa  , **entonces** retorna un error y no envia notificaciones. | EP06 |
| TS04  |Post Login / Registro |Como developer quiero un endpoint para registro e inicio de sesion . |**Scenario 1:** <br>**Dado que** un usuario coloca credenciales validas , **cuando** se solicita autenticacion  , **entonces** el sistema retorna validacion. <br><br>**Scenario 2:**<br>**Dado que** un usuario coloca credenciales invalidas  , **cuando** intena iniciar sesion  , **entonces** el sistema retorna un error y vuelva a intentar de nuevo. | EP06 |
| TS05  |Post roles/ permisos |Como developer quiero un endpoint para asignar y validar permisos de usuarios(visitantes,administrador y organizador) . |**Scenario 1:** <br>**Dado que** admin autorizado solitica asignar un rol , **cuando** el sistema procesa la solicitud  , **entonces** actualiza el rol del usuario. <br><br>**Scenario 2:**<br>**Dado que** un usuario sin autoridad intenta cambiar roles  , **cuando** se procesa  , **entonces** el sistema retorna un error . | EP06 |
| TS06  |Get metricas/eventos|Como developer quiero un endpoint para devolver metricas de un evento . |**Scenario 1:** <br>**Dado que** un evento valido con permisos adecuados , **cuando** se solicita la verificacion del endpoint  , **entonces** retorna metricas detalladas del evento. <br><br>**Scenario 2:**<br>**Dado que** un evento sin permisos  , **cuando** se procesa  , **entonces** el sistema retorna un error y vuelva a intentar de nuevo. | EP06 |
| TS07  |Post pagos|Como developer quiero un endpoint para procesar pagos mediante distintas formas posibles . |**Scenario 1:Informacion de pago encontrada** <br>**Dado que** un request valido con datos de pago , **cuando** se solicita la verificacion   , **entonces** retorna la confirmacion de la transaccion. <br><br>**Scenario 2:Informacion de pago no encontrada**<br>**Dado que** un request devuelve error  , **cuando** se procesa el pago  , **entonces** el sistema retorna un error y registra el intento. | EP06 |
| TS08  |Get logs|Como developer quiero un endpoint para registrar eventos criticos y auditoria del sistema . |**Scenario 1:** <br>**Dado que** un request valido con datos de log, **cuando** se solicita la verificacion   , **entonces** se guarda en el sistema y retorna confirmacion. <br><br>**Scenario 2:**<br>**Dado que** un request invalido sin campos requeridos , **cuando** se procesa  , **entonces** el sistema retorna un error. | EP06 |
| TS09  |Post recomendaciones |Como developer quiero un endpoint entregue recomendaciones de eventos segun el perfil e historial . |**Scenario 1:** <br>**Dado que** un request valido con perifl de usuario, **cuando** se solicita la verificacion   , **entonces** retorna una lista de eventos sugeridos. <br><br>**Scenario 2:**<br>**Dado que** un perfil no tiene datos suficientes , **cuando** se procesa  , **entonces** el sistema retorna una lista vacia recomendaciones por defecto. | EP06 |
| TS10  |Get traduccion |Como developer quiero un endpoint que traduzco los textos a idiomas diferentes . |**Scenario 1:** <br>**Dado que** un request valido con idioma y texto soportado, **cuando** se solicita la verificacion   , **entonces** retorna el texto traducido. <br><br>**Scenario 2:**<br>**Dado que** un idioma no soportado , **cuando** se procesa  , **entonces** el sistema retorna un mensaje de error. | EP06 |



## 3.3. Impact Mapping
![Impact Mapping](docs/images/Impact_map.png)


## 3.4. Product Backlog
