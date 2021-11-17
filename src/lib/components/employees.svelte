<script>
    import Card from "$lib/components/employeeCard.svelte"
    
    const employees = [
    
        {
            name: "Rebekah Morehouse",
            image: "img/employees/rebekah.jpg",
            bio: "\"I have been working in the home inspection business for 3+ years, scheduling inspections and providing high quality customer service. I look forward to assisting in anyway possible and improving my skills to continue serving our clients.\"",
        },
        {
            name: "Kalen Bahlman",
            image: "img/employees/kalen.jpg",
            bio: "Born and Raised in San Antonio Texas. Went to College in Virginia studied Political Science, Multimedia Journalism and creative writing. Has 5 years of Customer service and spare time collects everything Star Wars.",
        },
        {
            name: "Belinda Burnett",
            image: "img/employees/belinda.jpg",
            bio: "\"I am a Grandma to 4 boys and one girl and a Great Grandma to three girls and one boy. I have over 10 years in clerical and support staff experience. I am Blessed to be a part of Your Time Home Inspections family\"",
        },
        {
            name: "Elvia Williams",
            image: "img/employees/elvia.jpg",
            bio: "\"Wife & Mother of three amazing young men and a Sidney Lanier Graduate. Banker by trade & now proud Co-owner with my Husband James Williams of Your Time Home Inspections. We continue to be blessed beyond words.\""
        },
        { 
            name: "Roger Sandoval",
            image: "img/employees/roggie.jpg",
            bio: "Roger provides his creativity in producing films, advertisements, applications and more for the company. Born and Raised in San Antonio, Roger has trasitioned from working in the service and goods industry into the world of tech and music engineering. Currently working on mulitple projects including a Your Time Home Inspections exclusive WDI form application.",
        }
    ]

</script>

<section class="mt-10 flex flex-wrap mx-auto w-full gap-x-5 gap-y-5 justify-center md:justify-around">

    {#each employees as employee}
        <Card employee={employee} />
    {/each}

</section>