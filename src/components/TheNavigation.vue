<template>
  <div class="TheNavigation">
    <router-link :to="$i18nRoute({ name: 'HelloWorld'})">{{ $t('Home') }}</router-link>
    <router-link :to="$i18nRoute({ name: 'about'})">{{ $t('pages.about') }}</router-link>
  </div>
</template>

<style>
.TheNavigation {
  display: flex;
  justify-content: center;
  margin-bottom: 1rem;
}

.TheNavigation a {
  text-decoration: none;
  font-weight: bold;
  color: #535353;
  margin: 0 0.5rem;
}

.TheNavigation a:hover {
  color: #333;
}
</style>
