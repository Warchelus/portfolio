<!-- PriceTableCard.svelte -->

<script>
    export let priceTier;
    export let price;
    export let features;
  </script>
  
  <style>
    .card {
      border: 1px solid #ccc;
      border-radius: 8px;
      padding: 20px;
      text-align: center;
    }
  
    .price {
      font-size: 24px;
      font-weight: bold;
      margin-bottom: 10px;
    }
  
    .features {
      text-align: left;
    }
  
    .features li {
      margin-bottom: 5px;
    }
  </style>
  
  <div class="card">
    <h3>{priceTier}</h3>
    <div class="price">{price}</div>
    <ul class="features">
      {#each features as feature}
        <li>{feature}</li>
      {/each}
    </ul>
  </div>
  