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
          title: 'Relax Pepe #050',
          description: 'ZombiePepe v.2.0 [Unique]',
          img: '55.jpg',
          link:
            'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:75:0x83fa662610b204080bcdbf1345905d86744a7495',
        },
    {
          title: 'Relax Pepe #049',
          description: 'MexicanPepe [Rare]',
          img: '56.jpg',
          link:
            'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:74:0x83fa662610b204080bcdbf1345905d86744a7495',
        },
    {
          title: 'Relax Pepe #048',
          description: 'MoodPepe [Common]',
          img: '57.jpg',
          link:
            'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:73:0x83fa662610b204080bcdbf1345905d86744a7495',
        },
     {
          title: 'Relax Pepe #047',
          description: 'Pepes Home [Rare]',
          img: '53.jpg',
          link:
            'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:71:0x83fa662610b204080bcdbf1345905d86744a7495',
        },
      {
          title: 'Relax Pepe #046',
          description: 'OgrePepe [Common]',
          img: '54.jpg',
          link:
            'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:68:0x83fa662610b204080bcdbf1345905d86744a7495',
        },
       {
          title: 'Relax Pepe #045',
          description: 'DogePepe [Unique]',
          img: '52.jpg',
          link:
            'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:66:0x83fa662610b204080bcdbf1345905d86744a7495',
        },
       {
          title: 'Relax Pepe #044',
          description: 'The Queen [Rare]',
          img: '51.jpg',
          link:
            'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:65:0x83fa662610b204080bcdbf1345905d86744a7495',
        },
        {
          title: 'Relax Pepe #043',
          description: 'ZombiePepe(Rare)',
          img: '49.jpg',
          link:
            'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:64:0x83fa662610b204080bcdbf1345905d86744a7495',
        },
        {
          title: 'Relax Pepe #042',
          description: 'ZombiePepe',
          img: '48.jpg',
          link:
            'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:62:0x83fa662610b204080bcdbf1345905d86744a7495',
        },
        {
          title: 'Relax Pepe #041',
          description: 'MrCookiesPepe',
          img: '45.jpg',
          link:
            'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:61:0x83fa662610b204080bcdbf1345905d86744a7495',
        },
        {
          title: 'Relax Pepe #040',
          description: 'MinerPepe',
          img: '46.jpg',
          link:
            'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:60:0x83fa662610b204080bcdbf1345905d86744a7495',
        },
        {
          title: 'Relax Pepe #039',
          description: 'GhostPepe',
          img: '44.png',
          link:
            'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:59:0x83fa662610b204080bcdbf1345905d86744a7495',
        },
        {
          title: 'Relax Pepe #038',
          description: 'DetectivePepe',
          img: '43.jpg',
          link:
            'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:58:0x83fa662610b204080bcdbf1345905d86744a7495',
        },
        {
          title: 'Relax Pepe #037',
          description: 'The King',
          img: '42.png',
          link:
            'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:57:0x83fa662610b204080bcdbf1345905d86744a7495',
        },
        {
          title: 'Relax Pepe #036',
          description: 'SnowWhitePepe',
          img: '39.png',
          link:
            'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:56:0x83fa662610b204080bcdbf1345905d86744a7495',
        },
        {
          title: 'Relax Pepe #035',
          description: 'LocPepe',
          img: '40.png',
          link:
            'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:55:0x83fa662610b204080bcdbf1345905d86744a7495',
        },
        {
          title: 'Relax Pepe #034',
          description: 'HippiePepe',
          img: '41.png',
          link:
            'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:54:0x83fa662610b204080bcdbf1345905d86744a7495',
        },
        {
          title: 'Relax Pepe #033',
          description: 'HellPepe',
          img: '37.png',
          link:
            'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:52:0x83fa662610b204080bcdbf1345905d86744a7495',
        },
        {
          title: 'Relax Pepe #032',
          description: 'PepeRick',
          img: '36.png',
          link:
            'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:50:0x1f87338e6689159fbbce349230b4087cdd18e838',
        },
        {
          title: 'Relax Pepe #031',
          description: 'PepePunk',
          img: '38.png',
          link:
            'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:49:0x5bf4b5dd92918f496230726877e28714fad8abc8',
        },
        {
          title: 'Relax Pepe #030',
          description: 'Kitty',
          img: '35.png',
          link:
            'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:43:0xa84944735b66e957fe385567dcc85975022fe68a',
        },
        {
          title: 'Relax Pepe #029',
          description: "HonkHonk's Grandfather",
          img: '34.png',
          link:
            'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:41:0x0be425067baf65e8cf63077ec1bb1e6038715d73',
        },
        {
          title: 'Relax Pepe #028',
          description: 'Honk Honk',
          img: '33.png',
          link:
            'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:40:0x9ed3db7a8ec964ef0813edb7bf3ff514a25fae70',
        },
        {
          title: 'Relax Pepe #027',
          description: 'Super Relax Pepe Hero SE',
          img: '31.png',
          link:
            'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:39:0x1f87338e6689159fbbce349230b4087cdd18e838',
        },
        {
          title: 'Relax Pepe #026',
          description: 'ShaoPepe',
          img: '030.png',
          link:
            'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:34:0xf20749dbec0426f0323b6e686629f3b517dd4799',
        },
        {
          title: 'Relax Pepe #025',
          description: 'ReptilePepe',
          img: '029.png',
          link:
            'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:33:0x9ed3db7a8ec964ef0813edb7bf3ff514a25fae70',
        },
        {
          title: 'Relax Pepe #024',
          description: 'SubZeroPepe',
          img: '028.png',
          link:
            'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:32:0x9ed3db7a8ec964ef0813edb7bf3ff514a25fae70',
        },
        {
          title: 'Relax Pepe #023',
          description: 'ScorpionPepe',
          img: '027.png',
          link:
            'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:31:0xf20749dbec0426f0323b6e686629f3b517dd4799',
        },
        {
          title: 'Relax Pepe #022',
          description: 'StellarMiragePepe',
          img: '025.png',
          link:
            'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:28:0x9ed3db7a8ec964ef0813edb7bf3ff514a25fae70',
        },
        {
          title: 'Relax Pepe #021',
          description: 'JasonPepe',
          img: '026.png',
          link:
            'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:30:0x9ed3db7a8ec964ef0813edb7bf3ff514a25fae70',
        },
        {
          title: 'Relax Pepe #020',
          description: 'PiratePepe',
          img: '023.png',
          link:
            'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:25:0xc9bd470a494e002aecbbbf73ca5bd8a2807f296b',
        },
        {
          title: 'Relax Pepe #019',
          description: 'Relax Pepe Never Sleeps',
          img: '024.png',
          link:
            'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:24:0x5be10f3434bc1ac6c0a34f86da39ea0095392f21',
        },
        {
          title: 'Relax Pepe #018',
          description: 'PepeMusk',
          img: '006.png',
          link:
            'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:23:0x9ed3db7a8ec964ef0813edb7bf3ff514a25fae70',
        },
        {
          title: 'Relax Pepe #017',
          description: 'CyberPepe (ETH edition)',
          img: '022.png',
          link:
            'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:21:0x9ed3db7a8ec964ef0813edb7bf3ff514a25fae70',
        },
        {
          title: 'Relax Pepe #016',
          description: 'Mini Pepe',
          img: '021.png',
          link:
            'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:20:0x9ed3db7a8ec964ef0813edb7bf3ff514a25fae70',
        },
        {
          title: 'Relax Pepe #015',
          description: "It's time",
          img: '020.png',
          link:
            'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:17:0x3075dc76f1b6d386ca784a53a55ead34b9ff8b26',
        },
        {
          title: 'Relax Pepe #014',
          description: "It's time",
          img: '019.png',
          link:
            'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:16:0xb6e03b2e86d2e128ac2ae16f8864e33f00a9d404',
        },
        {
          title: 'Relax Pepe #013',
          description: 'Dark Pepe',
          img: '017.png',
          link:
            'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:15:0x9ed3db7a8ec964ef0813edb7bf3ff514a25fae70',
        },
        {
          title: 'Relax Pepe #012',
          description: 'Light Pepe',
          img: '018.png',
          link:
            'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:14:0x9ed3db7a8ec964ef0813edb7bf3ff514a25fae70',
        },
        {
          title: 'Relax Pepe #011',
          description: 'Space Pepe',
          img: '016.png',
          link:
            'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:13:0xe6b221eb84084cbf557465cb8972ce2eaca59382',
        },
        {
          title: 'Relax Pepe #010',
          description: 'UniPepe',
          img: '014.png',
          link:
            'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:10:0xe6b221eb84084cbf557465cb8972ce2eaca59382',
        },
        {
          title: 'Relax Pepe #009',
          description: 'BitLaser Pepe',
          img: '015.png',
          link:
            'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:9:0x9ed3db7a8ec964ef0813edb7bf3ff514a25fae70',
        },
        {
          title: 'Relax Pepe #008',
          description: 'Curio Team',
          img: '011.png',
          link:
            'https://rarible.com/token/0x60f80121c31a0d46b5279700f9df786054aa5ee5:174362:0x86f12d22052e0f351f99de75cceecbccee42af74',
        },
        {
          title: 'Relax Pepe #007',
          description: 'Curio Team',
          img: '013.png',
          link:
            'https://rarible.com/token/0x60f80121c31a0d46b5279700f9df786054aa5ee5:174335:0x86f12d22052e0f351f99de75cceecbccee42af74',
        },
        {
          title: 'Relax Pepe #006',
          description: 'Curio Team',
          img: '010.png',
          link:
            'https://rarible.com/token/0x60f80121c31a0d46b5279700f9df786054aa5ee5:174280:0x86f12d22052e0f351f99de75cceecbccee42af74',
        },
        {
          title: 'Relax Pepe #005',
          description: 'Pensive Pepe',
          img: '002.png',
          link:
            'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:8:0x6c183ee7ae606b69ba71a940c0b827bbf1de3589',
        },
        {
          title: 'Relax Pepe #004',
          description: 'The King of the Pepe',
          img: '004.png',
          link:
            'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:6:0x9ed3db7a8ec964ef0813edb7bf3ff514a25fae70',
        },
        {
          title: 'Relax Pepe #003',
          description: 'PikaPepe',
          img: '007.png',
          link:
            'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:4:0x6c183ee7ae606b69ba71a940c0b827bbf1de3589',
        },
        {
          title: 'Relax Pepe #002',
          description: 'This is fine',
          img: '003.png',
          link:
            'https://rarible.com/token/0x60f80121c31a0d46b5279700f9df786054aa5ee5:174749:0x6c183ee7ae606b69ba71a940c0b827bbf1de3589',
        },
        {
          title: 'Relax Pepe #001',
          description: 'Original Relax Pepe',
          img: '001.png',
          link:
            'https://rarible.com/token/0x79741245a85b6ef4d22cf928b87ee69ef6f872c6:2:0x9ed3db7a8ec964ef0813edb7bf3ff514a25fae70',
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
