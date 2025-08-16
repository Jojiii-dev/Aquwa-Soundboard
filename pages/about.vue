<template>
  <div>
    <VCard>
      <VCardTitle>
        <span class="text-3xl">Aquwa Soundboard</span>
      </VCardTitle>
      <VCardText class="text-lg">
        <ul class="list-disc pl-6">
          <p>
            Thanks for visiting my little soundboard site. I hope you enjoyed
            it. None of the sounds are AI and they are all from Aquwa
          </p>
          <li>
            Created by:
            <a class="link" href="https://x.com/Jojiii_dev" target="_blank">
              Jojiii
            </a>
          </li>
          <li>Contributors: M9W</li>
          <li>
            Sound file Sources: Twitch VOD/Clip, Youtube videoes/clips,
            Crewmates
          </li>

          <li>
            Template originally made by:
            <a class="link" href="https://konnokai.me/" target="_blank">
              孤之界
            </a>
            ,
            <a class="link" href="https://twitter.com/7Red4" target="_blank">
              紅柿
            </a>
            ,
            <a
              class="link"
              href="https://github.com/kujyonatsume"
              target="_blank"
            >
              九条夏目
            </a>
          </li>
        </ul>
      </VCardText>
    </VCard>
  </div>
</template>
<script setup lang="ts"></script>

<style scoped>
.link {
  @apply text-primary-500 underline;
}

ul * {
  @apply text-lg;
}
</style>
