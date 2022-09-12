<template>
  <section class="section">
    <h1 class="title"></h1>
<div> 
    <div class="columns mt-4"> 
      <div class="column is-3">
        <figure class="image is-300x300">
           <b-image class="image"  :src="require('@/assets/4.jpg')"></b-image>
        </figure>

      </div>

      
      <div class="column is-6">
      <div
        <h1 class="title is-1" style=background-color:#E1E12> Camiseta Pumba Básica</h1>

        <article class="message">
          
            <div class="message-body">
             Cor: <strong> Preta </strong> <br>
             Tamanhos disponíveis: <strong>(P) (M) (G)</strong>
            </div>
        </article>

        
      </div>
      

      
      <div class="column is-3 mt-4">
        <h1 class="title is-1  has-text-centered"> R$99,90</h1>
       <b-button tag="router-link" expanded :to="{ path: '/Carrinho' }" type="is-primary">Adicionar ao carrinho</b-button>
     
       
      </div>

     
    </div>

</div>   

  <div> 
    <div class="columns mt-4"> 
      <div class="column is-3">
        <figure class="image is-300x300">
           <b-image class="image"  :src="require('@/assets/11.jpg')"></b-image>
        </figure>

      </div>

      
      <div class="column is-6">
      <div
        <h1 class="title is-1" style=background-color:#E1E12>Moletom com capuz</h1>

        <article class="message">
          
            <div class="message-body">
             Cor: <strong> Amarelo </strong> <br>
             Tamanhos disponíveis: <strong>(P) (M) (GG)</strong>
            </div>
        </article>

        
      </div>
      

      
      <div class="column is-3 mt-4">
        <h1 class="title is-1  has-text-centered"> R$249,90</h1>
        <b-button type="is-primary" expanded>Adicionar ao carrinho</b-button>
     
       
      </div>

     
    </div>

</div>   

    <div> 
    <div class="columns mt-4"> 
      <div class="column is-3">
        <figure class="image is-300x300">
           <b-image class="image"  :src="require('@/assets/10.jpg')"></b-image>
        </figure>

      </div>

      
      <div class="column is-6">
      <div
        <h1 class="title is-1" style=background-color:#E1E12>Pumba X Converse</h1>

        <article class="message">
          
            <div class="message-body">
             Cor: <strong> Preto </strong> <br>
             Tamanhos disponíveis: <strong>(38) (39) (40)</strong>
            </div>
        </article>

        
      </div>
      

      
      <div class="column is-3 mt-4">
        <h1 class="title is-1  has-text-centered"> R$379,90</h1>
        <b-button type="is-primary" expanded>Adicionar ao carrinho</b-button>
     
       
      </div>

     
    </div>

</div>   

      <div> 
    <div class="columns mt-4"> 
      <div class="column is-3">
        <figure class="image is-300x300">
           <b-image class="image"  :src="require('@/assets/9.jpg')"></b-image>
        </figure>

      </div>

      
      <div class="column is-6">
      <div
        <h1 class="title is-1  has-text-centered" style=background-color:#E1E12> Timão Classic White</h1>

        <article class="message">
          
            <div class="message-body">
             Cor: <strong> Branco </strong> <br>
             Tamanhos disponíveis: <strong>(36) (39) (42)</strong>
            </div>
        </article>

        
      </div>
      

      
      <div class="column is-3 mt-4">
        <h1 class="title is-1  has-text-centered"> R$499,90</h1>
        <b-button type="is-primary" expanded>Adicionar ao carrinho</b-button>
     
       
      </div>

     
    </div>

</div>   
  </section>
</template>