<script>
  import welcome from "$lib/images/svelte-welcome.webp";
  import welcomeFallback from "$lib/images/svelte-welcome.png";
</script>

<svelte:head>
  <title>Home</title>
  <meta name="description" content="Svelte demo app" />
</svelte:head>

<div class="container">
  <section class="hero">
    <div class="hero-text">
      <h2>Welcome to Book Hub</h2>
      <p>
        Discover, buy, exchange, or gift books — and share the notes and quotes
        that made them meaningful.
      </p>

      <div class="search-bar">
        <input
          type="search"
          placeholder="Search by title, author, or keyword"
        />
        <button class="btn btn-buy">Search</button>
      </div>

      <div class="features">
        <div class="feature-card">
          <h4>Buy Books</h4>
          <a href="buy.html" class="btn btn-buy">Browse</a>
        </div>
        <div class="feature-card">
          <h4>Exchange</h4>
          <a href="exchange.html" class="btn btn-exchange">Browse</a>
        </div>
        <div class="feature-card">
          <h4>Gift</h4>
          <a href="gift.html" class="btn btn-gift">Browse</a>
        </div>
      </div>
    </div>

    <div style="min-width:180px; text-align:center; color:#65451F;">
      <div style="font-size:18px; font-weight:700;">Featured</div>
      <p style="margin-top:6px">Hand-picked books for you</p>
    </div>
  </section>

  <section class="featured-section">
    <h3>Featured Books</h3>
    <div class="book-grid">
      <section class="book-card">
        <div class="book-cover"></div>
        <div class="book-info">
          <h3 class="book-title">The Little Prince</h3>
          <div class="book-meta">by Antoine de Saint-Exupéry</div>
          <div class="book-desc">
            A poetic tale about a young prince's journey and lessons about life
            and love.
          </div>
          <div class="book-actions">
            <button class="btn btn-buy">Buy</button>
          </div>
        </div>
      </section>

      <section class="book-card">
        <div class="book-cover"></div>
        <div class="book-info">
          <h3 class="book-title">Sapiens</h3>
          <div class="book-meta">by Yuval Noah Harari</div>
          <div class="book-desc">
            A brief history of humankind — thought-provoking and wide-ranging.
          </div>
          <div class="book-actions">
            <button class="btn btn-buy">Buy</button>
          </div>
        </div>
      </section>

      <section class="book-card">
        <div class="book-cover"></div>
        <div class="book-info">
          <h3 class="book-title">The Alchemist</h3>
          <div class="book-meta">by Paulo Coelho</div>
          <div class="book-desc">
            A fable about following your dreams and listening to your heart.
          </div>
          <div class="book-actions">
            <button class="btn btn-buy">Buy</button>
          </div>
        </div>
      </section>
    </div>
  </section>
</div>
