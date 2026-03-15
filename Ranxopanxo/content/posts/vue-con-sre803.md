+++
date = '2026-03-15T10:30:00+01:00'
draft = false
title = 'Introduccion a Vue con Sre803'
author = 'Sre803'
+++

Vue es un framework progresivo de JavaScript para construir interfaces web de forma clara y mantenible. Si vienes de HTML, CSS y JavaScript puro, su curva de aprendizaje suele ser muy amigable.

## Por que Vue

- Sintaxis declarativa y facil de leer.
- Componentes reutilizables para ordenar mejor el proyecto.
- Ecosistema solido con Vue Router y Pinia.
- Muy buena opcion para proyectos pequenos y tambien para apps grandes.

## Conceptos clave

### 1. Reactividad

La reactividad permite que la interfaz se actualice automaticamente cuando cambian los datos.

```js
import { ref } from 'vue'

const contador = ref(0)
```

### 2. Componentes

En Vue, cada parte de la interfaz puede convertirse en un componente.

```vue
<template>
  <button @click="contador++">Clicks: {{ contador }}</button>
</template>

<script setup>
import { ref } from 'vue'
const contador = ref(0)
</script>
```

### 3. Directivas

Directivas como `v-if`, `v-for` y `v-model` te ayudan a manejar logica en la vista sin complicarte.

## Recomendaciones para empezar

1. Comienza con `create-vue` para generar un proyecto base.
2. Organiza tus componentes por dominio funcional.
3. Separa la logica de negocio en composables.
4. Agrega linting y formateo desde el inicio.

Vue combina simplicidad y potencia. Si estas iniciando en frontend moderno, es una excelente herramienta para aprender buenas practicas desde el primer dia.
