<template>
  <main class="bg-black">
      <!--   <aside class="top-1 justify-start h-full md:mt-1 md:w-1/5 md:left md:ml-2 md:fixed md:min-h-screen md:flex" aria-label="Sidebar"> -->
  <div class="overflow-y-auto py-2 rounded">
   <!-- <div class="flex flex-col gap-y-2 justify-center items-center mx-auto"> -->
 <ul class="flex flex-col gap-4 justify-start ml-1 text-white">
    <li><Nuxtlink to="/home">Home</Nuxtlink></li>
 </ul>
  </div>
        <!-- </aside> -->
 <div class="flex justify-center items-center text-xl text-white">
  Hello welcome to this platform feel free and relax
 </div>
 <div class="container grid grid-cols-1 grid-rows-3 gap-4 justify-center items-center mx-auto mb-20 md:grid-rows-2 md:grid-cols-3 lg:grid-cols-3">
   <img src="../assets/1.jpg" alt="" class="w-80 h-80 rounded-md hover:scale-105">
    <img src="../assets/2.webp" alt="" class="w-80 h-80 rounded-md hover:scale-105">
    <img src="../assets/3.webp" alt="" class="w-80 h-80 rounded-md hover:scale-105">
    <img src="../assets/4.webp" alt="" class="w-80 h-80 rounded-md hover:scale-105">
    <img src="../assets/5.webp" alt="" class="w-80 h-80 rounded-md hover:scale-105">
    <img src="../assets/6.jpeg" alt="" class="w-80 h-80 rounded-md hover:scale-105">
    <img src="../assets/7.webp" alt="" class="w-80 h-80 rounded-md hover:scale-105">
    <img src="../assets/8.webp" alt="" class="w-80 h-80 rounded-md hover:scale-105">
    <img src="../assets/9.webp" alt="" class="w-80 h-80 rounded-md hover:scale-105">

 </div>

<label class="block mt-12 mb-2 text-sm font-medium text-gray-900 dark:text-white" for="file_input">Upload file</label>
<input class="block w-full text-sm text-gray-900 bg-gray-50 rounded-lg border border-gray-300 cursor-pointer dark:text-gray-400 focus:outline-none dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400" id="file_input" type="file">



<form>
   <div class="mb-12 w-full rounded border border-gray-200 -lg bg-fullgray-50 dark:bg-gray-700 dark:border-gray-600">
       <div class="px-4 py-2 bg-white rounded-t-lg dark:bg-gray-800">
           <label for="comment" class="sr-only">Your comment</label>
           <textarea id="comment" rows="4" class="px-0 w-full text-sm text-gray-900 bg-white border-0 dark:bg-gray-800 focus:ring-0 dark:text-white dark:placeholder-gray-400" placeholder="Write a comment..." required></textarea>
       </div>
       <div class="flex justify-between items-center px-3 py-2 border-t dark:border-gray-600">
           <button type="submit" class="inline-flex items-center px-4 py-2.5 text-xs font-medium text-center text-white bg-blue-700 rounded-lg focus:ring-4 focus:ring-blue-200 dark:focus:ring-blue-900 hover:bg-blue-800">
               Post comment
           </button>
           <div class="flex pl-0 space-x-1 sm:pl-2">
               <button type="button" class="inline-flex justify-center p-2 text-gray-500 rounded cursor-pointer hover:text-gray-900 hover:bg-gray-100 dark:text-gray-400 dark:hover:text-white dark:hover:bg-gray-600">
                   <svg aria-hidden="true" class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M8 4a3 3 0 00-3 3v4a5 5 0 0010 0V7a1 1 0 112 0v4a7 7 0 11-14 0V7a5 5 0 0110 0v4a3 3 0 11-6 0V7a1 1 0 012 0v4a1 1 0 102 0V7a3 3 0 00-3-3z" clip-rule="evenodd"></path></svg>
                   <span class="sr-only">Attach file</span>
               </button>
               <button type="button" class="inline-flex justify-center p-2 text-gray-500 rounded cursor-pointer hover:text-gray-900 hover:bg-gray-100 dark:text-gray-400 dark:hover:text-white dark:hover:bg-gray-600">
                   <svg aria-hidden="true" class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M5.05 4.05a7 7 0 119.9 9.9L10 18.9l-4.95-4.95a7 7 0 010-9.9zM10 11a2 2 0 100-4 2 2 0 000 4z" clip-rule="evenodd"></path></svg>
                   <span class="sr-only">Set location</span>
               </button>
               <button type="button" class="inline-flex justify-center p-2 text-gray-500 rounded cursor-pointer hover:text-gray-900 hover:bg-gray-100 dark:text-gray-400 dark:hover:text-white dark:hover:bg-gray-600">
                   <svg aria-hidden="true" class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M4 3a2 2 0 00-2 2v10a2 2 0 002 2h12a2 2 0 002-2V5a2 2 0 00-2-2H4zm12 12H4l4-8 3 6 2-4 3 6z" clip-rule="evenodd"></path></svg>
                   <span class="sr-only">Upload image</span>
               </button>
           </div>
       </div>
   </div>
</form>
 
  </main>
</template>

<script>
export default {
  

}
</script>

<style>

</style>