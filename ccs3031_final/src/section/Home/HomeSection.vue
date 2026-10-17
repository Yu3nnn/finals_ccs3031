<template>
  <section class="Home" id="home">
    <div class="container">
      <div class="logo">
        <img src="@/assets/image/Logo.png" alt=" Logo" />
      </div>

      <div class="Body">
        <p class="welcome">WELCOME TO KAPEHAN NI EMMAN</p>

        <h1>Find Your Perfect Coffee</h1>

        <p>
          Where every cup comes with a warm welcome and a friendly wag
        </p>

        
      </div>
    </div>
  </section>
</template>

<style scoped>
.Home {
  width: 100%;
  min-height: 100vh;
  background-color: #e6eadb;
}

.container {
  width: 100%;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  padding: 30px 20px;
  box-sizing: border-box;
  text-align: center;
}

.logo {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 80px;
}

.logo img {
  width: 400px;
  height: 500px;
}

.Body {
  max-width: 750px;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.welcome {
  color: #647b4e;
  font-weight: bold;
  font-size: 16px;
}

.Body h1 {
  color: #29452c;
  font-size: 42px;
}

.Body p {
  color: #444444;
  font-size: 18px;
}

.Button {
  background-color: #29452c;
  color: white;
  padding: 12px 22px;
  border-radius: 5px;
  margin-top: 15px;
}

@media (max-width: 768px) {
  .logo img {
    width: 300px;
    height: 150px;
  }

  .Body h1 {
    font-size: 32px;
  }

  .Body p {
    font-size: 16px;
  }
}
</style>
