<script>
  import Tailwindcss from "./Tailwindcss.svelte";

  export let name;
</script>


<Tailwindcss />


<header class="px-4 sm:px-10 pt-12 pb-8">
  <div class="border-b border-gray-300 pb-5">
    <h1 class="font-extrabold text-4xl text-gray-900 leading-none tracking-tight">Get your Kemper Profiling Amp</h1>
    <p class="text-2xl sm:text-2xl text-gray-500 mt-4 font-light leading-tight">All your favorite amps and effects, together in one little box.</p>
  </div>
</header>

<main class="px-4 sm:px-10 pb-12">
  <div class="mb-8">
    <div class="border border-gray-200 rounded-lg shadow-sm py-2">
      <img class="mx-auto" src="/img/head-black_front.png" alt="">
    </div>
    <div class="grid gap-2 grid-cols-3 mt-5">
      <div class="px-3 border-2 border-gray-700 rounded-lg shadow-sm">
        <img class="rounded-lg" src="/img/head-black_front.png" alt="">
      </div>
      <div class="px-3 border border-gray-200 rounded-lg shadow-sm">
        <img class="rounded-lg" src="/img/head-black_front-side-left.png" alt="">
      </div>
      <div class="px-3 border border-gray-200 rounded-lg shadow-sm">
        <img class="rounded-lg" src="/img/powerhead_back.png" alt="">
      </div>
    </div>
  </div>

  <div>
    <span class="text-gray-500 text-sm">Starting at</span>
    <h3 class="text-5xl font-extrabold leading-none">$1,799</h3>
    <p class="text-gray-900 text-xl font-normal mt-5 leading-snug">
      The KEMPER PROFILER™ is the leading-edge digital guitar amplifier and all-in-one effects processor.
    </p>
    <p class="text-gray-500 font-light text-lg mt-5">
      Hailed as a game-changer by guitarists the world over, the PROFILER™ is the first digital guitar amp to really nail the full and dynamic sound of a guitar or bass amp.
    </p>
    <p class="text-gray-500 font-light text-lg mt-5">
      This is made possible by a radical, patented technology and concept which we call "PROFILING".
    </p>

    <div class="mt-12 text-gray-900">
      <h4 class="text-lg mb-3 font-medium text-gray-900">Form Factor</h4>
      <div class="sm:flex sm:justify-between sm:items-start">
        <div class="sm:w-1/2 sm:mr-2 border-2 border-gray-700 rounded-lg p-5 px-6 mb-5 shadow-sm">
          <strong class="text-sm mb-2 font-medium block">Profiler Head</strong>
          <p class="text-sm leading-normal font-light text-gray-500">Compact amplifier head, perfect for a speaker cabinet or desk.</p>
        </div>
        <div class="sm:w-1/2 sm:ml-2 border border-gray-200 rounded-lg p-5 px-6 shadow-sm">
          <strong class="text-sm mb-2 font-medium block">Profiler Rack</strong>
          <p class="text-sm leading-normal font-light text-gray-500">3U rackmount version of the classic profiling amplifier.</p>
        </div>
      </div>
    </div>

    <div class="mt-12 text-gray-900">
      <h4 class="text-lg mb-3 font-medium text-gray-900">Power Amp</h4>
      <div class="">
        <div class="border-2 border-gray-700 rounded-lg p-5 px-6 mb-5 shadow-sm">
          <strong class="text-sm mb-2 font-medium block">None</strong>
          <p class="text-sm leading-normal font-light text-gray-500">Use in the studio or with your own power amp.</p>
        </div>
        <div class="border border-gray-200 rounded-lg p-5 px-6 shadow-sm">
          <strong class="text-sm mb-2 font-medium block">Powered</strong>
          <div class="flex justify-between">
            <p class="flex-1 text-sm leading-normal font-light text-gray-500">3U rackmount version of the classic profiling amplifier.</p>
            <span class="text-sm font-light ml-3">+ $449</span>
          </div>
        </div>
      </div>
    </div>

    <div class="mt-12 text-gray-900">
      <h4 class="text-lg mb-3 font-medium text-gray-900">Foot Controller</h4>
      <div class="">
        <div class="border-2 border-gray-700 rounded-lg p-5 px-6 mb-5 shadow-sm">
          <div class="flex justify-between">
            <p class="flex-1 text-sm font-medium block">None</p>
            <span class="text-sm font-light ml-3">+ $449</span>
          </div>
        </div>
        <div class="border border-gray-200 rounded-lg p-5 px-6 shadow-sm">
          <strong class="text-sm font-medium block">Profiler Remote Foot Controller</strong>
        </div>
      </div>
    </div>

  </div>

  <div class="mt-12 text-gray-900">
    <h4 class="text-lg font-medium border-b border-gray-200 pb-2 text-gray-900">Specifications</h4>

    <div class="flex justify-between py-5 border-b border-gray-200">
      <span>Amp Models</span>
      <span>200</span>
    </div>

    <div class="flex justify-between py-5 border-b border-gray-200">
      <span>Effects Loop</span>
      <span>Yes</span>
    </div>

    <div class="flex justify-between py-5 border-b border-gray-200">
      <span>Inputs</span>
      <span>2 x 1/4”</span>
    </div>

    <div class="flex justify-between py-5 border-b border-gray-200">
      <span>Outputs</span>
      <span>1 x 1/4”, 2 x XLR, 2 x 1/4”</span>
    </div>

    <div class="flex justify-between py-5 border-b border-gray-200">
      <span>MIDI I/O</span>
      <span>In/Out/Thru</span>
    </div>

    <div class="flex justify-between py-5 border-b border-gray-200">
      <span>Height</span>
      <span>8.54”</span>
    </div>

    <div class="flex justify-between py-5 border-b border-gray-200">
      <span>Width</span>
      <span>14.88”</span>
    </div>

    <div class="flex justify-between py-5 border-b border-gray-200">
      <span>Depth</span>
      <span>6.81”</span>
    </div>

    <div class="flex justify-between py-5 border-b border-gray-200">
      <span>Weight</span>
      <span>11.73 lbs</span>
    </div>
  </div>
</main>

<footer class="py-5 px-4 bg-gray-50 border-t border-gray-200">
  <div class="flex items-center justify-between">
    <div class="flex-1 text-right pr-5">
      <span class="text-gray-900 text-4xl font-bold">$2,717</span>
    </div>
    <a href="#" class="inline-block text-white bg-gray-900 px-5 py-3 rounded-lg">Buy now</a>
  </div>
</footer>