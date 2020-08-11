<script>
  import Tailwindcss from "./Tailwindcss.svelte"
  import Button from "./components/Button.svelte"

  export let name
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

<footer class="py-5 px-4 sm:px-10 bg-gray-50 border-t border-gray-200">
  <div class="flex items-center sm:items-end justify-between">
    <div class="hidden sm:block">
      <ul>
        <li class="flex items-center mb-3">
          <svg class="mr-3" width="16" height="16" fill="none" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" clip-rule="evenodd" d="M8 16A8 8 0 108 0a8 8 0 000 16zM2.332 6.027a6.012 6.012 0 011.912-2.706C4.512 3.73 4.974 4 5.5 4A1.5 1.5 0 017 5.5V6a2 2 0 004 0 2 2 0 011.523-1.943A5.977 5.977 0 0114 8c0 .34-.028.675-.083 1H13a2 2 0 00-2 2v2.197A5.973 5.973 0 018 14v-2a2 2 0 00-2-2 2 2 0 01-2-2 2 2 0 00-1.668-1.973z" fill="#9FA6B2"/></svg>
          Free Shipping
        </li>
        <li class="flex items-center">
          <svg class="mr-3" width="16" height="18" fill="none" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" clip-rule="evenodd" d="M.166 3.999A11.954 11.954 0 008 .944 11.954 11.954 0 0015.834 4c.11.65.166 1.32.166 2.001 0 5.225-3.34 9.67-8 11.317C3.34 15.67 0 11.225 0 6c0-.682.057-1.35.166-2.001zm11.541 3.708a1 1 0 00-1.414-1.414L7 9.586 5.707 8.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" fill="#9FA6B2"/></svg>
          2 Year Warranty
        </li>
      </ul>
    </div>
    <div class="flex-1 text-right pr-5">
      <span class="text-gray-900 text-4xl font-bold">$2,717</span>
      <p class="hidden sm:block text-gray-500">Need a financing? <a href="#" class="visited:text-gray-500 hover:text-gray-100 underline">Learn more</a></p>
    </div>
    <Button src="#">Buy now</Button>
  </div>
</footer>