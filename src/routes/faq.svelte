<link rel="stylesheet" href="https://demos.creative-tim.com/notus-js/assets/styles/tailwind.css">
<link rel="stylesheet" href="https://demos.creative-tim.com/notus-js/assets/vendor/@fortawesome/fontawesome-free/css/all.min.css">

<style>

    .bigvid {
    filter: brightness(50%);
    }

    #faq {
        display: none;
    }

    @media screen and (min-width: 1280px) {

        .cent {
        position: absolute;
        top: 23%;
        left: 50%;
        transform: translate(-50%, -50%);
        font-size: 60px;
        }

        #faq {
        display: inline-block;
        }

        .question {
            font-size: 35px;
        }

        .answer {
            font-size: 25px;
        }

        .box{
            border: 5px solid black;
            background: lightblue;
    }

    }

    @media screen and (min-width:640px) and (max-width:1280px) {

        .cent {
        position: absolute;
        top: 15%;
        left: 50%;
        transform: translate(-50%, -50%);
        font-size: 45px;
        }

        #faq {
        display: inline-block;
        }

        .question {
            font-size: 30px;
        }

        .answer {
            font-size: 22px;
        }

        .box{
            border: 5px solid black;
            background: lightblue;
    }

    }

    @media screen and (max-width: 640px) {
        
        .cent {
        position: absolute;
        top: 19%;
        left: 50%;
        transform: translate(-50%, -50%);
        font-size: 37px;
        }

        #faq {
            display: inline-block;
        }

        .question {
            font-size: 25px;
        }

        .box{
            background: lightblue;
    }

    }

</style>

<section class="relative bg-yellow-200 font-sans">

    <div class="mx-auto">
        <video class="bigvid mx-auto border-t-4 border-b-4 border-blue-500 object-cover h-52 lg:h-80 w-full" style="width:100%" muted autoplay loop>
        <source src="../../video/landing.webm" type="video/webm" />
        </video>
        
        <div class="cent container mx-auto text-center" id="faq">
            
            <div class="pb-40 text-white font-bold">
                <p class="font-bold tracking-wider" style="text-shadow:black 0px 0px 10px;">Frequently Asked Questions</p>
            </div>

        </div>
    </div>

    <div class="sm:p-2 md:p-4">
        <div class="box container mx-auto text-center">
            <p class="question font-bold p-4">“What is the difference between a home inspection and an appraisal?"</p>

            <p class="answer max-w-6xl mx-auto p-2">Usually the confusion starts with the the fact they both are needed prior to closing. The difference between these two is the simple fact that one determines the value of a home for your mortgage lender while the other determines the condition of a home for your benefit.
            <br>
            <br>
            An appraisal is conducted by a licensed appraiser, meaning not just anyone can perform such duties, and although the job functions between these two are similar in timing, home inspectors provide the buyer with knowledge to make an informed decision before closing.  The inspection report will provide conditions of the home- real problems and solutions without opinion or bias.
            </p>
        </div>
    </div>


    <div class="sm:p-2 md:p-4">
        <div class="box container mx-auto text-center">
        <p class="question font-bold p-2">“Do I need to get a home inspection?"</p>

        <p class="answer p-4 max-w-6xl mx-auto">There is no law that requires a buyer or a seller to conduct an inspection when purchasing or selling any home. However, getting a home inspection can uncover potentially hazardous issues that may become a problem in the future. Usually people wont notice little things with a quick look around but a home inspection will be able to provide you with a thorough review of your home. Basically, better to be safe than sorry.
        </p>
        </div>
    </div>
    

</section>