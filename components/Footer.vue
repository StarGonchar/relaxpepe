<template>
  <footer class="footer">
    <div class="links">
      <template v-for="{ name, link } in links">
        <a :key="name" :href="link" class="link" target="_blank">
          <span :class="['icon']">
            <img :src="require(`~/assets/img/social/${name}.svg`)" alt="" />
          </span>
        </a>
      </template>
    </div>
  </footer>
</template>

<script>
export default {
  data() {
    return {
      links: [
        {
          name: 'twitter',
          link: 'https://twitter.com/pepe_relax',
        },
        {
          name: 'rarible',
          link: 'https://rarible.com/relaxpepe',
        },
      ],
    }
  },
}
</script>
