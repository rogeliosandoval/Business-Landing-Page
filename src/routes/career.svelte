<!-- component -->
<link rel="stylesheet" href="https://demos.creative-tim.com/notus-js/assets/styles/tailwind.css">
<link rel="stylesheet" href="https://demos.creative-tim.com/notus-js/assets/vendor/@fortawesome/fontawesome-free/css/all.min.css">

<style>

    .bigvid {
    filter: brightness(50%);
    }

    .cent {
    width: 1150px;
    position: absolute;
    top: 25%;
    left: 50%;
    transform: translate(-50%, -50%);
    }

</style>

<section class="relative pb-12 pt-12 bg-yellow-200 font-sans">

    <div class="container mx-auto">
        <video class="bigvid mx-auto border-t-4 border-b-4 border-blue-500" style="width:100%" muted autoplay loop>
        <source src="https://yourtimehomeinspections.com/wp-content/uploads/2020/08/Preview-yourtime-site-vids-2-2.mp4" type="video/mp4" />
        </video>
        
        <div class="cent container mx-auto text-center">

            <div class="text-white">
                get a career with
            </div>
            
            <div class="pb-40 text-6xl text-white font-bold">
                YOUR TIME HOME INSPECTIONS
            </div>

        <div class="grid grid-cols-3 gap-x-20">
        
            <div class="max-w-sm rounded overflow-hidden shadow-lg bg-blue-100">
            <img class="mx-auto pt-5" style="width:70px;height:100px;" alt="inspector" src="../../img/inspector.png">
            <div class="px-6 py-4">
                <div class="font-bold text-xl mb-2">Inspector</div>
                <p class="text-gray-700 text-base">
                    Join our team of inspectors and help others find piece within their porperties. Our inspectors are what drive this business and we would love to have you on the team!
                </p>
            </div>
            </div>

            <div class="max-w-sm rounded overflow-hidden shadow-lg bg-blue-100 pb-7">
            <img class="mx-auto pt-5" style="width:103px;height:115px;" alt="client" src="../../img/client.png">
            <div class="px-6 py-4">
                <div class="font-bold text-xl mb-2">Client Coordinator</div>
                <p class="text-gray-700 text-base">
                    Our client coordinators play an essential role in getting our inspectors to you. Help book inspections, set up events, or simply explain what Your Time Home Inspections is all about with generalized information.
                </p>
            </div>
            </div>

            <div class="max-w-sm rounded overflow-hidden shadow-lg bg-blue-100">
            <img class="mx-auto pt-5" style="width:90px;height:115px;" alt="penguin" src="../../img/penguin.png">
            <div class="px-6 py-4">
                <div class="font-bold text-xl mb-2">Marketer/Tech</div>
                <p class="text-gray-700 text-base">
                    Help us spread the word on social media and take on a developer role! Or help us market by dropping off flyers, creating videos and/or attending events to help out the business!
                </p>
            </div>
            </div>

        </div>
        </div>
    </div>

    <div class="container w-1/2 mx-auto pt-20">

        <form class="bg-white shadow-md rounded px-8 pt-6 pb-8 mb-4">

            <label class="block text-grey-700 text-sm font-bold mb-2" for="interest">Position Of Interest</label>
            <label class="text-sm text-blue-600 pl-4"><input type="radio" name="interests" value="Inspector"> Inspector</label>
            <label class="text-sm text-yellow-800 pl-4"><input type="radio" name="interests" value="Client Coordinator"> Client Coordinator</label>
            <label class="text-sm text-green-700 pl-4"><input type="radio" name="interests" value="Marketer/Tech"> Marketer/Tech</label>
            <label class="text-sm text-black pl-4"><input type="radio" name="interests" value="Other"> Other</label>

            <label class="block text-black text-sm font-bold mb-2 pt-6" for="firstName">First Name</label>
            <input class="w-full" id="firstName" type="text" placeholder="First Name">

            <label class="block text-black text-sm font-bold mb-2 pt-6" for="lastName">Last Name</label>
            <input class="w-full" id="lastName" type="text" placeholder="Last Name">

            <label class="block text-black text-sm font-bold mb-2 pt-6" for="phoneNumber">Phone Number</label>
            <input class="w-full" id="phoneNumber" type="text" placeholder="(xxx) xxx-xxxx">

            <label class="block text-black text-sm font-bold mb-2 pt-6" for="salary">Expected Salary/Month</label>
            <input class="w-full" id="salary" type="text" placeholder="In USD">

            <label class="block text-black text-sm font-bold mb-2 pt-6" for="start">When Can You Start?</label>
            <input class="w-full" id="start" type="date">

            <label class="block text-grey-700 text-sm font-bold mb-2 pt-6" for="level">Highest Level Of Education</label>
            <label class="text-sm text-black pl-4"><input type="radio" name="education" value="High School Diploma/GED"> High School Diploma/GED</label>
            <label class="text-sm text-black pl-4"><input type="radio" name="education" value="Associates"> Associates</label>
            <label class="text-sm text-black pl-4"><input type="radio" name="education" value="Bachelors"> Bachelors</label>
            <label class="text-sm text-black pl-4"><input type="radio" name="education" value="Masters"> Masters</label>
            <label class="text-sm text-black pl-4"><input type="radio" name="education" value="Other/Trade"> Other/Trade</label>

            <label class="block text-black text-sm font-bold mb-2 pt-6" for="start">What are your skills?</label>
            <textarea class="w-full" id="skills" rows="3" placeholder="Tell us a little ablout yourself"></textarea>

            <div class="pt-6 text-center">

                <input class="bg-blue-500 hover:bg-blue-400 text-white font-bold py-2 px-4 border-b-4 border-blue-700 hover:border-blue-500 rounded" type="submit" value="Submit Your Application">

            </div>
            
        </form>
        

    </div>
</section>