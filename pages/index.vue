<template>
  <div
    h="full"
    p="y-4"
    gap="4 md:8 lg:16"
    grid="~ md:cols-2"
  >
    <div
      flex="~ col"
      justify="center"
    >
      <Hello />
      <div text="dark:(white opacity-75)" class="about">
        <About class="mx-0" />
      </div>
    </div>
    <div
      grid="~"
      gap="4"
      content="center"
    >
    <Card label="My Inspirations" to="/inspiration">
        <template #icon>
          <ph-address-book />
        </template>
        Sudha Murthy, Malala Yousafzai, Kailash Satyarthi
      </Card>
      <Card label="Notes" to="/notes">
        <template #icon>
          <ph-note />
        </template>
        Take a look out some of my short notes.
      </Card>
      
    </div>
  </div>
</template>

<style>
html .about a {
  text-decoration-color: #db2777 !important;
}
</style>


