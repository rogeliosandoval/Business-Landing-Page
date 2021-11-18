<script>

    import Employees from "$lib/components/employees.svelte"
    import Inspectors from "$lib/components/inspectors.svelte"

</script>

<style>

    .bigvid {
    filter: brightness(50%);
    }

    #career {
    display: none;
    }

    #career2 {
    display:none;
    }

    #career3 {
    display: none;
    }

    @media screen and (min-width: 1536px) {

        .cent2 {
        position: absolute;
        top: 39.2%;
        left: 50%;
        transform: translate(-50%, -50%);
        font-size: 65px;
        }

        .cent3 {
        position: absolute;
        top: 69.2%;
        left: 50%;
        transform: translate(-50%, -50%);
        font-size: 65px;
        }

        #career2 {
        display: inline-block;
        }

        #career3 {
        display: inline-block;
        }

    }

    @media screen and (min-width: 1280px) {
        #word {
            font-size: 30px;
        }

        #word2 {
            font-size: 54px;
            text-shadow: black 0px 0px 10px;
        }

        #word3 {
            font-size: 21px;
        }

        .cent {
        position: absolute;
        top: 4%;
        left: 50%;
        transform: translate(-50%, -50%);
        font-size: 40px;
        }

        #career { 
        display: inline-block;
        }

    }

    @media screen and (min-width:640px) and (max-width:1280px) {

        .cent {
        position: absolute;
        top: 3%;
        left: 50%;
        transform: translate(-50%, -50%);
        font-size: 28px;
        }

        #career {
        display: inline-block;
        }

        #word {
            font-size: 25px;
        }

        #word2 {
            font-size: 44px;
            text-shadow: black 0px 0px 10px;
        }

        #word3 {
            font-size: 17px;
        }
    }

    @media screen and (max-width: 640px) {

        .cent {
        position: absolute;
        top: 2%;
        left: 50%;
        transform: translate(-50%, -50%);
        font-size: 23px;
        }

        .cent2 {
        position: absolute;
        top:27.6%;
        left:50%;
        transform: translate(-50%, -50%);
        font-size: 35px;
        }

        .cent3 {
        position: absolute;
        top:65%;
        left:50%;
        transform: translate(-50%, -50%);
        font-size: 27px;
        }

        #career { 
        display: inline-block;
        }

        #career2 {
        display: inline-block;
        }

        #career3 {
        display: inline-block;
        }

    }


</style>

