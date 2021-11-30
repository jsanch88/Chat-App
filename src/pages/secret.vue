<template>
  <h1 class="text-6xl font-extralight tracking-tighter text-center mt-8 bg-gradient-to-r from-purple-400 via-pink-500 to-indigo-500 rounded-xl">The Chat of all Chats!</h1>

  <div class="min-h-[500px] w-full mt-8 rounded-lg shadow-2xl flex flex-col justify-between">

  <ul class= "p-4 space-y-5">

    <li v-for ="n in 5">
    <div class="flex justify-between bg-gradient-to-r from-yellow-400 via-red-500 to-pink-500 px-4 py-2 rounded-xl">
    <span>Message itself</span><span>By Author Name</span>
    </div>
    </li>
  </ul>
  <div>
  <input class ="w-full p-4 rounded-xl focus:outline-none focus:bg-indigo-500" type = "text" placeholder="Type here..." />
  </div>
  </div>
</template>