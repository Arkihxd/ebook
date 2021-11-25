<template>
  <div class="presentation">
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sed, eum non. Eveniet error quibusdam nostrum debitis eum architecto, tempore soluta impedit dicta maxime laborum officia. Accusamus hic suscipit maxime illum. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Amet tenetur repellat quia dignissimos eius illum voluptates, corporis ea adipisci, similique accusamus optio quae, inventore earum quaerat illo aperiam eligendi obcaecati. Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti nemo iusto ullam maiores vero, sit dolores! Magni et ullam dolorum cum dolores, cupiditate alias distinctio incidunt totam nobis laborum provident!
    </p>
    <img src="@/assets/img/presentation.svg" alt=" presentation eBook">
  </div>
</template>

<style lang="scss" scoped>
.presentation {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  grid-gap: 2rem;
  align-items: center;
  @include screen('small', 'medium') {
    grid-template-columns: 1fr;
  }
  p {
    line-height: 26px;
  }
  img {
    max-width: 100%;
  }
}
</style>
