<script setup lang="ts">
import WelcomeItem from '../components/WelcomeItem.vue'
import DocumentationIcon from '../components/icons/IconDocumentation.vue'
import ToolingIcon from '../components/icons/IconTooling.vue'
import EcosystemIcon from '../components/icons/IconEcosystem.vue'
import CommunityIcon from '../components/icons/IconCommunity.vue'
import SupportIcon from '../components/icons/IconSupport.vue'
</script>

<template>
    <main>
        <WelcomeItem>
            <template #icon>
                <DocumentationIcon />
            </template>
            <template #heading>Resumen</template>
            Esta aplicación, "Catch It", ha sido desarrollada por juanpivl y está diseñada para ofrecer una experiencia
            de entretenimiento divertida y desafiante para los usuarios. Valoramos la privacidad de nuestros usuarios y
            queremos asegurarnos de que comprendan cómo manejamos sus datos personales.
        </WelcomeItem>

        <WelcomeItem>
            <template #icon>
                <ToolingIcon />
            </template>
            <template #heading>Recolección de Datos</template>
            Queremos asegurar a todos nuestros usuarios que "Catch It" no recopila, almacena ni transmite ninguna
            información personal. No solicitamos ni recopilamos datos como nombres, direcciones de correo electrónico,
            ubicaciones, ni ninguna otra información de identificación personal. Nuestro enfoque es proporcionar un
            juego sencillo y divertido sin necesidad de interferir en tu privacidad.
        </WelcomeItem>

        <WelcomeItem>
            <template #icon>
                <EcosystemIcon />
            </template>
            <template #heading>Acceso a Internet</template>
            "Catch It" no requiere ni utiliza acceso a Internet para funcionar. Todas las funcionalidades del juego
            están disponibles sin necesidad de conexión a la red, garantizando así que no haya transmisión de datos a
            través de Internet. Puedes disfrutar del juego en cualquier momento y lugar, sin preocupaciones de consumo
            de datos.
        </WelcomeItem>

        <WelcomeItem>
            <template #icon>
                <CommunityIcon />
            </template>
            <template #heading>Permisos Solicitados</template>
            Para el correcto funcionamiento de "Catch It", es posible que solicitemos permisos específicos del
            dispositivo,
            como acceso al almacenamiento o a las notificaciones. Sin embargo, estos permisos son estrictamente
            necesarios
            para ofrecer la funcionalidad principal del juego y no implican la recopilación de información personal.
        </WelcomeItem>

        <WelcomeItem>
            <template #icon>
                <SupportIcon />
            </template>
            <template #heading>Cambios en la Política de Privacidad</template>
            Nos reservamos el derecho de actualizar o cambiar nuestra Política de Privacidad en cualquier momento. Se
            recomienda revisar este documento periódicamente para estar al tanto de cualquier cambio. Las modificaciones
            a esta política serán efectivas una vez publicadas en esta página.
        </WelcomeItem>

        <WelcomeItem>
            <template #icon>
                <SupportIcon />
            </template>
            <template #heading>Contacto</template>
            Si tienes alguna pregunta o inquietud sobre nuestra Política de Privacidad, por favor contacta con nosotros
            a través de juanpivl@hotmail.com.
        </WelcomeItem>
    </main>
</template>
