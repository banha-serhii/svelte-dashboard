<script>
  import LogoIcon from "../components/IconLogo.svelte";
  import IconAccount from "../components/IconAccount.svelte";
  import IconSettings from "../components/IconSettings.svelte";
</script>

<!-- component -->
<aside class="flex">
  <div class="flex rounded rounded-l-none  flex-col items-center w-16 h-screen py-8 space-y-8 bg-white dark:bg-gray-900 dark:border-gray-700">
    <a href={"#"}>
     <LogoIcon />
    </a>

    <a href={"#"} class="p-1.5 text-gray-500 focus:outline-nones transition-colors duration-200 rounded-lg dark:text-gray-400 dark:hover:bg-gray-800 hover:bg-gray-100">
    <IconAccount />
    </a>

    <a href={"#"} class="p-1.5 text-gray-500 focus:outline-nones transition-colors duration-200 rounded-lg dark:text-gray-400 dark:hover:bg-gray-800 hover:bg-gray-100">
    <IconSettings />
    </a>
  </div>
</aside>

<style lang="postcss">
    :global(html) {
        background-color:  #13132E;
    }
</style>