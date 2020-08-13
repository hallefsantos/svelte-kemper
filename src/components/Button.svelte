<script>
   export let src;
</script>

<a href={src} 
   class="inline-block text-white visited:text-white hover:bg-gray-700 hover:no-underline bg-gray-900 focus:shadow-outline px-5 py-3 sm:mb-3 rounded-lg transition duration-300">
   <slot></slot>
</a>