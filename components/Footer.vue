<template>
  <div>
    <ul class="list-group flex-row bg-light">
      <li class="list-group-item text-center p-0 border-0 rounded-0">
        <font-awesome-icon :icon="['fas', 'home']" />
        <p class="mb-0">
          Home
        </p>
      </li>
      <li class="list-group-item text-center p-0 border-0">
        <font-awesome-icon :icon="['fas', 'fire']" />
        <p class="mb-0">
          Trending
        </p>
      </li>
      <li class="list-group-item text-center p-0 border-0">
        <font-awesome-icon :icon="['far', 'play-circle']" />
        <p class="mb-0">
          Subscriptions
        </p>
      </li>
      <li class="list-group-item text-center p-0 border-0 rounded-0">
        <font-awesome-icon :icon="['fas', 'book']" />
        <p class="mb-0">
          Library
        </p>
      </li>
    </ul>
  </div>
</template>

<style scoped>
.list-group-item {
  width: 25%;
}
</style>
