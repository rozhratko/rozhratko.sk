<template>
  <main>
    <h1>Rozhrátko</h1>
  </main>
</template>

<style scoped>
main {
  --background-color: white;
  --background-color-gradient: #fdfdfd;
  --text-color: #222;

  min-height: 100vh;
  display: grid;
  place-items: center;
  font-family: 'Sriracha', sans-serif;
  background: var(--background-color)
    radial-gradient(var(--background-color) 0%, var(--background-color-gradient) 100%);
  color: var(--text-color);

  @media (prefers-color-scheme: dark) {
    --background-color: #222;
    --background-color-gradient: #151515;
    --text-color: #eee;
  }
}

h1 {
  font-size: 5rem;
}
</style>
