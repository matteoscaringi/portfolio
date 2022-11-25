<script>
    import "../app.css";

    import Icon from "@iconify/svelte";

    import PFP from "../../public/PFP.jpg"
</script>

<header class="h-screen">
    <nav />
    <div
        class="flex relative h-4/5 w-full mx-auto pt-[10%] justify-center"
    >
        <div class="flex w-full h-full items-center justify-center">
            <img
                src="{PFP}"
                alt="Mato"
                class="block h-[370px] w-[370px] rounded-3xl align-middle mx-[30px] ml-[150px]"
            />

            <div class="text-white text-xl">
                <p class="font font-bold">Hello there!</p>
                <h1 class="font font-medium w-[26ch]">
                    I’m Matteo student developer from Belgium.
                </h1>
            </div>

            <div class="flex flex-grow flex-col justify-center items-end mr-[74px] text-2xl gap-4">
                <Icon icon="simple-icons:discord" color="white" />
                <Icon icon="simple-icons:twitter" color="white" />
                <Icon icon="simple-icons:github" color="white" />
            </div>

            
        </div>
    </div>

    <div class="absolute bottom-0 left-0 h-[40px] w-full flex justify-center items-center text-6xl mb-[25px] animate-bounce">
        <Icon icon="ic:round-chevron-right" color="white" rotate={1} />
    </div>
</header>
