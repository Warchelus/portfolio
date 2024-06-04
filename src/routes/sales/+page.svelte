<script>
    import Hero from '$lib/components/Hero.svelte';
	import Longdescription from '../../lib/components/Longdescription.svelte';
	import PriceTableGrid from '../../lib/components/PriceTableGrid.svelte';
	import TestimonialGrid from '../../lib/components/TestimonialGrid.svelte';
	import TrustedByGrid from '../../lib/components/TrustedByGrid.svelte';
    </script>
  
  <Hero title="sales page"></Hero>
  <section class="content">
    <Longdescription></Longdescription>
    <PriceTableGrid></PriceTableGrid>
    <TestimonialGrid></TestimonialGrid>
    <TrustedByGrid></TrustedByGrid>
  </section>

    <style>
        .content {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            max-width: 64rem;
            margin: 0 auto;
            padding: 2rem 0;
        }
    </style>