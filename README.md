
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Responsive Product Cards</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <section class="products-section">
    <h2 class="section-title">Our Featured Products</h2>
    <div class="cards-container">
      <!-- Card 1 (with NEW badge using ::before) -->
      <article class="card badge-new">
        <img src="https://images.unsplash.com/photo-1505740420928-5e560c06d30e?w=500&q=80" alt="Wireless Headphones" class="card-img" />
        <div class="card-content">
          <h3 class="card-title">Wireless Headphones</h3>
          <p class="card-desc">High-fidelity sound with active noise cancellation and 30-hour battery life.</p>
          <span class="card-price">₱2,499</span>
          <button class="card-btn">Buy Now</button>
        </div>
      </article>

      <!-- Card 2 -->
      <article class="card">
        <img src="https://images.unsplash.com/photo-1523275335684-37898b6baf30?w=500&q=80" alt="Smart Watch" class="card-img" />
        <div class="card-content">
          <h3 class="card-title">Smart Fitness Watch</h3>
          <p class="card-desc">Track your daily steps, heart rate, and sleep metrics with style and comfort.</p>
          <span class="card-price">₱1,899</span>
          <button class="card-btn">Buy Now</button>
        </div>
      </article>

      <!-- Card 3 -->
      <article class="card">
        <img src="https://images.unsplash.com/photo-1583394838336-acd977736f90?w=500&q=80" alt="Gaming Headset" class="card-img" />
        <div class="card-content">
          <h3 class="card-title">Pro Gaming Headset</h3>
          <p class="card-desc">Immersive surround sound featuring an ultra-clear noise-canceling microphone.</p>
          <span class="card-price">₱3,199</span>
          <button class="card-btn">Buy Now</button>
        </div>
      </article>
    </div>
  </section>

</body>
</html>
