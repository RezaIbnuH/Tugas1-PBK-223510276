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
    <template #heading>Tentang Saya</template>
    saya adalah pria yang suka bermain futsal, saya menjuarai turnamen milad dan ifc dan saya pernah meraih milad mvp ml di milad ti 2022
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Pendidikan</template>

    SDS WAHIDIN BAGAN SIAPI-API 2010-2016<br />
    SMPS WAHIDIN BAGAN SIAPI-API 2016-2019<br />
    SMKS LABOR PEKANBARU 2019-2022<br />
    UNIVERSITAS ISLAM RIAU 2022-NOW
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Pengalaman</template>
    Magang di TOKO BESS KOMPUTER PEKANBARU Maret 2021-Juni 2021
    <ul>
      <li>INSTAL ULANG LAPTOP</li>
      <li>MEMBELI ALAT-ALAT UNTUK TOKO</li>
      <li>Menyeting Access point</li>
    </ul>
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Skill</template>
    <ul>
      <li>Pemasangan jaringan komputer</li>
      <li>IoT(Internet Of Things)</li>
    </ul>
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Hubungi Saya</template>

    Instagram :<a href="https://www.instagram.com/lkmnbasa/" target="_blank">lkmnbasa </a
    ><br />
    Email : lukmanbsha21@gmail.com<br />
    No HP : 081234567924
  </WelcomeItem>
</template>