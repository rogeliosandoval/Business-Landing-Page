<script>
    export let displayModal;
</script>

{#if displayModal}
<div class="modal-bg">
    <div class="modal-container p-7 text-center font-sans border-solid border-8 border-blue-600">
        <p class="font-bold pb-5 text-3xl">
            Inspector
        </p>

        <p class="text-gray-700 text-base">
            Join our team of inspectors and help others find piece within their porperties. Our inspectors are what drive this business and we would love to have you on the team!
        </p>

        <button class="bg-red-500 hover:bg-red-400 text-black font-bold py-2 px-4 border-b-4 border-red-700 hover:border-red-500 rounded"on:click="{() => displayModal = false}">Close</button>
    </div>
</div>
{/if}

<style>
    .modal-bg{
        width: 100vw;
        height: 100vh;
        top: 0;
        left: 0;
        background-color: rgba(0,0,0,0.7);
        position: absolute;
        z-index: 444;
    }

    .modal-container{
        width: 600px;
        height: 500px;
        margin: 0 auto;
        position: relative;
        top: 25%;
        background-color: cornsilk
    }
</style>