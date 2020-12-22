<template>
  <div class="toolbar">
    <button class="toolbar-button">New</button>
    <button class="toolbar-button">Delete</button>
    <input class="toolbar-search" type="text" placeholder="Search...">
  </div>
</template>


<style>
.toolbar {
  padding: 0.5em;
}
.toolbar-button,
.toolbar-search {
  padding: inherit;
  border-radius: 0.3em;
}
.toolbar-search {
  float: right;
}
</style>

