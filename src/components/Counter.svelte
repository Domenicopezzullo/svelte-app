<script lang="ts">
    let count = 0
    let increment = () => {
        count++
    }
  </script>


<div class="bg-gradient-to-r from-violet-600 to-indigo-600 h-screen w-screen flex-col flex items-center justify-center">
  <div class="bg-white/50 text-2xl font-bold font-quicksand flex flex-col items-center justify-center py-40 px-40 rounded-xl">
    <button on:click={increment} class="border-2 border-black font-bold text-white  hover:bg-blue-700 p-5 rounded-2xl mb-[50px] bg-blue-600 transition-all duration-300 ease-in-out transform hover:scale-125">Increment</button>
    <h1 class="text-9xl">{count}</h1> 
  </div>
</div>