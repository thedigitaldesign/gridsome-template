<page-query>
  query Blog($id: ID!) {
    data: blog(id: $id) {
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