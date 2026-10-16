<template>
  <section class="socials" id="socials">
    <div class="container">
      <div class="text">
        <h1>Socials</h1>
        <p>Follow Kape ni Emman for new drinks, updates and café moments.</p>
      </div>
      <div class="list">
        <a class="item" href="https://web.facebook.com/kapeniemman" target="_blank">
          <img src="@/assets/image/facebook-logo.png" alt="Facebook logo" />
          <h2>Facebook</h2>
          <p>kapeniemman</p>
        </a>
        <a class="item" href="https://www.instagram.com/kapeniemman" target="_blank">
          <img src="@/assets/image/instagram-logo.png" alt="Instagram logo" />
          <h2>Instagram</h2>
          <p>@kapeniemman</p>
        </a>
        <a class="item" href="https://www.tiktok.com/@kapeniemman" target="_blank">
          <img src="@/assets/image/tiktok-logo.png" alt="TikTok logo" />
          <h2>TikTok</h2>
          <p>@kapeniemman</p>
        </a>
      </div>
    </div>
  </section>
</template>

<style scoped>
.socials {
  max-width: 100vw;
  scroll-margin-top: 100px;
}

.container {
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  background-color: #f1e6cc;
  padding: 40px 20px;
  gap: 30px;

  .text {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 10px;
    text-align: center;

    h1 {
      color: #7a4a2b;
      font-size: 42px;
    }
    p {
      font-size: 20px;
    }
  }
  .list {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    gap: 20px;
    max-width: 1000px;
    margin: 0 auto;
    width: 100%;
  }
  .item {
    background-color: #f8f0dc;
    display: flex;
    flex-direction: column;
    align-items: center;
    border: 1px solid #7a4a2b;
    border-radius: 10px;
    padding: 30px 20px;
    gap: 10px;
    color: inherit;
    text-decoration: none;

    img {
      width: 70px;
      height: 70px;
      object-fit: contain;
    }
    h2 {
      color: #7a4a2b;
    }
  }
}
</style>