<script setup>
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
    <template #heading>Ubicacion del telefono</template>
    La aplicación requere permisos de Ubicacion.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Acceso a camara</template>
    La aplicaión requiere de permisos de camara para acceder a la camara
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Galeria</template>
    La aplicación podra acceder a su Galeria
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Descargar</template>

    Puedes descargar la aplicación en MEGA
    <a href="https://mega.nz/file/dHEEFbrb#sWm9Kc8pb8FD2EUOjQhWV3aEZePcIYneF1iEtxjZMkY" target="_blank" rel="noopener">Practic4U3</a>
  </WelcomeItem>
</template>
