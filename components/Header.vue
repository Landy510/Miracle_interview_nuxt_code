<template>
  <nav class="navbar navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">
        <font-awesome-icon :icon="['fab', 'youtube']" class="text-danger" />
        <span class="font-weight-bold">Youtube</span>
      </a>
      <div class="d-flex flex-row align-items-center">
        <font-awesome-icon :icon="['fas', 'search']" class="searchIcon" />
        <div class="current-user d-flex justify-content-center align-items-center text-light font-weight-bold">
          R
        </div>
      </div>
    </div>
    <div class="badge-content w-100">
      <ul class="list-group flex-row w-100 rounded-0 border-top border-dark">
        <li class="list-group-item border-0">
          <span class="badge badge-secondary text-light bg-secondary">All</span>
        </li>
        <li class="list-group-item border-0">
          <span class="badge badge-secondary text-light bg-secondary">Music</span>
        </li>
        <li class="list-group-item border-0">
          <span class="badge badge-secondary text-light bg-secondary">One Direction</span>
        </li>
        <li class="list-group-item border-0">
          <span class="badge badge-secondary text-light bg-secondary">History</span>
        </li>
        <li class="list-group-item border-0">
          <span class="badge badge-secondary text-light bg-secondary">王力宏</span>
        </li>
        <li class="list-group-item border-0">
          <span class="badge badge-secondary text-light bg-secondary">30 Seconds</span>
        </li>
        <li class="list-group-item border-0">
          <span class="badge badge-secondary text-light bg-secondary">G.E.M</span>
        </li>
        <li class="list-group-item border-0">
          <span class="badge badge-secondary text-light bg-secondary">灌籃高手</span>
        </li>
        <li class="list-group-item border-0">
          <span class="badge badge-secondary text-light bg-secondary">Energy</span>
        </li>
        <li class="list-group-item border-0">
          <span class="badge badge-secondary text-light bg-secondary">外國人來台灣</span>
        </li>
        <li class="list-group-item border-0">
          <span class="badge badge-secondary text-light bg-secondary">10大精選</span>
        </li>
        <li class="list-group-item border-0">
          <span class="badge badge-secondary text-light bg-secondary">惡靈古堡</span>
        </li>
      </ul>
    </div>
  </nav>
</template>

<style lang="scss" scoped>
.current-user {
  height: 30px;
  width: 30px;
  background-color: green;
  border-radius: 50%;
}
.searchIcon {
  margin-right: 20px;
}
.navbar-brand {
  margin-left: 5px;
}
.user-content {
  margin-right: 5px;
}
.logo {
  font-weight: 600;
}
.badge {
  font-size: 20px;
  border-radius: 20px;
  padding: 10px;
}
.list-group {
  overflow-x: auto;
}
</style>
