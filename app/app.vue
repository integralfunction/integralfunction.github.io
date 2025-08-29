<template>
  <div>
    <NuxtRouteAnnouncer />
    <UApp>
      <header class="py-2 px-2 justify-between flex flex-row">
        <div></div>
        <div></div>
        <a class="p-2 bg-black inline-flex rounded-full align-middle" href="https://github.com/integralfunction">
          <UIcon name="i-lucide-github" class="size-6 bg-white" />
        </a>
      </header>
      <NuxtPage />
      <footer class="h-8">
      </footer>
    </UApp>
  </div>
</template>