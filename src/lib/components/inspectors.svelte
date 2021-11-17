<script>
    import InspectorCard from "$lib/components/inspectorCard.svelte"

    const inspectors = [
        {
            name: "James Williams",
            image: "img/employees/james.jpg",
            bio: "James is co-owner and lead inspector of Your Time Home Inspections. He has been in the construction field both in residential and commercial his whole career to include commercial construction and commercial concrete.",
            trec: "21507"
        },
        {
            name: "Luis Vargas",
            image: "img/employees/luis.jpg",
            bio: "\"I am very motivated and enthusiastic to help people when buying/selling a home. Married and father of an amazing woman. I speak Spanish and graduated in Mechanical Engineering.\"",
            trec: "23535"
        },
        {
            name: "Robbie Spencer",
            image: "img/employees/robbie.jpg",
            bio: "\"Proud Retired ARMY Staff Sergeant, Combat Veteran, and Patriot enlisting to follow in my father’s footsteps. I’m extremely proud to be a part of Your Time Home Inspections and eager to serve your home inspection needs!\"",
            trec: "23968"
        },
        {
            name: "Nicholas Pooley",
            image: "img/employees/nicholas.jpg",
            bio: "Owned his own Home Inspection Company in Maine called “ Bay view Home Inspections”. Has two cats one is 8 years old named Daryl Loves to play Bass on his spare time and Bartend.",
            trec: "24758"
        }
    ]

</script>

<section class="mt-10 flex flex-wrap mx-auto w-full gap-x-5 gap-y-5 justify-center md:justify-around">

    {#each inspectors as inspector}
        <InspectorCard employee={inspector} />
    {/each}

</section>