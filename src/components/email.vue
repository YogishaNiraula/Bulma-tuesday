<template>
  <section class="secction">
    <div class="container">
      <div class="level">
        <div class="level-item has-text-centered">
          <slot></slot>
        </div>
      </div>
      <div class="field">
        <input
          class="input"
          type="email"
          placeholder="Email"
          style="width: 40%"
        />
      </div>
      <div class="field is-grouped">
        <button class="button is-primary">submit</button>
      </div>
    </div>
  </section>
</template>
<script>
export default {
  name: "email",
};
</script>