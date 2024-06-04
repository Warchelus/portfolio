<!-- TestimonialGrid.svelte -->

<script>
    import TestimonialCard from './TestimonialCard.svelte';
  </script>
  
  <section class="testimonial-grid">
    <div class="grid-container">
      <TestimonialCard
        company="Company"
        logo="https://lh3.googleusercontent.com/a-/ALV-UjVxz_dgSweAw-XAhcJS7KoHbdJT2X9Llz4_6wjZ0gvzvInv2jV9=s75-c"
        name="Michael Linane"
        quote="Product is so great! I lost my big belly in only 2 weeks!"
        role="CEO"
      />
      <TestimonialCard
        company="Company"
        logo="https://lh3.googleusercontent.com/a-/ALV-UjVADjn1ZiS6fyIg0RHYjNogP2KAN3K0dF85x7foxACoVl-o39s=s75-c"
        name="Lauren Millette"
        quote="With this product, I can finally wear my favorite dress again!"
        role="CTO"
      />
      <TestimonialCard
        company="Company"
        logo="https://lh3.googleusercontent.com/a-/ALV-UjXjYgZZwKTInXU1GDCmP7YVDqgkMcA_u2aaz8o_Smb9CCohMPNh=s75-c"
        name="Lindsay Tallman"
        quote="This product is amazing! I feel so much healthier and happier now!"
        role="CFO"
      />
      <!-- Add more TestimonialCard components as needed -->
    </div>
  </section>
  
  <style>
    .testimonial-grid {
      padding: 40px 0;
      display: flex;
      justify-content: center;
    }
    .grid-container {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 16px;
      width: 75%;
    }
  </style>
  