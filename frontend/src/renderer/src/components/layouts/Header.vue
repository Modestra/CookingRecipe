<template>
  <header>
    <p>Рецепты</p>
    <div class="list-btn">
      <button></button>
    </div>
  </header>
</template>

<script setup></script>

<style lang="scss">
header {
  display: flex;
  flex-direction: row;
  align-items: center;

  padding-left: 10px;
  width: 100%;
  height: 40px;
  min-height: 40px;
  border-bottom: 1px solid black;
}
.list-btn {
  display: flex;
  justify-content: end;
  align-items: center;
  width: 100%;
  min-width: 600px;
  height: 100%;
}
.list-btn button {
  width: 30px;
  height: 30px;
  margin-right: 10px;
  margin-left: 10px;
  background-color: #ffe77c;
}
.list-btn:last-child {
  margin-right: 10px;
}
</style>
