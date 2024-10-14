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
    <template #heading>Introducción</template>
    Bienvenidos a speedTest, una aplicación dedicada a proporcionar pruebas de velocidad de internet confiables y
    eficientes. Valoramos la privacidad de nuestros usuarios y nos comprometemos a protegerla. Esta política de
    privacidad explica cómo speedTest maneja y protege la información de sus usuarios.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Información Recopilada</template>
    speedTest no recopila ni almacena datos personales de sus usuarios. La aplicación se ha diseñado para funcionar sin
    necesidad de recabar información personal o de identificación.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Uso de la Información</template>
    Dado que speedTest no recopila datos personales, no hay uso de dicha información. La aplicación se utiliza
    exclusivamente para proporcionar mediciones de velocidad de internet y no requiere ni procesa datos personales de
    los usuarios.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Compartir Información con Terceros</template>
    speedTest no comparte ningún dato con terceros, ya que no recopila información personal de sus usuarios.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Seguridad de los Datos</template>
    La seguridad de nuestros usuarios es una prioridad. Al no recopilar datos personales, speedTest asegura que la
    privacidad y seguridad de los usuarios estén protegidas.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Derechos del Usuario</template>
    Dado que no recopilamos datos personales, los derechos típicos relacionados con la privacidad de datos (como acceso,
    rectificación o eliminación) no son aplicables en el contexto de nuestra aplicación.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Cambios en la Política de Privacidad</template>
    Nos reservamos el derecho de modificar estas políticas de privacidad en cualquier momento. Cualquier cambio será
    comunicado adecuadamente a nuestros usuarios y reflejado con una actualización en la fecha de vigencia.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Contacto</template>
    Si tienes preguntas o inquietudes sobre nuestras políticas de privacidad, por favor contáctanos a través de
    juanpivl@hotmail.com.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Cumplimiento Legal</template>
    speedTest se compromete a cumplir con todas las leyes y regulaciones de privacidad aplicables.
  </WelcomeItem>
</template>
