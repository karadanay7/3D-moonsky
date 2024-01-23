<template>
  <div class="relative bg-cover bg-black h-screen">
    <img
      src="/a.jpg"
      class="absolute top-0 w-full h-full object-cover"
      sizes="200px"
    />
    <div
      class="absolute top-0 w-full h-full flex flex-col justify-start items-start text-white font-index"
    >
      <div class="relative pl-10 top-1/4 text-3xl md:text-4xl lg:text-6xl z-20">
        <h1 class="mb-4">Welcome! I'm Aysegul Karadan,</h1>
        <h1 class="mb-4">a Full Stack Developer</h1>
        <h1 class="mb-4">Let's craft remarkable</h1>
        <h1 class="mb-4">digital experiences together!</h1>
        <div class="icons flex items-center">
          <NuxtLink
            target="_blank"
            to="https://www.linkedin.com/in/aysegulkaradan/"
            class="mx-4 text-gray-50 hover:text-blue-300"
            alt="linkedin"
            aria-label="connect with linkedin"
          >
            <Icon name="uil:linkedin" class="text-4xl md:text-6xl" />
          </NuxtLink>
          <NuxtLink
            target="_blank"
            to="mailto:karadan.ay7@gmail.com"
            class="mx-4 text-gray-50 hover:text-blue-300"
            alt="mailto"
            aria-label="connect with mail"
          >
            <Icon name="uil:envelope" class="text-4xl md:text-6xl" />
          </NuxtLink>
          <NuxtLink
            target="_blank"
            alt="github"
            to="https://github.com/karadanay7"
            class="mx-4 text-gray-50 hover:text-blue-300"
            aria-label="connect with github"
          >
            <Icon name="uil:github" class="text-4xl md:text-6xl" />
          </NuxtLink>
        </div>
        <div class="flex flex-col items-start mt-2 ml-20">
          <NuxtLink
            to="https://aysegulk.me/projects"
            class="text-gray-50 hover:text-blue-300 text-2xl md:text-3xl"
          >
            <p class="hidden md:inline-block">Projects!</p>
          </NuxtLink>
          <Icon
            name="clarity:cursor-hand-click-line"
            class="mt-4 animate-bounce ml-10"
            size="40"
          />
        </div>
      </div>
    </div>
    <div class="absolute top-0 w-full h-full">
      <iframe
        src="https://my.spline.design/3dearthcopy-19fd36aaa27da5868b8a271d2a392aff/"
        frameborder="0"
        width="100%"
        height="100%"
        class="object-cover"
      ></iframe>
    </div>
  </div>
</template>
