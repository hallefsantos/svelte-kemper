<script>
  import Tailwindcss from "./Tailwindcss.svelte";

  export let name;
</script>


<Tailwindcss />


<header class="px-4 pt-12 pb-8">
  <div class="border-b border-gray-300 pb-5">
    <h1 class="font-extrabold text-4xl text-gray-900 leading-none tracking-tight">Get your Kemper Profiling Amp</h1>
    <p class="text-2xl text-gray-500 mt-4 font-light leading-tight">All your favorite amps and effects, together in one little box.</p>
  </div>
</header>

<main class="px-4 pb-16">
  <div class="mb-8">
    <div class="border border-gray-200 rounded-lg shadow-sm py-2">
      <img class="mx-auto" src="/img/head-black_front.png" alt="">
    </div>
    <div class="flex justify-between mt-5">
      <div class="px-3 border-2 border-gray-700 rounded-lg shadow-sm">
        <img class="rounded-lg" src="/img/head-black_front.png" alt="">
      </div>
      <div class="px-3 mx-4 border border-gray-200 rounded-lg shadow-sm">
        <img class="rounded-lg" src="/img/head-black_front.png" alt="">
      </div>
      <div class="px-3 border border-gray-200 rounded-lg shadow-sm">
        <img class="rounded-lg" src="/img/head-black_front.png" alt="">
      </div>
    </div>
  </div>

  <div>
    <span class="text-gray-500 text-sm">Starting at</span>
    <h3 class="text-5xl font-extrabold leading-none">$1,799</h3>
    <p class="text-gray-900 text-xl font-normal mt-5 leading-snug">
      The KEMPER PROFILER™ is the leading-edge digital guitar amplifier and all-in-one effects processor.
    </p>
    <p class="text-gray-500 text-lg mt-5">
      Hailed as a game-changer by guitarists the world over, the PROFILER™ is the first digital guitar amp to really nail the full and dynamic sound of a guitar or bass amp.
    </p>
    <p class="text-gray-500 text-lg mt-5">
      This is made possible by a radical, patented technology and concept which we call "PROFILING".
    </p>

    <div class="mt-16 text-gray-900">
      <h4 class="text-lg mb-3 font-medium">Form Factor</h4>
      <div class="">
        <div class="border-2 border-gray-700 rounded-lg p-5 px-6 mb-5 shadow-sm">
          <strong class="text-sm font-semibold">Profiler Head</strong>
          <p class="text-sm mt-2 leading-normal font-light text-gray-500">Compact amplifier head, perfect for a speaker cabinet or desk.</p>
        </div>
        <div class="border border-gray-200 rounded-lg p-5 px-6 shadow-sm">
          <strong class="text-sm font-semibold">Profiler Rack</strong>
          <p class="text-sm mt-2 leading-normal font-light text-gray-500">3U rackmount version of the classic profiling amplifier.</p>
        </div>
      </div>
    </div>

    <div class="mt-16 text-gray-900">
      <h4 class="text-lg mb-3 font-medium">Power Amp</h4>
      <div class="">
        <div class="border-2 border-gray-700 rounded-lg p-5 px-6 mb-5 shadow-sm">
          <strong class="text-sm font-semibold">None</strong>
          <p class="text-sm mt-2 leading-normal font-light text-gray-500">Use in the studio or with your own power amp.</p>
        </div>
        <div class="border border-gray-200 rounded-lg p-5 px-6 shadow-sm">
          <strong class="text-sm font-semibold">Powered</strong>
          <div>
            <p class="text-sm mt-2 leading-normal font-light text-gray-500">3U rackmount version of the classic profiling amplifier.</p>
          </div>
        </div>
      </div>
    </div>

  </div>
</main>