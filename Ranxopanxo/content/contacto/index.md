+++
title = 'Contacto'
+++

¿Quieres ponerte en contacto con nosotros? Rellena el formulario y te responderemos lo antes posible.

<form action="https://formspree.io/f/TU_FORM_ID" method="POST" style="max-width: 600px; margin: 2rem auto;">

  <div style="margin-bottom: 1rem;">
    <label for="name" style="display: block; margin-bottom: 0.3rem; font-weight: bold;">Nombre</label>
    <input type="text" id="name" name="name" required
      style="width: 100%; padding: 0.5rem; border: 1px solid #ccc; border-radius: 4px;">
  </div>

  <div style="margin-bottom: 1rem;">
    <label for="email" style="display: block; margin-bottom: 0.3rem; font-weight: bold;">Correo electrónico</label>
    <input type="email" id="email" name="email" required
      style="width: 100%; padding: 0.5rem; border: 1px solid #ccc; border-radius: 4px;">
  </div>

  <div style="margin-bottom: 1rem;">
    <label for="subject" style="display: block; margin-bottom: 0.3rem; font-weight: bold;">Asunto</label>
    <input type="text" id="subject" name="_subject" required
      style="width: 100%; padding: 0.5rem; border: 1px solid #ccc; border-radius: 4px;">
  </div>

  <div style="margin-bottom: 1rem;">
    <label for="message" style="display: block; margin-bottom: 0.3rem; font-weight: bold;">Mensaje</label>
    <textarea id="message" name="message" rows="6" required
      style="width: 100%; padding: 0.5rem; border: 1px solid #ccc; border-radius: 4px;"></textarea>
  </div>

  <button type="submit"
    style="padding: 0.7rem 2rem; background: #333; color: #fff; border: none; border-radius: 4px; cursor: pointer; font-size: 1rem;">
    Enviar mensaje
  </button>

</form>
