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
    <template #heading>Tujuan</template>
    Tujuan tugas ini dibuat untuk memenuhi tugas Praktikum Pemrograman Berbasis Komponen atau disebut dengan PBK.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Profil</template>
    <table id="data">
      <tr>
        <th>Nama Lengkap</th>
        <th>Nama Panggilan</th>
        <th>Tempat, Tanggal Lahir</th>
        <th>Pendidikan</th>
      </tr>

      <tr>
        <td>Syakirah Qanitah</td>
        <td>Syakirah</td>
        <td>Pekanbaru, 09 September 2004</td>
        <td>Universitas Islam Riau (UIR)</td>
      </tr>
    </table>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Data Hobi</template>
    Saya mempunyai hobi seperti sebagai
    berikut ini :<br />
    <ul>
      <li>Bermain Basket</li>
      <li>Membaca Buku</li>
      <li>Nonton NBA</li>
    </ul>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Warna Kesukaan :</template>
    <ol>
      <li>Putih</li>
      <li>Hitam</li>
      <li>Merah</li>
      <li>Pink</li>
    </ol>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Hubungi</template>
    WA : 08-123-....<br />
  </WelcomeItem>
</template>
