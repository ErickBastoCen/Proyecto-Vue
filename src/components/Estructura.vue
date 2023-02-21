<template>
  <div class="item">
    <div class="details">
      <h3>
        <slot name="heading"></slot>
      </h3>
      <slot></slot>
    </div>
  </div>
</template>

<style scoped>
.item {
  margin-top: 2rem;
  display: flex;
}

.details {
  flex: 1;
  margin-left: 1rem;
}

i {
  display: flex;
  place-items: center;
  place-content: center;
  width: 32px;
  height: 32px;

  color: var(--color-text);
}

h3 {
  font-size: 2.2rem;
  font-weight: 500;
  margin-bottom: 0.4rem;
  color: var(--color-heading);


}

@media (min-width: 1024px) {
  .item {
    margin-top: 0;
    padding: 1 rem;
    align-items: center;
    background-color: #E67E22;
    height:500px;
    width: 800px;
  }
}
</style>
