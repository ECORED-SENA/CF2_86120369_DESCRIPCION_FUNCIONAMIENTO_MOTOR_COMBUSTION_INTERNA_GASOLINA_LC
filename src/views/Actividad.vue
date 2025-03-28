<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno(icono="far fa-question-circle" titulo="Actividad didáctica")
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5
  
      #Actividad                
        <Actividad :cuestionario="cuestionario"/>
  
  </template>

<script>
import Actividad from 'ecored-pkg-fliz/plugin/components/actividad/Actividad.vue'
export default {
  name: 'ActividadDidactica',
  components: {
    Actividad,
  },
  data: () => ({
    cuestionario: {
      tema:
        'Evaluación sobre componentes y funcionamiento del motor de combustión interna',
      titulo: 'Cuestionario',
      introduccion:
        '<b> Objetivo:</b> evaluar el conocimiento sobre los componentes y el funcionamiento del sistema de válvulas, culata y árbol de levas en motores de combustión interna.',
      barajarPreguntas: true,
      titulo_aprobado: '¡BUEN TRABAJO!',
      titulo_reprobado: '¡VUELVA A INTENTARLO!',
      preguntas: [
        {
          id: 1,
          texto:
            '¿Cuál es la función principal del árbol de levas en un motor de combustión interna?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Controlar el encendido de la bujía.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Regular la apertura y cierre de las válvulas.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Enfriar los gases de escape.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Controlar el flujo de combustible.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 2,
          texto: '¿Qué función cumplen los seguros de las válvulas?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Facilitar el ingreso del combustible.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Permitir la lubricación de las válvulas.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Mantener fijo el platillo del muelle de la válvula.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto: 'Controlar la presión del combustible.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 3,
          texto:
            '¿Cuál es el propósito de los conductos de admisión en la culata?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Permitir la salida de los gases quemados.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Reducir la temperatura del motor.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Controlar el nivel de aceite del motor.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Permitir el ingreso de la mezcla aire-combustible.',
              esCorrecta: true,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 4,
          texto:
            '¿Cuál es la ventaja de los motores con más de dos válvulas por cilindro?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Reducen el consumo de combustible.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Disminuyen el desgaste del pistón.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Aumentan la eficiencia en la entrada y salida de gases.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto: 'Evitan la contaminación por gases de escape.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 5,
          texto: '¿Para qué se utilizan los muelles de las válvulas?',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Asegurar el cierre hermético de la válvula a altas revoluciones.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Reducir el desgaste del motor.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Evitar la acumulación de aceite en las válvulas.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Mejorar la combustión dentro del cilindro.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 6,
          texto: '¿Para qué se utilizan los muelles de las válvulas?',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Para aumentar la potencia del motor.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Para mantener la válvula cerrada cuando no es empujada por la leva.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Para reducir la vibración del cigüeñal.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Para evitar fugas de aceite.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 7,
          texto: '¿Cuál es la función del empaque de la culata?',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Separar los cilindros del motor.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Evitar fugas de compresión, lubricación y refrigeración.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Controlar el encendido de la bujía.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Reducir la fricción entre las piezas del motor.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 8,
          texto:
            '¿Por qué se requiere una tensión previa en los muelles de las válvulas al ser instalados?',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Para evitar que la válvula se quede abierta.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Para mejorar la refrigeración del motor.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Para reducir el ruido del motor.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Para facilitar el encendido del motor.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 9,
          texto:
            '¿Cómo se logra la sincronización entre el eje de levas y el cigüeñal?',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Ajustando manualmente las válvulas.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Mediante un sistema de engranajes, cadena o banda.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Aumentando la presión del combustible.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Disminuyendo la cantidad de aceite en el motor.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 10,
          texto:
            '¿Cuál es la principal función de las cámaras de combustión en la culata?',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Alojar la combustión de la mezcla aire-combustible y generar la fuerza del motor.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Regular la temperatura del motor.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Facilitar la mezcla de aire y combustible.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Aumentar la potencia del motor.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
      ],
      mensaje_final_aprobado: '¡Excelente! Ha superado la actividad.',
      mensaje_final_reprobado:
        'Le recomendamos volver a revisar el componente formativo e intentar nuevamente la actividad didáctica.',
    },
  }),
}
</script>
