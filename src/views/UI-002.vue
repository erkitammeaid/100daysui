<template>
  <body>
    <div class="container">
      <div class="pede">
        <h1 id="text">Loading Please Wait</h1>
      </div>
      <div class="loader"></div>
    </div>
  </body>
</template>
<style>
.pede {
  display: flex;
  height: 8rem;
  align-items: center;
}
body {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.container {
  display: flex;
  justify-content: center;
  flex-direction: column;
  align-items: center;
}
.loader {
  display: flex;
  justify-content: center;
  margin: 10px;
  border: 16px solid #f3f3f3; /* Light grey */
  border-top: 16px solid #3498db; /* Blue */
  border-radius: 50%;
  width: 120px;
  height: 120px;
  animation: spin 2s linear infinite;
}

@keyframes spin {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(360deg);
  }
}
</style>
