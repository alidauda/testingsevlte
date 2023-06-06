<script lang="ts">
    import "@unocss/reset/tailwind.css"; // https://github.com/unocss/unocss#style-resetting
    import "uno.css"; // https://github.com/unocss/unocss/tree/main/packages/vite#installation
  </script>
  <div class="h-screen w-full text-black bg-gray flex justify-center items-center flex-col">
    <slot />
  </div>