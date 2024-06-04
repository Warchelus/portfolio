<script>
    import PriceTableCard from './PriceTableCard.svelte';
  
    const cards = [
      { priceTier: 'Basic', price: '$9.99/month', features: ['Group Runs', '5, 1-hour sessions per week'] },
      { priceTier: 'Standard', price: '$19.99/month', features: ['Video Analysis', '5, 2-hour sessions per week'] },
      { priceTier: 'Premium', price: '$29.99/month', features: ['Field Event Help', '7, 2-hour sessions per week', 'Apart of Club Team', 'Compete for Club', 'Travel Fees Covered'] }
    ];
  </script>
  
  <style>
    .grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 20px;
    }
  </style>
  
  <div class="grid">
    {#each cards as card, i}
      <PriceTableCard
        priceTier={card.priceTier}
        price={card.price}
        features={card.features}
      />
   {/each}
  </div>