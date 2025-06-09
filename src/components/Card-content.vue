<script setup></script>

<template>
  <div class="content">
    <div class="header">
      <p class="text badge">Interior</p>
      <p class="second-text">Top 5 Living Room Inspirations</p>
    </div>
    <div class="content-text">
      <p class="third-text">
        Curated vibrants colors for your living, make it pop & calm in the same time.
      </p>
      <button class="button padding">
        Read more
        <img class="arrow-icon" src="/arrow-right-line.svg" alt="arrow point to the right" />
      </button>
    </div>
  </div>
</template>

<style scoped>
.content {
  display: flex;
  flex-direction: column;
  gap: 12px;
  align-self: stretch;
  padding: 24px 16px;
}

.header {
  display: flex;
  flex-direction: column;
  gap: 8px;
  align-self: stretch;
}

.badge {
  display: flex;
  align-items: center;
  background-color: #f0fdf4;
  padding: 2px 8px;
  border-radius: 9999px;
  border-width: 1px;
  border-style: solid;
  border-color: #bbf7d0;
  width: 16%;
}

.text {
  font-weight: 400;
  font-size: 14px;
  line-height: 20px;
  text-align: center;
  color: #15803d;
  margin: 0;
}

.second-text {
  font-weight: 600;
  font-size: 18px;
  line-height: 28px;
  color: #171717;
  margin: 0;
}

.content-text {
  display: flex;
  flex-direction: column;
  gap: 24px;
  align-self: stretch;
}

.third-text {
  font-weight: 500;
  font-size: 16px;
  line-height: 24px;
  color: #525252;
}

.button {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 6px;
  border-radius: 4px;
  font-weight: 500;
  font-size: 16px;
  line-height: 24px;
  color: #4338ca;
  width: 37%;
  border: none;
  background-color: transparent;
}

.padding {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 0px 2px;
}

.arrow-icon {
  width: 20px;
  height: 20px;
}
</style>
