<page-query>
  query Home($id: ID!) {
    data: home(id: $id) {
      heroText { code }
    }
  }
</page-query>

<template>
  <Layout>
    {{ $page.data.heroText.code }}
  </Layout>
</template>

<script>
export default {}
</script>

<style></style>
