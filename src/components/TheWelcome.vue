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
    <template #heading>Biodata Diri</template>

   Halo! Perkenalkan saya Farah, saya berasal dari Kota Dumai, Riau. Saya merupakan mahasiswa di Universitas Islam Riau.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Skill & Kemampuan</template>

    - Memasak <br>
    - Menari <br>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Pengalaman Yang Pernah Dimiliki</template>

    - Saya pernah mengikuti lomba menari saat TK <br>
    - Saya pernah mengikuti OSN Kimia saat SMA <br>
  </WelcomeItem>

  
 
</template>
