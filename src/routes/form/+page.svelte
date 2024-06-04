<script>
  import Hero from '$lib/components/Hero.svelte';
  </script>

<Hero title="form page"></Hero>
<section class="content">
<p>
    This is the form page
</p>

    <form action="submit">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name"><br><br>
        <label for="email">Email:</label>
        <input type="email" id="email" name="email"><br><br>
        <label for="message">Message:</label><br>
        <textarea id="message" name="message"></textarea><br><br>
        <input type="submit" value="Submit">
    </form>
    
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