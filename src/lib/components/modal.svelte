<script>
    export let displayModal;
    export let displayModal2;
</script>

{#if displayModal}
<div class="modal-bg">
    <div class="modal-container p-7 text-center font-sans border-solid border-8 border-blue-600">
        <p class="font-bold pb-5 text-3xl">
            Inspector
        </p>

        <p class="text-black text-sm pb-5 font-bold">
            Join our team of inspectors and help others find peace within their porperties. Our inspectors are what drive this business and we would love to have you on the team! Our inspectors make everything possible.
        </p>

        <div class="container grid grid-cols-2 gap-2 pb-5">

            <div>
                <video class="bigvid mx-auto" style="width:100%" muted autoplay loop>
                    <source src="https://metrixhosting.com/wp-content/uploads/2020/08/Preview-yourtime-site-vids-1.mp4" type="video/mp4" />
                  </video>
            </div>

            <div class="mx-auto">
                <p class="font-bold pb-1">Some of the expectations</p>
                <ul class="list-disc">
                    <li>checking light fictures</li>
                    <li>observing the plumbing</li>
                    <li>checking foundation</li>
                    <li>going on roofs</li>
                    <li>writting up reports</li>
                </ul>
            </div>

        </div>

        <button class="bg-red-500 hover:bg-red-400 text-black font-bold py-2 px-4 border-b-4 border-red-700 hover:border-red-500 rounded m-10 pt-4"on:click="{() => displayModal = false}">Close</button>
        
    </div>
</div>
{/if}

{#if displayModal2}
<div class="modal-bg">
    <div class="modal-container p-7 text-center font-sans border-solid border-8 border-blue-600">
        <p class="font-bold pb-5 text-3xl">
            Client Coordinator
        </p>

        <p class="text-gray-700 text-base pb-5">
            Our client coordinators play an essential role in getting our inspectors to you. Help book inspections, set up events, or simply explain what Your Time Home Inspections is all about with generalized information.
        </p>
        
        <button class="bg-red-500 hover:bg-red-400 text-black font-bold py-2 px-4 border-b-4 border-red-700 hover:border-red-500 rounded "on:click="{() => displayModal2 = false}">Close</button>
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