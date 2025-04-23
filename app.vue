<template>
  <div>
    <NuxtRouteAnnouncer />
    <NuxtWelcome />
    <div>
      <div>{{ $t('hello') }}</div>
      <div>{{ $router }}</div>
    </div>
  </div>
</template>
