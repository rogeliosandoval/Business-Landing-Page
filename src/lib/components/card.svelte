<div class="flex justify-center gap-x-2 max-w-xl ">

    <slot name="cardImage" />
    
    <div class="py-4 px-4 bg-yellow-300 flex flex-col">
        <slot name="cardTitle" />
        <slot />
    </div>

</div>