<template>
  <div>category page Olaplex</div>
</template>
<script>
export default {
  // asyncData({ $axios }) {
  //   return $axios
  //     .get(
  //       `https://api.mycolors.com/rest/kw_en/V2/products/filters?categoryId=${this.$route.params.id}`
  //     )
  //     .then((response) => {
  //       return {
  //         product: response.data,
  //       }
  //     })
  // },

  head() {
    return {
      title: 'Olaplex Mycolors',

      meta: [
        {
          hid: 'description',
          name: 'description',
          content:
            "Shop OLAPLEX's Exclusive and Latest Collection. Online Shopping for Men Hamad Al-Mubarak Street, Salmiya, Hawally, Kuwait at MyColors - my colors.",
        },
      ],
    }
  },
}
</script>
