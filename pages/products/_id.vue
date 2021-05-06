<script>
export default {
  async asyncData({ params }) {
    return new Promise((resolve, reject) => {
      setTimeout(() => {
        resolve({
          product: {
            id: params.id,
            name: `Product #${params.id}`,
            description: `This is product #${params.id}.`,
          },
        })
      }, 2000)
    })
  },
}
</script>

<template>
  <div>
    <h2>{{ product.name }}</h2>
    <p>{{ product.description }}</p>
  </div>
</template>
