<script setup lang="ts">
import WelcomeItem from '../components/WelcomeItem.vue'
import DocumentationIcon from '../components/icons/IconDocumentation.vue'
import ToolingIcon from '../components/icons/IconTooling.vue'
import EcosystemIcon from '../components/icons/IconEcosystem.vue'
import CommunityIcon from '../components/icons/IconCommunity.vue'
import SupportIcon from '../components/icons/IconSupport.vue'
</script>

<template>
    <WelcomeItem>
        <template #icon>
            <DocumentationIcon />
        </template>
        <template #heading>Resumen</template>
        Esta aplicación ha sido desarrollada por juanpivl y está diseñada para ofrecer entretenimiento al usuario.
        Valoramos
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
        Para el correcto funcionamiento de la aplicación, es posible que solicitemos permisos específicos del
        dispositivo.
        Sin
        embargo, estos permisos son estrictamente necesarios para ofrecer la funcionalidad principal de la aplicación y
        no
        implican la recopilación de información personal.
    </WelcomeItem>

    <WelcomeItem>
        <template #icon>
            <SupportIcon />
        </template>
        <template #heading>Cambios en la Politica de Privacidad</template>
        Nos reservamos el derecho de actualizar o cambiar nuestra Política de Privacidad en cualquier momento. Se
        recomienda
        revisar este documento periódicamente para estar al tanto de cualquier cambio. Las modificaciones a esta
        política
        serán efectivas una vez publicadas en esta página.
    </WelcomeItem>

    <WelcomeItem>
        <template #icon>
            <SupportIcon />
        </template>
        <template #heading>Contacto</template>
        Si tienes alguna pregunta o inquietud sobre nuestra Política de Privacidad, por favor contacta con nosotros a
        través
        de juanpivl@hotmail.com .
    </WelcomeItem>

</template>


<!-- # Políticas de Privacidad de speedTest


# Introducción
Bienvenidos a speedTest, una aplicación dedicada a proporcionar pruebas de velocidad de internet confiables y eficientes. Valoramos la privacidad de nuestros usuarios y nos comprometemos a protegerla. Esta política de privacidad explica cómo speedTest maneja y protege la información de sus usuarios.

# Información Recopilada
speedTest no recopila ni almacena datos personales de sus usuarios. La aplicación se ha diseñado para funcionar sin necesidad de recabar información personal o de identificación.

# Uso de la Información
Dado que speedTest no recopila datos personales, no hay uso de dicha información. La aplicación se utiliza exclusivamente para proporcionar mediciones de velocidad de internet y no requiere ni procesa datos personales de los usuarios.

# Compartir Información con Terceros
speedTest no comparte ningún dato con terceros, ya que no recopila información personal de sus usuarios.

# Seguridad de los Datos
La seguridad de nuestros usuarios es una prioridad. Al no recopilar datos personales, [Nombre de tu Aplicación] asegura que la privacidad y seguridad de los usuarios estén protegidas.

# Derechos del Usuario
Dado que no recopilamos datos personales, los derechos típicos relacionados con la privacidad de datos (como acceso, rectificación o eliminación) no son aplicables en el contexto de nuestra aplicación.

# Cambios en la Política de Privacidad
Nos reservamos el derecho de modificar estas políticas de privacidad en cualquier momento. Cualquier cambio será comunicado adecuadamente a nuestros usuarios y reflejado con una actualización en la fecha de vigencia.

# Contacto
Si tienes preguntas o inquietudes sobre nuestras políticas de privacidad, por favor contáctanos a través de juanpivl@hotmail.com

# Cumplimiento Legal
speedTest se compromete a cumplir con todas las leyes y regulaciones de privacidad aplicables. -->
