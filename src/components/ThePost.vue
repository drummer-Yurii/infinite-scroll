<template>
  <article>
    <h2>Naruto</h2>
    <p>
      Lorem ipsum dolor sit amet consectetur, adipisicing elit. Alias ipsam reprehenderit similique
      ut et, nisi cumque nostrum odit temporibus quasi!
    </p>
  </article>
</template>

<script>
export default {
  name: 'ThePost',
  props: ['anime'],
};
</script>

<style scoped>
article {
  background-color: #efefef;
  border-radius: 1rem;
  padding: 1rem 2rem;
  box-shadow: 0px 3px 6px rgba(0, 0, 0, 0.2);
  margin-bottom: 2rem;
  color: #2c3e50;
}

article h2 {
    margin-bottom: 1rem;
}
</style>
