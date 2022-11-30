<template>
  <main class="bg-black">  
   <div class="flex flex-row gap-10 justify-end items-center pr-40">
   <!--  <img src="../assets/linkedn.png" alt="" class=""> 
<img src="../assets/facebook.png" alt="" class=""> -->
  </div>
  <div class="flex flex-col md:flex-row">
<aside class="mt-5 ml-10 w-64" aria-label="Sidebar">
   <img src="../assets/logo.png" alt="" class="pb-4 w-20 h-16">
   <div class="overflow-y-auto px-3 py-4 bg-gray-50 rounded dark:bg-gray-800">
      <ul class="space-y-2">
        <li>
            <a href="#" class="flex items-center p-2 text-base font-normal text-gray-900 rounded-lg dark:text-white hover:bg-gray-100 dark:hover:bg-gray-700">
               <svg aria-hidden="true" class="w-6 h-6 text-gray-500 transition duration-75 dark:text-gray-400 group-hover:text-gray-900 dark:group-hover:text-white" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path d="M2 10a8 8 0 018-8v8h8a8 8 0 11-16 0z"></path><path d="M12 2.252A8.014 8.014 0 0117.748 8H12V2.252z"></path></svg>
               <span class="ml-3 text-4xl hover:text-green-500">Home</span>
            </a>
         </li>
         <li>
            <a href="#" class="flex items-center p-2 text-base font-normal text-gray-900 rounded-lg dark:text-white hover:bg-gray-100 dark:hover:bg-gray-700">
               <svg aria-hidden="true" class="w-6 h-6 text-gray-500 transition duration-75 dark:text-gray-400 group-hover:text-gray-900 dark:group-hover:text-white" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path d="M2 10a8 8 0 018-8v8h8a8 8 0 11-16 0z"></path><path d="M12 2.252A8.014 8.014 0 0117.748 8H12V2.252z"></path></svg>
               <span class="ml-3 hover:text-green-500">Dashboard</span>
            </a>
         </li>
          
         <li> 
            <a href="#" class="flex items-center p-2 text-base font-normal text-gray-900 rounded-lg dark:text-white hover:bg-gray-100 dark:hover:bg-gray-700">
               <svg aria-hidden="true" class="flex-shrink-0 w-6 h-6 text-gray-500 transition duration-75 dark:text-gray-400 group-hover:text-gray-900 dark:group-hover:text-white" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path d="M8.707 7.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l2-2a1 1 0 00-1.414-1.414L11 7.586V3a1 1 0 10-2 0v4.586l-.293-.293z"></path><path d="M3 5a2 2 0 012-2h1a1 1 0 010 2H5v7h2l1 2h4l1-2h2V5h-1a1 1 0 110-2h1a2 2 0 012 2v10a2 2 0 01-2 2H5a2 2 0 01-2-2V5z"></path></svg>
               <span class="flex-1 ml-3 whitespace-nowrap hover:text-green-500">Inbox</span>
          </a>
         </li>
         <li>
            <a href="#" class="flex items-center p-2 text-base font-normal text-gray-900 rounded-lg dark:text-white hover:bg-gray-100 dark:hover:bg-gray-700">
               <svg aria-hidden="true" class="flex-shrink-0 w-6 h-6 text-gray-500 transition duration-75 dark:text-gray-400 group-hover:text-gray-900 dark:group-hover:text-white" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M10 9a3 3 0 100-6 3 3 0 000 6zm-7 9a7 7 0 1114 0H3z" clip-rule="evenodd"></path></svg>
               <span class="flex-1 ml-3 whitespace-nowrap hover:text-green-500">Users</span>
            </a>
         </li>
         <li>
            <a href="#" class="flex items-center p-2 text-base font-normal text-gray-900 rounded-lg dark:text-white hover:bg-gray-100 dark:hover:bg-gray-700">
               <svg aria-hidden="true" class="flex-shrink-0 w-6 h-6 text-gray-500 transition duration-75 dark:text-gray-400 group-hover:text-gray-900 dark:group-hover:text-white" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M10 2a4 4 0 00-4 4v1H5a1 1 0 00-.994.89l-1 9A1 1 0 004 18h12a1 1 0 00.994-1.11l-1-9A1 1 0 0015 7h-1V6a4 4 0 00-4-4zm2 5V6a2 2 0 10-4 0v1h4zm-6 3a1 1 0 112 0 1 1 0 01-2 0zm7-1a1 1 0 100 2 1 1 0 000-2z" clip-rule="evenodd"></path></svg>
               <span class="flex-1 ml-3 whitespace-nowrap hover:text-green-500">Products</span>
            </a>
         </li>
          </ul>
        
     
      <div id="dropdown-cta" class="p-4 mt-6 bg-blue-50 rounded-lg dark:bg-blue-900" role="alert">
         <div class="flex items-center mb-3">
              
         </div>
       
   </div>
   </div>
</aside>
 
<p class="pt-24 pl-10 text-white"><span class="text-lg text-green-500 md:text-3xl">Trust us for better tomorrow </span><br>
    Nuxt 3 is an open-source framework for web development
     that is both simple and powerful. Nuxt 3 was developed by Sébastien Chopin to emulate the
      functionality of Nuxt.js, but with Vue instead of React. Furthermore, it is entirely written in
       typescript for easy maintenance and built-in typescript support.
We observe that Nuxt 3 is currently unstable, deeming it unfit to be production-ready.
 Let take a look at whats available.

</p>
  </div>
 
        <div class="">
        <h1 class="pt-20 pb-48 m-6 text-4xl text-white">MEN HERE WE GO DOWN TO LEARN NUXT <span class="text-green-600">THE VUE FRAMEWORK</span> </h1>
        <button class="p-7 mb-20 ml-10 text-4xl text-white bg-green-500 rounded-lg hover:scale-105">GET STARTED</button>
        </div>
 <div class="flex justify-center items-center pb-5 text-xl text-white">
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
 <div class="mt-20">

<label class="pt-14 text-xl font-medium text-white dark:text-white" for="file_input">Upload file</label>
<input class="block text-sm text-white bg-black rounded-lg border border-gray-300 cursor-pointer dark:text-gray-400 focus:outline-none dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400" id="file_input" type="file">
</div>


<form>
   <div class="w-full bg-fullgray-50 dark:bg-gray-700 dark:border-gray-600">
       <div class="px-4 py-2 mt-10 bg-white rounded-t-lg dark:bg-gray-800">
           <label for="comment" class="sr-only">Your comment</label>
           <textarea id="comment" rows="4" class="px-0 w-full text-sm text-gray-900 bg-white border-0 dark:bg-gray-800 focus:ring-0 dark:text-white dark:placeholder-gray-400" placeholder="Write a comment..." required></textarea>
       </div>
       <div class="flex justify-between items-center px-3 py-2 border-t dark:border-gray-600">
           <button type="submit" class="inline-flex items-center px-4 py-2.5 text-xs font-medium text-center text-white bg-green-500 rounded-lg focus:ring-4 focus:ring-blue-200 dark:focus:ring-blue-900 hover:bg-black">
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
  mounted(){
    this.$nextTick(()=>{
        this.$nuxt.$loading.start()
        setTimeout(()=>this.$nuxt.$loading.finish(),500)
    })
  }

}
</script>

<style>

</style>