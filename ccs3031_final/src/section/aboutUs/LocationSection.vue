<template>
  <section class="location" id="location">
    <div class="container">
      <div class="left">
        <p class="small">Visit Us</p>
        <h1>Location</h1>
        <p>Find our café on Sto. Domingo St. in Jaro, a short walk from Central Philippine University (CPU).</p>
      </div>
      <div class="right">
        <div class="info">
          <div class="right-item">
            <h2>Address</h2>
            <p>20 Sto. Domingo St., Jaro, Iloilo City, Iloilo</p>
          </div>
          <div class="right-item">
            <h2>Business Hours</h2>
            <p>Monday to Saturday</p>
            <p>10:00 AM to 7:00 PM</p>
          </div>
        </div>
        <div class="map">
          <iframe
            src="https://maps.google.com/maps?q=10.7312094,122.5522986&z=17&output=embed"
            title="Map of Kape ni Emman"
            loading="lazy"
          ></iframe>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.location {
  max-width: 100vw;
  scroll-margin-top: 100px;
}

.container {
  width: 100%;
  min-height: calc(100vh - 100px);
  display: grid;
  grid-template-columns: 1fr 2fr;
  gap: 10px;

  .left {
    background-color: #7a4a2b;
    color: #f8f0dc;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: start;
    padding: 40px;
    gap: 20px;

    .small {
      font-size: 14px;
      font-weight: bold;
      letter-spacing: 2px;
      color: #e8c08a;
    }
    h1 {
      font-size: 48px;
    }
    p {
      font-size: 20px;
    }
  }
  .right {
    background-color: #f1e6cc;
    display: flex;
    flex-direction: column;
    padding: 40px;
    gap: 20px;
  }
  .info {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 20px;
  }
  .right-item {
    background-color: #f8f0dc;
    border-left: 5px solid #7a4a2b;
    border-radius: 5px;
    padding: 20px 30px;
    display: flex;
    flex-direction: column;
    gap: 5px;

    h2 {
      color: #7a4a2b;
      font-size: 26px;
      margin-bottom: 5px;
    }
    p {
      font-size: 18px;
      color: #6e5747;
    }
  }
  .map {
    flex: 1;
    min-height: 300px;
    border: 2px solid #7a4a2b;
    border-radius: 10px;
    overflow: hidden;
    box-shadow: 0px 5px #8a7560;

    iframe {
      width: 100%;
      height: 100%;
      min-height: 300px;
      border: 0;
      display: block;
    }
  }
}
</style>