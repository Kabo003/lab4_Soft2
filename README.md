# Historia de Usuario - Sprint 2

## Historia de Usuario
**Como cliente**, quiero consultar a un **chatbot** sobre **medicamentos o farmacias disponibles**, para lograr obtener **información rápida y precisa** sin tener que **buscar manualmente en la plataforma**.

- **Módulo:** Chatbot  
- **Estado:** Pendiente  
- **Tamaño:** XL  
- **Prioridad:** 2  
- **Complejidad:** Intermedia  

---

## Escenarios de Prueba

### Happy Paths (Escenarios exitosos)

1. **Consulta exitosa por nombre de medicamento**
   - El cliente escribe “¿Tienen paracetamol?”
   - El chatbot responde con la disponibilidad del medicamento y farmacias donde se encuentra.
   - Resultado: El cliente recibe la información correctamente.

2. **Consulta exitosa por nombre de farmacia**
   - El cliente pregunta: “¿Qué medicamentos hay en Inkafarma?”
   - El chatbot lista los medicamentos disponibles en esa farmacia.
   - Resultado: El cliente obtiene una lista útil.

3. **Consulta general sobre disponibilidad**
   - El cliente escribe: “Necesito un analgésico”
   - El chatbot sugiere medicamentos relacionados (ej. ibuprofeno, paracetamol) y farmacias donde están disponibles.
   - Resultado: El usuario recibe opciones relevantes.

4. **Reconocimiento de sinónimos o errores menores**
   - El cliente pregunta por “paraceta mol”
   - El chatbot corrige automáticamente y responde como si hubiera escrito “paracetamol”.
   - Resultado: Mejora de la experiencia del usuario.

---

### Unhappy Paths (Escenarios fallidos o con errores)

1. **Entrada no entendida por el chatbot**
   - El cliente escribe: “¿Me puedes dar algo para el alma?”
   - El chatbot responde con: “Lo siento, no entendí tu consulta. ¿Podrías reformularla?”
   - Resultado: El usuario no recibe una respuesta útil.

2. **Medicamento no encontrado**
   - El cliente consulta: “¿Tienen dipirona?”
   - El chatbot responde: “Actualmente no tenemos información sobre ese medicamento.”
   - Resultado: Información limitada.

3. **Farmacia no registrada**
   - El cliente escribe: “¿Qué hay en Farmacia El Buen Samaritano?”
   - El chatbot indica que no tiene datos de esa farmacia.
   - Resultado: El sistema limita la búsqueda solo a farmacias registradas.

4. **Falla técnica en el chatbot**
   - El cliente hace una consulta pero el chatbot está fuera de servicio.
   - El sistema responde: “Actualmente el chatbot no está disponible. Intente más tarde.”
   - Resultado: Pérdida temporal de funcionalidad.

---