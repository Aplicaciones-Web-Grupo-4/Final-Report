# Capítulo IV: Product Design

## 4.1. Style Guidelines 

### 4.1.1. General Style Guidelines  

**Tono de Comunicación** <br>
El tono de NextHappen es cercano, dinámico y fresco, transmitiendo entusiasmo por descubrir nuevas experiencias. La comunicación busca ser amigable, inclusiva y confiable, con un lenguaje sencillo y positivo, acompañada por la personalidad de Happi, la llama, como guía de la experiencia.

**Tipografía:**<br>
- Spline Sans Bold → Títulos y subtítulos.
- Spline Sans Regular → Descripciones y textos secundarios.

**Colores de Marca:**<br>
- **Primarios:**
  -  **Amarillo (#FAC638):** usado para títulos, subtítulos y botones destacados → color de acento y diferenciador de marca.
  -  **Azul (#1E90FF):** fondo principal de la landing page (hero section) → color base y protagonista visual.
  -  **Negro (#000000 / #1D1C1B):** textos de descripciones y footer → color de soporte para legibilidad.
  -  **Blanco (#FFFFFF):** textos secundarios y contrastes → color de balance y limpieza visual.
  
- **Secundarios:**
  -  **Gris Claro (#F5F5F0 / #F5F5F7):** fondos generales, mantiene la estética limpia.
  -  **Gris Medio (#D9D9D9):** complementos y bordes.
  -  **Marrón (#1C170D):** subtítulos en contextos específicos.
  -  **Beige Claro (#F5F0E5):** barras de búsqueda.
  -  **Beige Suave (#E8E3CF):** detalles y acentos.
  -  **Dorado Suave (#9E8747):** texto de descripciones en secciones específicas.
  -  **Gris Separador (#E5E8EB):** divisores y líneas sutiles.
  -  **Amarillo Botón (#FAC738):** botones principales en la web.
  
**Paleta de Colores:**<br>

    Color            | Código Hex   |	Uso Principal
    -----------------|--------------|--------------------------------
    Amarillo	     |   #FAC638    |	Títulos, subtítulos y botones destacados
    Azul             |   #1E90FF    |	Fondo principal (hero section)
    Negro            |   #000000    |	Texto de descripciones
    Negro Footer     |   #1D1C1B    |	Footer
    Blanco           |   #FFFFFF    |	Textos secundarios
    Gris Claro       |   #F5F5F0    |	Fondo general
    Gris Medio       |   #D9D9D9    |	Complementos y bordes
    Marrón           |   #1C170D    |	Subtítulos
    Beige Claro      |   #F5F0E5    |	Barras de búsqueda
    Beige Suave      |   #E8E3CF    |	Detalles/acento
    Dorado Suave     |   #9E8747    |	Texto de descripciones
    Gris Separador   |   #E5E8EB    |	Separadores/espacios
    Amarillo Botón   |   #FAC738    |	Botones principales

**Spacing y Layout:**<br>
- **Espaciado amplio:** se prioriza la claridad y la respiración visual.
- **Margen mínimo:** 16px en mobile, 24px en desktop.
- **Grid layout:** diseño basado en columnas (12 columnas en desktop, 4–6 en mobile).
- **Jerarquía visual clara:** títulos grandes en Bold, descripciones más pequeñas en Regular.
- **Botones:** esquinas redondeadas (border-radius 12–16px) con suficiente padding (12px 24px).
- **Consistencia en secciones:** bloques bien delimitados con contraste de color (ejemplo: fondo claro + texto oscuro).

### 4.1.2. Web Style Guidelines  

**Responsive Design:**<br>

El diseño de la pagina se adapta a cualquier tipo de dispositivo.

**Componentes Implementados:**<br>

- Header: Título y menú hamburguesa con botones de navegación.
- Sección Hero: Título, slogan, descripción creativa y botón llamativo.
- Cards de integrantes: Cada card tiene el nombre del integrante, se describe su perfil y cada uno tiene su foto.
- Cards de características: Cada card tiene un título, su respectivo texto explicativo e imagenes según su tema.
- Sección de CTA (Call To Action): Es clara, directa y llamativa.
- Footer: Señalización de derechos de autor, secciones de la página, información de nuestro contacto y redes solciales.

**Interacciones:** <br>

- Hover sobre botones (cambio de color).
- Cards interactivos.
- Layout simple y minimalista.

## 4.2. Information Architecture 

Se desarrolló una página con una estructura simple y ordenada, pensada para que pueda ser utilizada sin dificultad tanto por usuarios con experiencia tecnológica como por aquellos que no cuentan con dichos conocimientos.

Orden lógico de las secciones:

- Hero: Primer impacto visual y botón CTA.
- ¿Quiénes somos?
- ¿Qué es NextHappen?
- Misión, Visión, Valores
- Funciones de la app web 
- Footer con información de redes y contacto

### 4.2.1. Organization Systems 

- **Jerárquico:**
  - El contenido se organiza de lo más llamativo a lo más específico. Primero se muestran los eventos destacados y cercanos en el mapa interactivo, luego se despliega la agenda por distritos y, finalmente, se presentan los detalles de cada feria, stand o emprendimiento.
- **Secuencial:**
  - La explicación del funcionamiento de la plataforma sigue un paso lógico y sencillo:
    
    1. **Registro y selección de intereses** con ayuda de Happi, la llama.
    2. **Exploración de eventos** a través del mapa y la agenda.
    3. **Personalización mediante notificaciones** en tiempo real.
    4. **Interacción con emprendedores y organizadores** para descubrir sus propuestas.
- **Por audiencia:** 
  - El contenido y las herramientas se adaptan según el tipo de usuario:
    
    - **Usuarios finales (público general):** acceso rápido a eventos cercanos, agenda personalizada y notificaciones.
    - **Emprendedores y organizadores:** espacio para publicar ferias, registrar stands y consultar métricas básicas sobre la interacción del público.


### 4.2.2. Labeling Systems 

El sistema de etiquetado de NextHappen se diseña para facilitar la navegación y la rápida identificación de contenidos, tanto para usuarios finales como para emprendedores y organizadores. Se busca mantener un lenguaje claro, inclusivo y consistente, alineado con el tono cercano y dinámico de la marca.

**Principios del sistema de etiquetado:**
- **Claridad:** las etiquetas deben ser breves, comprensibles y directas.
- **Consistencia:** se mantienen mismos términos y estilos a lo largo de toda la plataforma.
- **Relevancia:** cada etiqueta responde a un interés o necesidad específica del usuario.
- **Jerarquía:** etiquetas principales para categorías globales y secundarias para subtemas o detalles.

**Tipos de etiquetas en NextHappen:**

1. **Categorías principales (tópicos de interés):**
  
    - Gatronomía
    - Moda
    - Artesanía 
    - Tecnología 
    - Pop-ups / Ferias

2. **Etiquetas contextuales (para mejorar la búsqueda y filtros):**
   
   - Ubicación (por distrito, zona o cercanía).
   - Fecha/Hora (hoy, este fin de semana, próximamente).
   - Tipo de evento (gratuito, entrada libre, especial).
   - Perfil de usuario (emprendedor, visitante).

3. **Etiquetas de interfaz (UI):**
   
   - Botones principales: acción directa (“Explorar eventos”, “Publicar feria”, “Ver agenda”).
   - Menús y secciones: términos simples (“Inicio”, “Mapa”, “Mis notificaciones”, “Mi perfil”).
   - Estados del sistema: mensajes claros como “No hay eventos disponibles por ahora” o “Tu feria se publicó con éxito”.

### 4.2.3. SEO Tags and Meta Tags  

### 4.2.4. Searching Systems

El sistema de búsqueda de NextHappen está diseñado para que los usuarios encuentren de forma rápida y sencilla los eventos y ferias de su interés. Combina búsqueda directa, filtros personalizados y sugerencias inteligentes, asegurando que tanto usuarios con experiencia tecnológica como aquellos sin ella puedan navegar sin dificultades.

**Principios del sistema de búqueda:**

- **Simplicidad:** un buscador central y visible en la interfaz.
- **Relevancia:** resultados ordenados por cercanía, popularidad o interés del usuario.
- **Personalización:** recomendaciones basadas en intereses seleccionados durante el onboarding.
- **Accesibilidad:** lenguaje claro y filtros fáciles de usar.

**Tipos de búsqueda en NextHappen:**

1. **Búsqueda por palabra clave:**
  
    - Ejemplo: “food truck”, “feria artesanal”, “tecnología”.

2. **Búsqueda filtrada:**

    - **Ubicación:** por distrito o eventos cercanos.
    - **Fecha:** hoy, fin de semana, próximamente.
    - **Categoría:** gastronomía, arte, moda, tecnología.
    - **Tipo de acceso:** gratuito, entrada libre, especial.

3. **Búsqueda guiada (recomendaciones):**

    - Sugerencias automáticas en base a intereses definidos con Happi, la llama.
    - Eventos destacados en la zona del usuario.

### 4.2.5. Navigation Systems  

El sistema de navegación de NextHappen está diseñado para ser intuitivo, inclusivo y consistente, de modo que facilite la exploración tanto a usuarios con experiencia tecnológica como a quienes no la tienen. Se basa en una estructura clara que combina menús principales, accesos rápidos y navegación contextual.

**Principios del sistema de navegación:**

- **Claridad:** menús y secciones con nombres simples y comprensibles.
- **Consistencia:** las opciones de navegación se mantienen uniformes en todas las pantallas.
- **Accesibilidad:** botones visibles, con suficiente contraste y textos legibles.
- **Jerarquía:** acceso prioritario a lo más relevante (eventos, mapa y agenda).

**Tipos de navegación en NextHappen:**

1. **Navegación global (menú principal):**

    - Inicio
    - Explorar (mapa interactivo + agenda de eventos)
    - Mis Notificaciones
    - Mi Perfil
    - Publicar Feria (para emprendedores/organizadores)

2. **Navegación local (submenús y secciones internas):**

    - Dentro de un evento: descripción, ubicación, stands, contacto con organizador.
    - Dentro del perfil: intereses, historial de ferias, métricas (para emprendedores).

3. **Navegación contextual:**

    - Botones de acción rápida (“Explorar eventos cercanos”, “Ver agenda de hoy”).
    - Recomendaciones guiadas por Happi, la llama según los intereses seleccionados.

## 4.3. Landing Page UI Design  

### 4.3.1. Landing Page Wireframe  

![wireframe_landing.png](/assets/chapter-4/wireframe_landing.png)<br>
![wireframe_landing1.png](/assets/chapter-4/wireframe_landing1.png)<br>
![wireframe_landing2.png](/assets/chapter-4/wireframe_landing2.png)<br>
![wireframe_landing3.png](/assets/chapter-4/wireframe_landing3.png)<br>

### 4.3.2. Landing Page Mock-up 

![mockup_landing.png](/assets/chapter-4/mockup_landing.png)
![mockup_landing1.png](/assets/chapter-4/mockup_landing1.png)
![mockup_landing2.png](/assets/chapter-4/mockup_landing2.png)
![mockup_landing3.png](/assets/chapter-4/mockup_landing3.png)
![mockup_landing4.png](/assets/chapter-4/mockup_landing4.png)


## 4.4. Web Applications UX/UI Design  

### 4.4.1. Web Applications Wireframes  

Los wireframes de la plataforma web NextHappen muestran una estructura pensada para conectar a los usuarios con ferias, eventos y emprendedores de Lima, en una experiencia fresca y amigable guiada por Happi la llama. Incluyen:

- **Welcome Screen:** introduce a NextHappen con su diseño retro y fresco, mostrando a Happi la llama y ofreciendo opciones claras para iniciar sesión o registrarse.
- **Onboarding Personalizado:** flujo inicial en dos pasos que guía al usuario a seleccionar sus intereses (gastronomía, artesanía, moda, tecnología) y sus distritos favoritos en Lima, personalizando notificaciones y la experiencia en la app, siempre acompañado de Happi.
- **Home Screen:** muestra un buscador principal, secciones destacadas con “eventos recomendados”, y un acceso rápido a la opción “Hoy cerca de mí”, que presenta lo más relevante en tiempo real.
- **Fair Details Screen:** brinda información detallada de cada feria, con galería de fotos, descripción, horarios, mapa de ubicación y lista de stands registrados, junto a botones para añadir a favoritos o compartir en redes sociales.
- **Favorites Screen:** concentra los eventos guardados por el usuario. Si está vacío, aparece Happi con un mensaje motivador que invita a descubrir nuevas experiencias.
- **Notifications Screen:** reúne el historial de notificaciones push, como recordatorios de eventos cercanos (“Hoy hay una feria en Surco a 500m de ti”), ayudando a los usuarios a no perderse nada.
- **User Profile Screen:** permite al usuario gestionar sus datos, modificar intereses, actualizar distritos favoritos y activar o desactivar notificaciones, ofreciendo control total de la personalización.
- **Organizer/Entrepreneur Dashboard:** ofrece a los organizadores un panel con un resumen de las ferias creadas, métricas básicas de rendimiento (vistas, guardados) y accesos rápidos a sus publicaciones.
- **Publish Fair Screen:** formulario para registrar una nueva feria con título, descripción, fotos, ubicación en Google Maps y fechas, facilitando la creación de eventos de manera intuitiva.
- **My Published Fairs Screen:** lista editable de las ferias creadas por el organizador, con opciones para actualizar datos, gestionar inscripciones y mantener la información al día.
- **Stand Registration Screen:** módulo para registrar y vincular stands a cada feria, conectando directamente a los emprendedores con sus espacios dentro del evento.

Estos wireframes establecen la base de una plataforma dinámica, social y fácil de usar, que promueve el descubrimiento de eventos en Lima y fortalece la conexión entre usuarios, organizadores y emprendedores.

![wireframe_web](/assets/chapter-4/wireframe_web.png)

### 4.4.2. Web Applications Wireflow Diagrams  

### 4.4.3. Web Applications Mock-ups  

![mockup_web.png](/assets/chapter-4/mockup_web.png)

### 4.4.4. Web Applications User Flow Diagrams 

![web_user_flow](/assets/chapter-4/web_user_flow.png)

## 4.5. Web Applications Prototyping  

![web_user_flow](/assets/chapter-4/web_user_flow.png)

## 4.6. Domain-Driven Software Architecture  

### 4.6.1. Software Architecture Context Diagram  
![Context Diagram](/assets/chapter-4/Context_Diagram.png)

### 4.6.2. Software Architecture Container Diagrams  
![Container Diagram](/assets/chapter-4/Container_Diagram.png)

### 4.6.3. Software Architecture Components Diagrams  

#### Diagrama de componentes - Content Bounded Context
![Content_BC](/assets/chapter-4/Content_BC.png)

#### Diagrama de componentes - Discovery Bounded Context
![Discovery_BC](/assets/chapter-4/Discovery_BC.png)

#### Diagrama de componentes - Identity Bounded Context
![Identity_BC](/assets/chapter-4/Identity_BC.png)

#### Diagrama de componentes - Media Bounded Context
![Media_BC](/assets/chapter-4/Media_BC.png)

#### Diagrama de componentes - Notifications Bounded Context
![Notifications_BC](/assets/chapter-4/Notifications_BC.png)

#### Diagrama de componentes - Ticketing Bounded Context
![Ticketing_BC](/assets/chapter-4/Ticketing_BC.png)

## 4.7. Software Object-Oriented Design  

### 4.7.1. Class Diagrams  
![Diagrama_de_Clases](/assets/chapter-4/Diagrama_de_Clases.png)

### 4.7.2. Class Dictionary  
#### Clase: `User`

| Nombre de Atributo | Descripción | Tipo de Dato |
|---|---|---|
| `id` | Identificador único | UUID |
| `email` | Correo electrónico | String |
| `passwordHash` | Hash de contraseña | String |
| `role` | Rol del usuario | Role (enum) |
| `createdAt` | Fecha de creación | DateTime |
| `updatedAt` | Fecha de actualización | DateTime |

**Métodos**
- `verifyPassword(raw: String): Boolean` — verifica credenciales.

---

#### Clase: `Profile`

| Nombre de Atributo | Descripción | Tipo de Dato |
|---|---|---|
| `id` | Identificador de perfil | UUID |
| `fullName` | Nombre completo | String |
| `avatarUrl` | URL del avatar | String |
| `phone` | Teléfono | String |
| `city` | Ciudad | String |

---

#### Clase: `Fair`

| Nombre de Atributo | Descripción | Tipo de Dato |
|---|---|---|
| `id` | Identificador único | UUID |
| `title` | Título de la feria | String |
| `description` | Descripción | String |
| `status` | Estado de la feria | FairStatus (enum) |
| `startDate` | Fecha/hora de inicio | DateTime |
| `endDate` | Fecha/hora de fin | DateTime |
| `basePrice` | Precio base de entrada | Money |
| `minAge` | Edad mínima | Integer |

**Métodos**
- `isActive(date: DateTime): Boolean` — indica si está vigente.

---

#### Clase: `Order`

| Nombre de Atributo | Descripción | Tipo de Dato |
|---|---|---|
| `id` | Identificador de orden | UUID |
| `status` | Estado de la orden | OrderStatus (enum) |
| `totalAmount` | Importe total | Money |
| `createdAt` | Creación | DateTime |
| `updatedAt` | Actualización | DateTime |

**Métodos**
- `addItem(type: TicketType, qty: Integer): Void` — agrega ítems validando stock.
- `markPaid(): Void` — marca la orden como pagada.
- `cancel(): Void` — cancela la orden según reglas de estado.

---

#### Clase: `TicketType`

| Nombre de Atributo | Descripción | Tipo de Dato |
|---|---|---|
| `id` | Identificador | UUID |
| `name` | Nombre del tipo (General, VIP) | String |
| `price` | Precio | Money |
| `stock` | Stock disponible | Integer |

---

#### Clase: `Ticket`

| Nombre de Atributo | Descripción | Tipo de Dato |
|---|---|---|
| `id` | Identificador | UUID |
| `qrCode` | Código QR del ticket | String |
| `status` | Estado del ticket | TicketStatus (enum) |
| `issuedAt` | Fecha de emisión | DateTime |

**Métodos**
- `use(): Void` — marca como usado (una sola vez).

---

#### Clase: `Payment`

| Nombre de Atributo | Descripción | Tipo de Dato |
|---|---|---|
| `id` | Identificador de pago | UUID |
| `provider` | Pasarela de pago | PaymentProvider (enum) |
| `status` | Estado del pago | PaymentStatus (enum) |
| `externalId` | ID externo de la pasarela | String |
| `amount` | Importe cobrado | Money |
| `createdAt` | Fecha de creación | DateTime |
| `confirmedAt` | Fecha de confirmación | DateTime |
| `method` | Medio de pago | PaymentMethod (enum) |


---

#### Clase: `Coupon`

| Nombre de Atributo | Descripción | Tipo de Dato |
|---|---|---|
| `id` | Identificador | UUID |
| `code` | Código de cupón | String |
| `percentOff` | Descuento (%) | Decimal |
| `validFrom` | Vigente desde | DateTime |
| `validUntil` | Vigente hasta | DateTime |

---

#### Clase: `Subscription`

| Nombre de Atributo | Descripción | Tipo de Dato |
|---|---|---|
| `id` | Identificador | UUID |
| `emailEnabled` | Habilita correos | Boolean |
| `pushEnabled` | Habilita push | Boolean |


---

#### Clase: `Notification`

| Nombre de Atributo | Descripción | Tipo de Dato |
|---|---|---|
| `id` | Identificador | UUID |
| `type` | Tipo | NotificationType (enum) |
| `title` | Título | String |
| `body` | Cuerpo del mensaje | String |
| `scheduledAt` | Programada para | DateTime |
| `sentAt` | Enviada en | DateTime |
| `status` | Estado | NotificationStatus (enum) |

---

#### Clase: `MediaAsset`

| Nombre de Atributo | Descripción | Tipo de Dato |
|---|---|---|
| `id` | Identificador | UUID |
| `fileName` | Nombre de archivo | String |
| `mimeType` | Tipo MIME | String |
| `sizeBytes` | Tamaño (bytes) | Long |
| `storageKey` | Clave en storage | String |
| `publicUrl` | URL pública | String |
| `uploadedAt` | Subida en | DateTime |
| `isTemporary` | Indicador temporal | Boolean |

---

#### Clase: `ProfileInterest`

| Nombre de Atributo | Descripción | Tipo de Dato |
|---|---|---|
| `id` | Identificador | UUID |
| `createdAt` | Fecha de asociación | DateTime |

---

#### Clase: `Review`

| Nombre de Atributo | Descripción | Tipo de Dato |
|---|---|---|
| `id` | Identificador | UUID |
| `rating` | Calificación (1–5) | Integer |
| `comment` | Comentario | String |
| `createdAt` | Fecha de reseña | DateTime |

---

#### Clase: `Favorite`

| Nombre de Atributo | Descripción | Tipo de Dato |
|---|---|---|
| `id` | Identificador | UUID |
| `createdAt` | Fecha de guardado | DateTime |

---

#### Clase: `Stand`

| Nombre de Atributo | Descripción | Tipo de Dato |
|---|---|---|
| `id` | Identificador | UUID |
| `name` | Nombre del stand | String |
| `description` | Descripción | String |
| `ownerName` | Responsable | String |

---

#### Clase: `Category`

| Nombre de Atributo | Descripción | Tipo de Dato |
|---|---|---|
| `id` | Identificador | UUID |
| `name` | Nombre | String |
| `slug` | Slug URL | String |

---

#### Clase: `FairCategory`

| Nombre de Atributo | Descripción | Tipo de Dato |
|---|---|---|
| `id` | Identificador | UUID |
| `createdAt` | Fecha de asociación | DateTime |

---

#### Clase: `Recommendation`

| Nombre de Atributo | Descripción | Tipo de Dato |
|---|---|---|
| `id` | Identificador | UUID |
| `reason` | Motivo (intereses, zona, popularidad) | String |
| `score` | Puntuación/relevancia | Double |

---

#### Clase: `OrderItem`

| Nombre de Atributo | Descripción | Tipo de Dato |
|---|---|---|
| `id` | Identificador | UUID |
| `quantity` | Cantidad | Integer |
| `unitPrice` | Precio unitario | Money |
| `subtotal` | Subtotal calculado | Money |

---

#### Clase: `Location` *(ValueObject)*

| Nombre de Atributo | Descripción | Tipo de Dato |
|---|---|---|
| `address` | Dirección | String |
| `district` | Distrito | String |
| `latitude` | Latitud | Decimal |
| `longitude` | Longitud | Decimal |

---

#### Enum: `FairStatus`
| Valor | Descripción |
|---|---|
| `DRAFT` | Borrador |
| `PUBLISHED` | Publicada |
| `CANCELLED` | Cancelada |
| `FINISHED` | Finalizada |

---

#### Clase: `OAuthAccount`

| Nombre de Atributo | Descripción                                      | Tipo de Dato |
|---------------------|--------------------------------------------------|--------------|
| `id`               | Identificador único de la cuenta OAuth           | UUID         |
| `provider`         | Proveedor de autenticación (Google, Facebook)    | String       |
| `providerUserId`   | ID del usuario en el proveedor externo           | String       |
| `accessToken`      | Token de acceso proporcionado por el proveedor   | String       |
| `linkedAt`         | Fecha y hora de vinculación                      | DateTime     |

---

#### Clase: `Session`

| Nombre de Atributo | Descripción                           | Tipo de Dato |
|---------------------|---------------------------------------|--------------|
| `id`               | Identificador único de la sesión      | UUID         |
| `jwt`              | Token de sesión JWT                   | String       |
| `expiresAt`        | Fecha y hora de expiración            | DateTime     |
| `deviceInfo`       | Información del dispositivo           | String       |
| `ip`               | Dirección IP de inicio de sesión      | String       |

---

#### Enum: `PaymentProvider`

| Valor    | Descripción                          |
|----------|--------------------------------------|
| `STRIPE` | Procesador Stripe                    |
| `NIUBIZ` | Procesador Niubiz (local Perú)       |
| `PAYPAL` | Procesador PayPal                    |

---

#### Enum: `PaymentStatus`

| Valor            | Descripción                                      |
|------------------|--------------------------------------------------|
| `REQUIRES_ACTION` | Requiere acción adicional (ej. autenticación)   |
| `AUTHORIZED`      | Pago autorizado, pendiente de captura           |
| `CAPTURED`        | Pago confirmado y capturado                     |
| `FAILED`          | Pago fallido                                    |
| `REFUNDED`        | Pago reembolsado                                |

---

#### Enum: `PaymentMethod`

| Valor   | Descripción                  |
|---------|------------------------------|
| `CARD`  | Pago con tarjeta             |
| `CASH`  | Pago en efectivo             |
| `YAPE`  | Pago con billetera Yape      |
| `PLIN`  | Pago con billetera Plin      |

---

#### Clase: `Template`

| Nombre de Atributo | Descripción                            | Tipo de Dato |
|---------------------|----------------------------------------|--------------|
| `id`               | Identificador único de la plantilla    | UUID         |
| `code`             | Código interno de la plantilla         | String       |
| `subject`          | Asunto del mensaje                     | String       |
| `body`             | Contenido del mensaje                  | String       |

---

#### Clase: `NotificationLog`

| Nombre de Atributo | Descripción                               | Tipo de Dato |
|---------------------|-------------------------------------------|--------------|
| `id`               | Identificador único del log               | UUID         |
| `timestamp`        | Fecha y hora del evento                   | DateTime     |
| `providerMessageId`| ID del mensaje en el proveedor externo     | String       |
| `result`           | Resultado de la entrega                   | String       |

---

#### Clase: `ModerationRequest`

| Nombre de Atributo | Descripción                                   | Tipo de Dato |
|---------------------|-----------------------------------------------|--------------|
| `id`               | Identificador único de la solicitud           | UUID         |
| `status`           | Estado de la solicitud de moderación          | ModerationStatus (enum) |
| `reason`           | Razón de la solicitud                         | String       |
| `requestedAt`      | Fecha de creación de la solicitud             | DateTime     |
| `decidedAt`        | Fecha de resolución de la solicitud           | DateTime     |

---

#### Enum: `ModerationStatus`

| Valor      | Descripción                           |
|------------|---------------------------------------|
| `PENDING`  | Pendiente de revisión                 |
| `APPROVED` | Aprobado                              |
| `REJECTED` | Rechazado                             |

---

#### Clase: `OrganizerMetrics`

| Nombre de Atributo | Descripción                                    | Tipo de Dato |
|---------------------|------------------------------------------------|--------------|
| `id`               | Identificador único de métricas                | UUID         |
| `views`            | Número de visualizaciones del evento           | Integer      |
| `favorites`        | Número de usuarios que marcaron como favorito  | Integer      |
| `ticketsSold`      | Entradas vendidas                              | Integer      |
| `ratingAvg`        | Promedio de calificaciones                     | Double       |
| `ratingCount`      | Número total de calificaciones recibidas       | Integer      |

## 4.8. Database Design  

### 4.8.1. Database Diagram  
![Diagrama_DB1](/assets/chapter-4/Diagrama_DB1.png)
![Diagrama_DB2](/assets/chapter-4/Diagrama_DB2.png)
