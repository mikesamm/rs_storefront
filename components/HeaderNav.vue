<template>
  <UContainer class="flex flex-col">
    <UContainer id="nav-header" class="flex flex-row justify-between">
      <div>logo</div>
      <div>
        <USlideover close-icon="lucide:x">
          <UButton icon="lucide:align-justify" />
          <template #body> Menu goes here </template>
        </USlideover>
      </div>
    </UContainer>
    <div id="banner">
      <h1>River Shepard Photographic Arts</h1>
    </div>
  </UContainer>
</template>
