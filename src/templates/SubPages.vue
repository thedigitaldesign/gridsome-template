<page-query>
  query SubPages($id: ID!) {
    data: subPages(id: $id) {
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