<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Resumen</template>
    Esta aplicación ha sido desarrollada por juanpivl y está diseñada para ofrecer entretenimiento al usuario. Valoramos
    la
    privacidad de nuestros usuarios y queremos asegurarnos de que comprendan cómo manejamos sus datos personales.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Recoleccion de Datos</template>
    Queremos asegurar a todos nuestros usuarios que esta aplicación no recopila, almacena ni transmite ninguna
    información
    personal. No solicitamos ni recopilamos datos como nombres, direcciones de correo electrónico, ubicaciones, ni
    ninguna
    otra información de identificación personal.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Acceso a internet</template>
    Nuestra aplicación no requiere ni utiliza acceso a Internet para funcionar. Todas las funcionalidades están
    disponibles sin necesidad de conexión a la red, garantizando así que no haya transmisión de datos a través de
    Internet.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Permisos Solicitados</template>
    Para el correcto funcionamiento de la aplicación, es posible que solicitemos permisos específicos del dispositivo.
    Sin
    embargo, estos permisos son estrictamente necesarios para ofrecer la funcionalidad principal de la aplicación y no
    implican la recopilación de información personal.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Cambios en la Politica de Privacidad</template>
    Nos reservamos el derecho de actualizar o cambiar nuestra Política de Privacidad en cualquier momento. Se recomienda
    revisar este documento periódicamente para estar al tanto de cualquier cambio. Las modificaciones a esta política
    serán efectivas una vez publicadas en esta página.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Contacto</template>
    Si tienes alguna pregunta o inquietud sobre nuestra Política de Privacidad, por favor contacta con nosotros a través
    de juanpivl@hotmail.com .
  </WelcomeItem>

</template>
