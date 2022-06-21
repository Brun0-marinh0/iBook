<template>
    <div class="presentation">
        <p>
            Lorem ipsum dolor sit amet. Ad repellendus amet et sapiente nemo vel aspernatur sint et tempore omnis non velit soluta et expedita galisum. Et temporibus facilis aut molestiae molestias et repudiandae sunt cum esse deserunt. Sit aperiam nesciunt non ipsum architecto et error assumenda aut ipsam natus. Qui unde cumque ea amet dolorem ex pariatur nihil At ullam exercitationem a animi voluptatem. Aut libero laborum et sequi eius eos enim magni aut quibusdam doloribus sit laborum sunt vel molestias quia qui  sunt. Est dolore corporis sit rerum voluptas qui repellendus expedita At autem rerum et quis assumenda. At odit earum ab quia natus et similique praesentium eos veritatis molestias non iusto dolor et nihil itaque ut corporis explicabo! Qui quis voluptas aut consequatur quam ut enim galisum quo atque mollitia eum cupiditate fuga et corporis odit. Ut cupiditate reiciendis 33 ipsam laboriosam aut voluptatum nihil ad reiciendis sunt? Vel illum autem qui ipsa esse et eius veniam cum iure provident id voluptatibus nemo eum aperiam reprehenderit. Quis voluptas ut voluptatem iure in minus voluptatem. 
        </p>
        <img src="@/assets/img/presentation.svg" alt="Apresentação do iBook">
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