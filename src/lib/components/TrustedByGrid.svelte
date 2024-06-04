<script>
    export let logos = [
     { src: 'https://www.logo.wine/a/logo/Adidas/Adidas-Logo.wine.svg', alt: 'Adidas' },
     { src: 'data:image/png;base64,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', alt: 'HOKA' },
     { src: 'https://www.logo.wine/a/logo/Brooks_Sports/Brooks_Sports-Logo.wine.svg', alt: 'Brooks' },
     { src: 'https://cdn.shopify.com/s/files/1/0263/6270/8027/files/tenshi-Nike-logo.jpg?v=1584898573', alt: 'Nike' },
     { src: 'https://download.logo.wine/logo/Saucony/Saucony-Logo.wine.png', alt: 'Saucony' },
     { src: 'https://www.logo.wine/a/logo/New_Balance/New_Balance-Logo.wine.svg', alt: 'New Balance' }
    ];
   </script>
   
   <section class="trusted-by-grid">
    <div class="grid-container">
     {#each logos as logo}
      <div class="logo-item">
       <img src={logo.src} alt={logo.alt} />
      </div>
     {/each}
    </div>
   </section>
   
   <style>
    .trusted-by-grid {
      background-color: #1a1a1a;
      padding: 40px 0;
      text-align: center;
    }
    .grid-container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(100px, 1fr));
      gap: 20px;
      justify-items: center;
      align-items: center;
    }
    .logo-item img {
      max-width: 100%;
      height: auto;
      filter: grayscale(100%);
      opacity: 0.7;
      transition: opacity 0.3s;
    }
    .logo-item img:hover {
      opacity: 1;
    }
   </style>
   