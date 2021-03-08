<template>
  <splide :options="options">
    <splide-slide
      v-for="({ title, description, img, link }, index) in slides"
      :key="index"
    >
      <a class="slide-box" :href="link" target="_blank">
        <img :src="require(`~/assets/img/pepe/${img}`)" />
        <h3>{{ title }}</h3>
        <p>{{ description }}</p>
      </a>
    </splide-slide>
  </splide>
</template>

<script>
export default {
  data() {
    return {
      slides: [
        {
          title: 'Relax Pepe #001',
          description: 'Original Relax Pepe',
          img: '1.svg',
          link: 'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:54:0x83fa662610b204080bcdbf1345905d86744a7495',
        },
        {
          title: 'Relax Pepe #002',
          description: 'Relax Pepe 2',
          img: '002.png',
          link: 'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:54:0x83fa662610b204080bcdbf1345905d86744a7495',
        },
        {
          title: 'Relax Pepe #003',
          description: 'Original Relax Pepe',
          img: '003.png',
          link: 'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:54:0x83fa662610b204080bcdbf1345905d86744a7495',
        },
        {
          title: 'Relax Pepe #004',
          description: 'Original Relax Pepe',
          img: '004.png',
          link: 'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:54:0x83fa662610b204080bcdbf1345905d86744a7495',
        },
      ],
      options: {
        type: 'loop',
        perPage: 3,
        pagination: false,
        arrow: true,
        width: 1023,
        arrowPath: 'M16.5,11l9,9-9,9',
        breakpoints: {
          575: {
            perPage: 1,
            width: '100%',
            arrows: false,
          },
          991: {
            perPage: 1,
            width: 346,
            arrows: true,
          },
          1300: {
            perPage: 2,
            width: 682,
            arrows: true,
          },
        },
      },
    }
  },
}
</script>
