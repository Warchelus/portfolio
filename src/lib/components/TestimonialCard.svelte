<!-- TestimonialCard.svelte -->

<script>
    export let quote = 'Quote placeholder.';
    export let name = 'John Doe';
    export let role = 'CEO';
    export let company = 'Company Name';
    export let logo = 'https://via.placeholder.com/150';
  </script>
  
  <div class="testimonial-card">
    <div class="testimonial-content">
      <div class="testimonial-logo">
        <img alt="company logo" src={logo} />
      </div>
      <div class="testimonial-text">
        <p><em>{quote}</em></p>
        <p class="testimonial-name">{name}</p>
        <p class="testimonial-role">{role} at {company}</p>
      </div>
    </div>
  </div>
  
  <style>
    .testimonial-card {
      width: 100%;
      padding: 16px;
    }
    .testimonial-content {
      background-color: #fff;
      border-radius: 8px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      padding: 16px;
      display: flex;
      flex-direction: column;
      align-items: center;
      text-align: center;
    }
    .testimonial-logo img {
      border-radius: 50%;
      width: 96px;
      height: 96px;
      margin-bottom: 16px;
    }
    .testimonial-text p {
      margin: 8px 0;
    }
    .testimonial-name {
      font-weight: bold;
    }
    .testimonial-role {
      font-style: italic;
    }
  </style>
  