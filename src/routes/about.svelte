<link rel="stylesheet" href="https://demos.creative-tim.com/notus-js/assets/styles/tailwind.css">
<link rel="stylesheet" href="https://demos.creative-tim.com/notus-js/assets/vendor/@fortawesome/fontawesome-free/css/all.min.css">

<script>
    import Card from "$lib/components/card.svelte"
    
    const employees = [
    
        {
            name: "Rebekah Morehouse",
            image: "../../img/employees/rebekah.jpg",
            bio: "I have been working in the home inspection business for 3+ years, scheduling inspections and providing high quality customer service. I look forward to assisting in anyway possible and improving my skills to continue serving our clients.",
        },
        {
            name: "Kalen Bahlman",
            image: "../../img/employees/kalen.jpg",
            bio: "Born and Raised in San Antonio Texas. Went to College in Virginia studied Political Science, Multimedia Journalism and creative writing. Has 5 years of Customer service and spare time collects everything Star Wars.",
        },
        {
            name: "Belinda Burnett",
            image: "../../img/employees/belinda.jpg",
            bio: "I am a Grandma to 4 boys and one girl and a Great Grandma to three girls and one boy. I have over 10 years in clerical and support staff experience. I am Blessed to be a part of Your Time Home Inspections family",
        },
        {
            name: "Elvia Williams",
            image: "../../img/employees/elvia.jpg",
            bio: "Wife & Mother of three amazing young men and a Sidney Lanier Graduate. Banker by trade & now proud Co-owner with my Husband James Williams of Your Time Home Inspections. We continue to be blessed beyond words."
        },
        { 
            name: "Roger Sandoval",
            image: "../../img/employees/roggie.jpg",
            bio: "I am a Grandma to 4 boys and one girl and a Great Grandma to three girls and one boy. I have over 10 years in clerical and support staff experience. I am Blessed to be a part of Your Time Home Inspections family.",
        }
    ]

    const employees2 = [
        {
            name: "James Williams",
            image: "../../img/employees/james.jpg",
            bio: "James is co-owner and lead inspector of Your Time Home Inspections. He has been in the construction field both in residential and commercial his whole career to include commercial construction and commercial concrete.",
            trec: "21507"
        },
        {
            name: "Luis Vargas",
            image: "../../img/employees/luis.jpg",
            bio: "I am very motivated and enthusiastic to help people when buying/selling a home. Married and father of an amazing woman. I speak Spanish and graduated in Mechanical Engineering.",
            trec: "23535"
        },
        {
            name: "Robbie Spencer",
            image: "../../img/employees/robbie.jpg",
            bio: "Proud Retired ARMY Staff Sergeant, Combat Veteran, and Patriot enlisting to follow in my father’s footsteps. I’m extremely proud to be a part of Your Time Home Inspections and eager to serve your home inspection needs!",
            trec: "23968"
        },
        {
            name: "Nicholas Pooley",
            image: "../../img/employees/nicholas.jpg",
            bio: "Owned his own Home Inspection Company in Maine called “ Bay view Home Inspections”. Has two cats one is 8 years old named Daryl Loves to play Bass on his spare time and Bartend.",
            trec: "24758"
        }
    ]

</script>

<style>

    .bigvid {
    filter: brightness(50%);
    }

    .cent {
    width: 1150px;
    position: absolute;
    top: 8%;
    left: 50%;
    transform: translate(-50%, -50%);
    }

    .cent2 {
    width: 1150px;
    height: 424px;
    position: absolute;
    top: 53%;
    left: 50%;
    transform: translate(-50%, -50%);
    }

    .cent3 {
    width: 1150px;
    height: 424px;
    position: absolute;
    top: 73%;
    left: 50%;
    transform: translate(-50%, -50%);
    }

</style>

