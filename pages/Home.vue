<template>
  <section class="section">

<!-- carousel com imagens -->
    <b-carousel class="colums mb-5">
      <b-carousel-item>
        <b-image class="image"  :src="require('@/assets/1.jpg')"></b-image>
      </b-carousel-item>
      <b-carousel-item>
        <b-image class="image"  :src="require('@/assets/2.jpg')"></b-image>
      </b-carousel-item>      
      <b-carousel-item>
        <b-image class="image" :src="require('@/assets/3.jpg')"></b-image>
      </b-carousel-item>            
    </b-carousel>

    <h4 class="title is-4">Mais Vendidos</h4>

 <div class="columns mt-3">
      <div class="column is-3">
        <article class="notification is-white  has-text-centered">
           <b-image class="image"  :src="require('@/assets/4.jpg')"></b-image>
          <p class="title">Camisetas</p>
          <p class="subtitle">Básicas</p>
          <b-button tag="router-link" expanded :to="{ path: '/Produtos' }" type="is-primary">Próximo</b-button>
        </article>
      </div>
      <div class="column is-3">
        <article class="notification is-white has-text-centered">
          <b-image class="image"  :src="require('@/assets/5.jpg')"></b-image>
          <p class="title">Moletons</p>
          <p class="subtitle">Clássico</p>
          <b-button tag="router-link" expanded :to="{ path: '/Produtos' }" type="is-primary">Próximo</b-button>
        </article>
      </div>
      <div class="column is-3">
        <article class="notification is-white has-text-centered">
          <b-image class="image"  :src="require('@/assets/6.jpg')"></b-image>
          <p class="title">Moletons</p>
          <p class="subtitle">e Calça</p>
          <b-button tag="router-link" expanded :to="{ path: '/Produtos' }" type="is-primary">Próximo</b-button>
        </article>
        
      </div>  
    <div class="column is-3">
        <article class="notification is-white has-text-centered">
          <b-image class="image"  :src="require('@/assets/9.jpg')"></b-image>
          <p class="title">Calçados</p>
          <p class="subtitle">Esportivos</p>
          <b-button tag="router-link" expanded :to="{ path: '/produtos' }" type="is-primary">Próximo</b-button>
        </article>
        
      </div>
   
    </div> 

<section class="hero is-black">
            <div class="hero-body">
                <p class="title has-text-centered">
                    Just Pumba It
                </p>
            </div>
        </section>  
    
  </section>
</template>

