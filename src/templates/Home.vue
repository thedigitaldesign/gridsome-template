<page-query>
  query Home($id: ID!) {
    home: home(id: $id) {
      heroText { code }
    }
  }
</page-query>

<template>
  <Layout>
    {{ $page.home.heroText.code }}
  </Layout>
</template>

<script>
export default {}
</script>

<style></style>
