<page-query>
  query Pages($id: ID!) {
    data: pages(id: $id) {
      title
    }
  }
</page-query>

<template>
  <Layout>
    <div class="container max-w-full">
      {{ $page.data.title }}
    </div>
  </Layout>
</template>

<script>
export default {

}
</script>

<style>

</style>