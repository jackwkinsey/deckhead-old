<template>
  <div>
    <div>
      <img :src="$auth.user.picture" :alt="`image of ${$auth.user.name}`" />
      <div>{{ $auth.user.name }}</div>
      <div>{{ $auth.user.email }}</div>
    </div>

    <div>
      <pre>{{ JSON.stringify($auth.user, null, 2) }}</pre>
    </div>
  </div>
</template>