<section class="relative pb-12 bg-yellow-200 font-sans">

    <div class="mx-auto">
        <video class="bigvid mx-auto border-t-4 border-b-4 border-blue-500 object-cover h-96 w-full" style="width:100%" muted autoplay loop>
        <source src="https://yourtimehomeinspections.com/wp-content/uploads/2020/08/Preview-yourtime-site-vids-2-2.mp4" type="video/mp4" />
        </video>
        
        <div class="cent container mx-auto text-center">

            <div class="text-white font-bold text-5xl tracking-wider pb-10">
                We Want To Be Your Home Inspection Team
            </div>
            
            <div class="pb-40 text-white font-bold">
                <a class="bg-yellow-600 rounded-lg hover:bg-yellow-700 px-3 py-3" href="#" style="border:3px solid white">200% GUARANTEE <i class="text-white fa fa-shield"></i></a>
            </div>

        </div>
    </div>

    <!-- <div class="text-6xl font-bold text-black text-center pt-7 pb-7">
        About Us!
    </div>  -->

    <div class="container mx-auto pt-16 pb-16 text-center grid grid-cols-2 gap-x-20">
        
        <div>
            <img class="mx-auto" style="width:390px;height:350px;" alt="house" src="../../img/bighouse.webp">
        </div>

        <div>
            <p>The Right Choice</p>
            <p class="font-bold text-4xl">Home Inspector In San Antonio, TX</p>
            <br>
            <p class="tracking-wide">Your Time Home Inspections prides itself on following a comprehensive standard of practice which ensures our clients will receive a detailed accurate home inspection. We abide by a strict code of ethics, which puts each client’s interest first</p>
            <br>
            <p class="tracking-wide">We are members of SABOR, TPREIA, as well as a certified professional inspector, trained and certified by InterNachi. Call or book your home inspection online today.</p>
        </div>

    </div>

    <div class="px-80 py-12 mx-auto bg-yellow-600 grid grid-cols-2 gap-x-10">

        <div class="px-9 py-8">
            <p class="font-bold text-xl">Our Owners</p>
            <p class="font-bold text-5xl text-white tracking-wide pt-5">James & Elvia Williams</p>
            <p class="font-bold  text-white pt-5 text-xl">Our Promise To You</p>
            <p class="tracking-widest text-white">Choosing the right home inspector can be difficult. Different inspectors have varying qualifications, equipment, experience, reporting methods, and pricing. One thing that’s certain is that a home inspection requires a lot of work. Ultimately, a thorough inspection depends heavily on the individual inspector’s effort. If you honor us with your trust to inspect your new home, we guarantee that we will give you a very best effort. This is our promise to you.</p>
            <p class="font-bold text-white pt-5 text-xl">Giving Back</p>
            <p class="tracking-widest text-white">We believe that true success is about more than growing a Home Inspection business; we devote time each year to charitable causes that benefit diverse populations. From helping the homeless to sponsoring charities that help families adopt children, Your Time Home Inspections is committed to improving the town we call home.</p>
        </div>

        <div>
            <img class="mx-auto" style="border: 5px solid white" alt="owners" src="https://yourtimehomeinspections.com/wp-content/uploads/2020/08/yourtimeowners-768x768.jpg">
        </div>
    </div>

    <div class="mx-auto pt-10">
        <video class="bigvid mx-auto border-t-4 border-b-4 border-blue-500 object-cover h-96 w-full" style="width:100%" muted autoplay loop>
        <source src="https://yourtimehomeinspections.com//wp-content//uploads//2020//08//Preview-yourtime-site-vids-3.mp4" type="video/mp4" />
        </video>
        
        <div class="cent2 container mx-auto text-center">

            <div class="text-white tracking-wider text-lg">
                Your Time Home Inspections
            </div>
            
            <div class="pb-40 text-white font-bold">
                <p class="font-bold text-6xl tracking-wider">Our Support Team</p>
            </div>

        </div>
    </div>

    <section class="mt-10 flex flex-wrap mx-auto w-3/4 gap-16 justify-center">

        {#each employees as employee}
            <Card employee={employee} />
        {/each}

    </section>

    <div class="mx-auto pt-10">
        <video class="bigvid mx-auto border-t-4 border-b-4 border-blue-500 object-cover h-96 w-full" style="width:100%" muted autoplay loop>
        <source src="https://metrixhosting.com/wp-content/uploads/2020/08/Preview-yourtime-site-vids-1.mp4" type="video/mp4" />
        </video>
        
        <div class="cent3 container mx-auto text-center">

            <div class="text-white tracking-wider text-lg">
                Your Time Home Inspections
            </div>
            
            <div class="pb-40 text-white font-bold">
                <p class="font-bold text-6xl tracking-wider">Your Home Inspectors</p>
            </div>

        </div>
    </div>

    <section class="mt-10 flex flex-wrap mx-auto w-3/4 gap-16 justify-center">

        {#each employees2 as employee}
            <Card employee={employee} />
        {/each}

    </section>

</section>