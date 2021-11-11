<script>

    export let employee

</script>

<div class="flex justify-center gap-x-2 max-w-2xl text-center">

    <img class="mx-auto" alt="{employee.name}" src="{employee.image}">

    <div class="py-4 px-4 bg-yellow-300 flex flex-col">

        <p class="font-bold text-3xl p-4">{employee.name}</p>
        <p class="tracking-wider">"{employee.bio}"</p>

    </div>

</div>

<style>

    img{
        width: 305px;
        height: 360px;
        border: 5px solid white;
    }

</style>