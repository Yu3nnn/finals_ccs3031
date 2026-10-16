<template>
  <section class="history" id="history">
    <div class="container">
      <div class="top">
        <p class="small">Our Story</p>
        <h1>History</h1>
        <p class="intro">
          Kape ni Emman was started by a Christian couple who stepped out in faith because of their shared
          passion for coffee and ministry.
        </p>
        <p class="owners">— Michael and Jenny Molina, owners</p>
      </div>
      <div class="bottom">
        <div class="step">
          <p class="number">1</p>
          <h2>The Name</h2>
          <p>
            The café was first going to be called Café Immanuel, which means "God with us." They chose Kape
            ni Emman instead, a name that fits their mix of traditional and modern brewing while keeping the
            heart of their faith.
          </p>
        </div>
        <div class="step">
          <p class="number">2</p>
          <h2>A Quiet Opening</h2>
          <p>
            There were no balloons or big celebrations. The café opened with a simple prayer and a
            dedication to God.
          </p>
        </div>
        <div class="step">
          <p class="number">3</p>
          <h2>Two Years of Grace</h2>
          <p>
            On its second anniversary, the café had become a gathering place full of conversations, shared
            prayers and comforted hearts. The owners continue to serve with the same heart they started with.
          </p>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.history {
  max-width: 100vw;
  scroll-margin-top: 100px;
}

.container {
  width: 100%;
  min-height: 100vh;
  display: grid;
  grid-template-rows: auto 1fr;
  gap: 10px;

  .top {
    background-color: #7a4a2b;
    color: #f8f0dc;
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    padding: 50px 40px;
    gap: 15px;

    .small {
      font-size: 14px;
      font-weight: bold;
      letter-spacing: 2px;
      text-transform: uppercase;
      color: #e8c08a;
    }
    h1 {
      font-size: 48px;
    }
    .intro {
      max-width: 750px;
      font-size: 22px;
    }
    .owners {
      font-style: italic;
      color: #e8c08a;
    }
  }
  .bottom {
    background-color: #f1e6cc;
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    padding: 40px;
    gap: 20px;
  }
  .step {
    background-color: #f8f0dc;
    border: 1px solid #7a4a2b;
    border-top: 6px solid #7a4a2b;
    border-radius: 10px;
    padding: 30px;
    display: flex;
    flex-direction: column;
    gap: 12px;

    .number {
      width: 50px;
      height: 50px;
      border-radius: 50%;
      background-color: #5d1929;
      color: #f8f0dc;
      font-size: 22px;
      font-weight: bold;
      display: flex;
      align-items: center;
      justify-content: center;
    }
    h2 {
      color: #7a4a2b;
      font-size: 26px;
    }
    p {
      font-size: 18px;
      color: #6e5747;
    }
  }
}
</style>