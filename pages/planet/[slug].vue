<template>
  <vue-app>
    <div>
      <!-- <img :src="planet.image" alt=""> -->
      <!-- <h1>{{ planet.title }}</h1> -->
      {{ $params.slug }}
    </div>
  </vue-app>
</template>

<script>
// export default {
// 	name: 'MarsPage',
// 	async asyncData({ params }) {
// 		const planet = await fetch(
// 			`https://api.nuxtjs.dev/planets/mars`
// 		)
// 		.then((res) => {
//       console.log(res.json());
// 			return res.json();
// 		})
// 		.catch((err) => {
// 			console.log(err)
// 		})

// 		return {
// 			planet
// 		}
// 	},
// }
</script>
