<template>
  <section class="section">
    
    <h1 class="title has-text-centered">Mais vendidos</h1>
    
    <div class="columns">
        <div class="column is-3">
          <h2 class= "subtitle">Filtro:</h2> 
          <section class= "mt-3">
            <p>Tipo:</p>
          <p><b-checkbox>Camisetas</b-checkbox></p>
          <p><b-checkbox>Moletons</b-checkbox></p>
          <p><b-checkbox>Calçados</b-checkbox></p>
          </section>

          <section class= "mt-3">
            <p>Tamanhos:</p>
              <p><b-checkbox>P</b-checkbox></p>
              <p><b-checkbox>M</b-checkbox></p>
              <p><b-checkbox>G</b-checkbox></p>
          </section>

          
        <section class="mt-2">
          <button class="button is-small is-outlined is-black">Aplicar</button> 
        </section>
          
          
        </div>
        <div class="column is-9">
          <div class="columns mt-3 is-multiline">
            <div class="column is-4">
              <article class="notification is-white  has-text-centered">
                 <b-image class="image"  :src="require('@/assets/4.jpg')"></b-image>
                <p class="title">Camiseta Preta</p>
                <p class="subtitle">R$ 99,90</p>
                 <b-button tag="router-link" expanded :to="{ path: '/Descricao' }" type="is-primary">Próximo</b-button>
              </article>
            </div>
            <div class="column is-4">
              <article class="notification is-white has-text-centered">
                <b-image class="image"  :src="require('@/assets/5.jpg')"></b-image>
                <p class="title">Moletom Preto</p>
                <p class="subtitle">R$ 249,90</p>
                <b-button tag="router-link" expanded :to="{ path: '/Descricao' }" type="is-primary">Próximo</b-button>
              </article>
            </div>
            <div class="column is-4">
              <article class="notification is-white has-text-centered">
                <b-image class="image"  :src="require('@/assets/6.jpg')"></b-image>
                <p class="title">Molotom e Calça</p>
                <p class="subtitle">R$ 349,90</p>
                <b-button tag="router-link" expanded :to="{ path: '/Descricao' }" type="is-primary">Próximo</b-button>
              </article>
              
            </div>  
          <div class="column is-4">
              <article class="notification is-white has-text-centered">
                <b-image class="image"  :src="require('@/assets/7.jpg')"></b-image>
                <p class="title">Camiseta Vervelha</p>
                <p class="subtitle">R$ 99,90</p>
                <b-button tag="router-link" expanded :to="{ path: '/Descricao' }" type="is-primary">Próximo</b-button>
              </article>
              
            </div>

          <div class="column is-4">
              <article class="notification is-white has-text-centered">
                <b-image class="image"  :src="require('@/assets/8.jpg')"></b-image>
                <p class="title">Pumba Running X</p>
                <p class="subtitle">R$ 1499,90</p>
                <b-button tag="router-link" expanded :to="{ path: '/Descricao' }" type="is-primary">Próximo</b-button>
              </article>
              
            </div>

            <div class="column is-4">
              <article class="notification is-white has-text-centered">
                <b-image class="image"  :src="require('@/assets/9.jpg')"></b-image>
                <p class="title">Timão Classic White</p>
                <p class="subtitle">R$ 499,90</p>
                <b-button tag="router-link" expanded :to="{ path: '/Descricao' }" type="is-primary">Próximo</b-button>
              </article>    
          </div> 
           <div class="column is-4">
              <article class="notification is-white has-text-centered">
                <b-image class="image"  :src="require('@/assets/10.jpg')"></b-image>
                <p class="title">Pumba X Converse</p>
                <p class="subtitle">R$ 379,90</p>
                <b-button tag="router-link" expanded :to="{ path: '/Descricao' }" type="is-primary">Próximo</b-button>
              </article>    
          </div>
            
        </div>
    </div>
</div>
    
  </section>
</template>

<script>
export default {
  name: 'InspirePage'
}
</script>
