<template>
<main>
  <div class="input-container">
    <h1>Note</h1>
    <button>+</button>
  </div>

  <div class="card-container">
    <div class="card">
      <p>test card</p>
      <p>Date: 06.06.0666</p>
    </div>
  </div>
</main>
</template>


<style scoped>
main {
  background-color: AliceBlue;
  width: 100vw;
  height: 100vh;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.input-container{
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 80%;
  height: 10%;
  margin: 0 auto;
}

.input-container button {
  color: white;
  font-size: 1.8rem;
  background-color: black;
  width: 40px;
  height: 40px;
  border-radius: 100%;
}

.card-container {
  width: 80%;
  display: flex;
  justify-content: space-evenly;
  flex-wrap: wrap;
  gap: 20px;
}

.card {
  margin-right: auto;
  background-color: lightGrey;
  height: 225px;
  width: 225px;
}
</style>
