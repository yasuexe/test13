<div id="app">
  <router-link v-bind:to="{name: 'Home'}">トップページ</router-link>
  <router-link v-bind:to="{name: 'UserList'}">ユーザー一覧ページ</router-link>
  <router-view></router-view>
</div>