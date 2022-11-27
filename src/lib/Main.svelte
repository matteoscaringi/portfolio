<script>
  import "../app.css";
  import Icon from "@iconify/svelte";
  import PFP from "../../public/PFP.jpg";
</script>

<header class="h-screen">
  <nav />
  <div
    class="relative flex h-4/5 w-full flex-col items-center justify-center gap-10 px-10 pt-[10%] sm:mx-0 md:mx-auto md:flex-row md:gap-0"
  >
    <img
      src={PFP}
      alt="Mato"
      class="block max-h-[370px] w-full max-w-[370px] flex-shrink rounded-3xl align-middle md:mx-[30px] lg:ml-[150px]"
    />

    <div class="text-xl text-white">
      <p class="font font-bold">Hello there!</p>
      <h1 class="font max-w-[26ch] font-medium">
        I’m Matteo student developer from Belgium.
      </h1>
    </div>

    <div
      class=" flex flex-row items-end justify-center gap-4 text-3xl md:mt-0 md:mr-[74px] md:flex-grow md:flex-col"
    >
      <Icon icon="simple-icons:discord" color="white" />
      <a
        href="https://twitter.com/matte0_s"
        target="_blank"
        rel="noreferrer noopener"
      >
        <Icon icon="simple-icons:twitter" color="white" />
      </a>
      <a
        href="https://github.com/matteoscaringi"
        target="_blank"
        rel="noreferrer noopener"
      >
        <Icon icon="simple-icons:github" color="white" />
      </a>
    </div>
  </div>

  <div
    class="absolute bottom-0 left-0 mb-[25px] flex h-[40px] w-full animate-bounce items-center justify-center text-6xl"
  >
    <a href="#projects" class="scroll-smooth">
      <Icon icon="ic:round-chevron-right" color="white" rotate={1} />
    </a>
  </div>
</header>