<section class="relative bg-yellow-200 font-sans">

    <div class="mx-auto">
        <video class="bigvid mx-auto border-t-4 border-b-4 border-blue-500 object-cover h-96 w-full" style="width:100%" muted autoplay loop>
        <source src="https://yourtimehomeinspections.com/wp-content/uploads/2020/08/Preview-yourtime-site-vids-2-2.mp4" type="video/mp4" />
        </video>

        <div class="cent mx-auto text-center" id="career">

            <div class="text-white pb-5 font-bold" style="text-shadow:black 0px 0px 10px;">
                We Want To Be Your Home Inspection Team
            </div>
            
            <div class="text-white">
                <a class="bg-yellow-600 rounded-lg hover:bg-yellow-700 px-2 py-2 text-sm" href="#" style="border:3px solid white">200% GUARANTEE <i class="text-white fa fa-shield"></i></a>
            </div>
        </div>
        
        <!-- <div class="cent container mx-auto text-center">

            <div class="text-white font-bold text-5xl tracking-wider pb-10" style="text-shadow:black 0px 0px 10px;">
                We Want To Be Your Home Inspection Team
            </div>
            
            <div class="pb-40 text-white font-bold">
                <a class="bg-yellow-600 rounded-lg hover:bg-yellow-700 px-3 py-3" href="#" style="border:3px solid white">200% GUARANTEE <i class="text-white fa fa-shield"></i></a>
            </div>

        </div> -->

    </div>

    <div class="container mx-auto pt-5 md:pt-16 pb-16 text-center grid grid-rows-1 md:grid-cols-2 md:gap-x-20">
        
        <div>
            <img class="mx-auto pt-5 pb-5" style="width:390px;height:350px;" alt="house" src="../../img/bighouse.webp">
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

    <div class="text-center py-12 xl:px-10 mx-auto bg-yellow-600 grid grid-rows-1 xl:grid-cols-2 xl:gap-x-10">

        <div class="px-3 py-2 xl:px-9 xl:py-8">
            <p class="font-bold text-xl md:pt-12" id="word">Our Owners</p>
            <p class="font-bold text-2xl md:text-5xl text-white tracking-wide pt-5 md:pb-10" id="word2">James & Elvia Williams</p>
            <p class="font-bold  text-white pt-5 pb-5 text-xl" id="word">Our Promise To You</p>
            <p class="tracking-widest text-white md:pb-5 lg:pb-10 md:px-11" id="word3">Choosing the right home inspector can be difficult. Different inspectors have varying qualifications, equipment, experience, reporting methods, and pricing. One thing that’s certain is that a home inspection requires a lot of work. Ultimately, a thorough inspection depends heavily on the individual inspector’s effort. If you honor us with your trust to inspect your new home, we guarantee that we will give you a very best effort. This is our promise to you.</p>
            <p class="font-bold text-white pt-5 pb-5 text-xl" id="word">Giving Back</p>
            <p class="tracking-widest text-white md:px-11" id="word3">We believe that true success is about more than growing a Home Inspection business; we devote time each year to charitable causes that benefit diverse populations. From helping the homeless to sponsoring charities that help families adopt children, Your Time Home Inspections is committed to improving the town we call home.</p>
        </div>

        <div class="pt-8">
            <img class="mx-auto" style="border: 5px solid white" alt="owners" src="https://yourtimehomeinspections.com/wp-content/uploads/2020/08/yourtimeowners-768x768.jpg">
        </div>
    </div>

    <div class="mx-auto md:pt-10">
        <video class="bigvid mx-auto border-t-4 border-b-4 border-blue-500 object-cover h-64 2xl:h-96 w-full" style="width:100%" muted autoplay loop>
        <source src="https://yourtimehomeinspections.com//wp-content//uploads//2020//08//Preview-yourtime-site-vids-3.mp4" type="video/mp4" />
        </video>

        <div class="cent2 container mx-auto text-center" id="career2">

            <div class="text-white tracking-wider text-lg">
                Your Time Home Inspections
            </div>
            
            <div class="pb-40 text-white font-bold">
                <p class="font-bold tracking-wider" style="text-shadow:black 0px 0px 10px;">Our Support Team</p>
            </div>

        </div>
        
        <!-- <div class="cent2 container mx-auto text-center">

            <div class="text-white tracking-wider text-lg">
                Your Time Home Inspections
            </div>
            
            <div class="pb-40 text-white font-bold">
                <p class="font-bold text-6xl tracking-wider">Our Support Team</p>
            </div>

        </div> -->
    </div>

    <Employees />

    <div class="mx-auto pt-10">
        <video class="bigvid mx-auto border-t-4 border-b-4 border-blue-500 object-cover h-64 2xl:h-96 w-full" style="width:100%" muted autoplay loop>
        <source src="https://metrixhosting.com/wp-content/uploads/2020/08/Preview-yourtime-site-vids-1.mp4" type="video/mp4" />
        </video>

        <div class="cent3 container mx-auto text-center" id="career3">

            <div class="text-white tracking-wider text-sm">
                Your Time Home Inspections
            </div>
            
            <div class="pb-40 text-white font-bold">
                <p class="font-bold tracking-wider" style="text-shadow:black 0px 0px 10px;">Your Home Inspectors</p>
            </div>

        </div>
        
        <!-- <div class="cent3 container mx-auto text-center">

            <div class="text-white tracking-wider text-lg">
                Your Time Home Inspections
            </div>
            
            <div class="pb-40 text-white font-bold">
                <p class="font-bold text-6xl tracking-wider">Your Home Inspectors</p>
            </div>

        </div> -->
    </div>

    <Inspectors />

    <div class="mx-auto text-center pt-8 sm:py-6 lg:py-12 font-sans">
        <p class="tracking-widest bg-yellow-600 p-5 text-3xl sm:text-5xl lg:text-6xl">Our Certifications</p>
    </div>
     
    <div class="container mx-auto">
        <div class="grid grid-cols-5 gap-4 text-center bg-white p-5">

        <!-- {#each [1,2,3,4,5,6,7,8,9,10,11,12,13,14,15] as n}

            <div class="mx-auto">
                <img alt="cert{n}" src="img/icons/c{n}.png">
            </div>

        {/each} -->

        <div class="mx-auto">
            <img alt="cert1" src="../../img/icons/c1.png">
        </div>
    
        <div class="mx-auto">
            <img alt="cert2" src="../../img/icons/c2.png">
        </div>
    
        <div class="mx-auto">
            <img alt="cert3" src="../../img/icons/c3.png">
        </div>
    
        <div class="mx-auto">
            <img alt="cert4" src="../../img/icons/c4.png">
        </div>
    
        <div class="mx-auto">
            <img alt="cert5" src="../../img/icons/c5.png">
        </div>
    
        <div class="mx-auto">
            <img alt="cert6" src="../../img/icons/c6.jpeg">
        </div>
    
        <div class="mx-auto">
            <img alt="cert7" src="../../img/icons/c7.png">
        </div>
    
        <div class="mx-auto">
            <img alt="cert8" src="../../img/icons/c8.png">
        </div>
    
        <div class="mx-auto">
            <img alt="cert9" src="../../img/icons/c9.png">
        </div>
    
        <div class="mx-auto">
            <img alt="cert10" src="../../img/icons/c10.png">
        </div>
    
        <div class="mx-auto">
            <img alt="cert11" src="../../img/icons/c11.png">
        </div>
    
        <div class="mx-auto">
            <img alt="cert12" src="../../img/icons/c12.png">
        </div>
    
        <div class="mx-auto">
            <img alt="cert13" src="../../img/icons/c13.png">
        </div>
    
        <div class="mx-auto">
            <img alt="cert14" src="../../img/icons/c14.png">
        </div>
    
        <div class="mx-auto pt-8">
            <img alt="cert15" src="../../img/icons/c15.gif">
        </div>
    
        </div>
    </div>

</section>