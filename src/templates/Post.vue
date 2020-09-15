<page-query>
  query post($id: ID!) {
    data: post(id: $id) {
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