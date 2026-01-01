<template>
  <aside class="sidebar">
    <h2 class="logo">MyApp</h2>
    <ul>
      <li><a href="#">Dashboard</a></li>
      <li><a href="#">User</a></li>
      <li><a href="#">Setting</a></li>
    </ul>
  </aside>
</template>

<style scoped>
.sidebar {
  width: 220px;
  height: 100vh;
  background: #1e1e2f;
  color: white;
  padding: 20px;
}

.logo {
  margin-bottom: 20px;
}

ul {
  list-style: none;
  padding: 0;
}

li {
  margin-bottom: 12px;
}

a {
  color: white;
  text-decoration: none;
}

a:hover {
  color: #4fc3f7;
}
</style>
