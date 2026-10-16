<template>
  <section class="mission" id="mission">
    <div class="container">
      <div class="left">
        <h1>Mission</h1>
        <h2>"Not to impress, but to serve."</h2>
        <p>"Whatever you do, work at it with all your heart, as working for the Lord" - Colossians 3:23</p>
      </div>
      <div class="right">
        <div class="right-item">
          <h2>Excellence in Every Cup</h2>
          <p>Colossians 3:23 guides everything, from welcoming customers warmly to serving every cup with care.</p>
        </div>
        <div class="right-item">
          <h2>A Ministry Through Coffee</h2>
          <p>Along with quality drinks, the café shares the Word of God, the love of Christ and real fellowship.</p>
        </div>
        <div class="right-item">
          <h2>Faith and Community</h2>
          <p>Every cup is a chance to build both faith and community, in a quiet space where everyone belongs.</p>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.mission {
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
    background-color: #d9c19a;
    display: flex;
    flex-direction: column;
    justify-content: center;
    padding: 40px;
    gap: 20px;

    h1 {
      color: #7a4a2b;
      font-size: 48px;
    }
    h2 {
      font-size: 30px;
    }
    p {
      font-size: 18px;
      font-style: italic;
    }
  }
  .right {
    background-color: #f1e6cc;
    display: grid;
    grid-template-rows: repeat(3, 1fr);
    padding: 40px;
    gap: 20px;
  }
  .right-item {
    background-color: #f8f0dc;
    border-left: 5px solid #7a4a2b;
    border-radius: 5px;
    padding: 20px 30px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    gap: 10px;

    h2 {
      color: #7a4a2b;
      font-size: 28px;
    }
    p {
      font-size: 20px;
      color: #6e5747;
    }
  }
}
</style>