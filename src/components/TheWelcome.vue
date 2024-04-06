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
    <template #heading>Data Diri</template>
    Namaku rehan tifanno, bisa dipanggil apa aja. Asal jangan dulu di panggil yang maha kuasa, soalnya one piece belum tamat:"
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Keahlian</template>
    Tetap fastrespon balas chat walaupun di balasnya lama.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Hobi</template>
    Memancing. Memancing keributan hehe.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Asal</template>
    Saya asli warga pribumi pekanbaru yang tinggal di daerah panam.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Sosial Media</template>
    <a href="https://www.instagram.com/rehantifanno?utm_source=ig_web_button_share_sheet&igsh=ZDNlZDc0MzIxNw==">Rehan Tifanno</a>
  </WelcomeItem>
</template>
