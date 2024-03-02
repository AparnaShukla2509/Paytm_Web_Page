# Paytm_Web_Page
This Project is a clone of Paytm application, a Popular Digital Payment Platform that offers a wide range of services including mobile recharges, bill payments , ticket bookings and online shopping.

https://aparnashukla2509.github.io/Paytm_Web_Page/
<!DOCTYPE html>
<html lang="en">

<head>
    <link rel="stylesheet" href="style.css">
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Paytm: Secure & Fast UPI Payments, Recharge Mobile & Pay Bills Imagination & Delightful Creations</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.2/css/all.min.css"
    integrity="sha512-1sCRPdkRXhBV2PBLUdRb4tMg1w2YPf37qatUFeS7zlBy7jJI8Lf4VHwWfZZfpXtYSLy85pkm9GaYVYMfw5BC1A=="
    crossorigin="anonymous" referrerpolicy="no-referrer" />
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        bcg: '#1B98F5',
                        blue: '#120E43',
                        myblack: '#0D0D0D',
                        sky: '#12B0E8',
                        card:'#00baf2',
                        bcg_blue: '#0f4a8a',
                        background: '#CAD5E2',
                        lightgray:'#f5f7fa',
                    }
                }
            }
        }
    </script>
</head>

<body class="bg-gray-100 ">
    <header class=" flex bg-white h-20">
        
        <div class="container flex justify-between h-16 mx-auto">
            <a rel="noopener noreferrer" href="#" aria-label="Back to homepage" class="flex items-center p-2">
                <img class=" w-60" src="https://assetscdn1.paytm.com/images/catalog/category/5165/paytm_logo.png" alt="">
            </a>
            <ul class="items-stretch hidden space-x-3 lg:flex">
                <li class="flex decoration-none">
                    <a rel="noopener noreferrer" href="#" class="flex items-center px-4 -mb-1 text-black-900 
                font-bold dark:border-violet-400">Consumer Discover</a>
                </li>
                <li class="flex">
                    <a rel="noopener noreferrer" href="#" class="flex items-center px-4 -mb-1   text-black-900 
                font-bold">Business</a>
                </li>
                <li class="flex">
                    <a rel="noopener noreferrer" href="#" class="flex items-center px-4 -mb-1   text-black-900 
                font-bold">Company</a>
                </li>
                <li class="flex">
                    <a rel="noopener noreferrer" href="#" class="flex items-center px-4 -mb-1 text-black-900 
                font-bold">Investor Relation</a>
                </li>
                <li class="flex">
                    <a rel="noopener noreferrer" href="#" class="flex items-center px-4 -mb-1 text-black-900 
                font-bold">Career</a>
                </li>
            </ul>
            <div class="items-center flex-shrink-0 flex bg-sky rounded-full max-h-9 mt-4 hover:bg-blue ">
                <button class="self-center px-4 py-3 rounded text-white font-semibold">Sign in</button>
                <img src="https://assetscdn1.paytm.com/frontendcommonweb/9a65db05.svg" alt="">
            </div>

        </div>
    </header>
    <div class="flex justify-center items-center flex-end bg-gray-100 h-12 text-base taxt-black-900">
        <p class="font-bold">No Wallet KYC Required
            😊
            to pay using UPI on Paytm.Let your Imagination Soar ✨ and explore the realms of creativity.
            Learn more.</p>
    </div>
    <!-- hero section -->
    <section class="bg-white h-screen">
        <div class="container flex flex-col justify-center sm:py-12 lg:py-24 lg:flex-row lg:justify-between">
            <div
                class="flex flex-col justify-center p-6 text-center rounded-sm lg:max-w-md xl:max-w-lg lg:text-left lg:ml-36">
                <img class="w-24 m-auto lg:ml-4 mb-12" src="./assets/photo.png" alt="">
                <span class="font-bold text-black-900 sm:text-5xl text-4xl">India's Most-loved the Realms of <br>Payments App Paytm</span>
                <p class="text-xl mt-8 text-black-900 font-semibold ">Experience the enhancement - from making payements to booking flights,the possibilities are endless.Recharge & pay bills, book flights & movie
                    tickets, <br> open a savings account, invest in stocks & mutual <br> funds, and do a lot more.</p>
                <span class="flex m-auto lg:ml-0 mt-8 p-2 border-solid border-2 hover:border-myblack w-64 rounded-full text-white bg-black 
                    hover:bg-white hover:text-black justify-center">
                    <a class="ml-" href="#">Download Paytm App</a>
                    <div class="ml-2 m-1"> <span><i class="fa-brands fa-apple"></i></div>
                    <div class="ml-2 m-1"><span><i class="fa-brands fa-google-play"></i></span></div>
                </span>
            </div>
            <div class="flex items-center justify-between mt-8  h-72 sm:h-80 lg:h-96 xl:h-112 2xl:h-128">
                <img class="lg:max-w-xl mt-40 "
                    src="https://assetscdn1.paytm.com/images/catalog/view_item/850762/1656568118664.png" alt="">
            </div>
        </div>
    </section>

    <section class="bg-card lg:h-96 mt-72 sm:mt-0 lg:justify-center lg:items-center  ">
        <div class="flex justify-center sm:justify-start items-center flex-wrap ">
            <span
                class=" text-white font-semibold text-center text-3xl mb-8 sm:text-4xl sm:mx-24 mt-12 lg:ml-52">Recharge
                & Pay
                Bills on
                Paytm and unlock endless possibilities</span>
        </div>
        <!-- cards -->
        <div class="flex justify-center items-start  items-center sm:flex-row flex-wrap text-xl gap-5 ">
            <div
                class=" w-40 h-48 p-4 mr-8 rounded-lg hover:bg-bcg hover:cursor-pointer hover:max-w-xs p-6 rounded-xl shadow-xl bg-card">
                <img class="w-14 mb-4" src="https://paytm-clone-swadhin-dhara.netlify.app/assets/recharge.png" alt="">
                <p class="text-white font-semibold">Recharge<br>Prepaid<br>Mobile </p>
            </div>
            <!-- card 2 -->
            <div
                class=" w-40 h-48 p-4 mr-8 rounded-lg hover:bg-bcg hover:cursor-pointer hover:max-w-xs p-6 rounded-xl shadow-xl bg-card">
                <img class="w-14 mb-4" src="https://paytm-clone-swadhin-dhara.netlify.app/assets/rent.png" alt="">
                <p class="text-white font-semibold">Pay,<br>Rent <br>Payment </p>
            </div>
            <!-- card 3 -->
            <div
                class=" w-40 h-48 p-4 mr-8 rounded-lg hover:bg-bcg hover:cursor-pointer hover:max-w-xs p-6 rounded-xl shadow-xl bg-card">
                <img class="w-16 mb-4" src="https://paytm-clone-swadhin-dhara.netlify.app/assets/electricity.png" alt="">
                <p class="text-white font-semibold">Pay <br>Electricity <br>Bill
                </p>
            </div>
            <!-- card 4 -->
            <div
                class=" w-40 h-48 p-4 mr-8 rounded-lg hover:bg-bcg hover:cursor-pointer hover:max-w-xs p-6 rounded-xl shadow-xl bg-card">
                <img class="w-14 mb-4" src="https://paytm-clone-swadhin-dhara.netlify.app/assets/dth.png" alt="">
                <p class="text-white font-semibold">
                    Recharge <br> DTH <br>Conection
                </p>
            </div>
            <!-- card 5 -->
            <div
                class=" w-40 h-48 p-4 mr-8 rounded-lg hover:bg-bcg hover:cursor-pointer hover:max-w-xs p-6 rounded-xl shadow-xl bg-card">
                <img class="w-14 mb-4" src="https://paytm-clone-swadhin-dhara.netlify.app/assets/gas.png" alt="">
                <p class="text-white font-semibold">
                    Book <br>Gas <br>Cylinder
                </p>
            </div>
            <!-- card 6 -->
            <div
                class=" w-40 h-48 p-4 mr-8 rounded-lg hover:bg-bcg hover:cursor-pointer hover:max-w-xs p-6 rounded-xl shadow-xl bg-card">
                <img class="w-14 mb-4" src="https://paytm-clone-swadhin-dhara.netlify.app/assets/credit_card.png" alt="">
                <p class="text-white font-semibold">
                    Pay <br>Credit <br>Card bill
                </p>
            </div>
            
        </div>
    </section>
    <section class="bg-bcg_blue lg:h-80 lg:justify-center lg:items-center  ">
        <div class="flex justify-center sm:justify-start items-center flex-wrap ">
            <span class=" text-white font-semibold text-center text-3xl mb-8 sm:text-4xl sm:mx-24 mt-12 lg:ml-52">Book &
                Buy on
                Paytm.</span>
        </div>
        <!-- cards -->
        <div class="flex justify-center items-start items-center sm:flex-row flex-wrap text-xl gap-5">
            <div
                class="w-40 h-40 p-4 mr-8 rounded-lg hover:bg-blue hover:cursor-pointer hover:max-w-xs p-6 rounded-xl shadow-xl bg-bcg_blue">
                <img class="w-14 mb-4" src="https://assetscdn1.paytm.com/images/catalog/view_item/733295/1626259710574.png" alt="">
                <p class="text-white font-semibold">Movie<br>Tickets</p>
            </div>
            <div
                class="w-40 h-40 p-4 mr-8 rounded-lg hover:bg-blue hover:cursor-pointer hover:max-w-xs p-6 rounded-xl shadow-xl bg-bcg_blue">
                <img class="w-14 mb-4" src="https://assetscdn1.paytm.com/images/catalog/view_item/733296/1626259884425.png" alt="">
                <p class="text-white font-semibold">Flight<br>Tickets</p>
            </div>
            <div
                class="w-40 h-40 p-4 mr-8 rounded-lg hover:bg-blue hover:cursor-pointer hover:max-w-xs p-6 rounded-xl shadow-xl bg-bcg_blue">
                <img class="w-14 mb-4" src="https://assetscdn1.paytm.com/images/catalog/view_item/729996/1626260477699.png" alt="">
                <p class="text-white font-semibold">Bus<br>Tickets</p>
            </div>
            <div
                class="w-40 h-40 p-4 mr-8 rounded-lg hover:bg-blue hover:cursor-pointer hover:max-w-xs p-6 rounded-xl shadow-xl bg-bcg_blue">
                <img class="w-14 mb-4" src="https://assetscdn1.paytm.com/images/catalog/view_item/729997/1626260495975.png" alt="">
                <p class="text-white font-semibold">Train<br>Tickets</p>
            </div>
            <div
                class="w-40 h-40 p-4 mr-8 rounded-lg hover:bg-blue hover:cursor-pointer hover:max-w-xs p-6 rounded-xl shadow-xl bg-bcg_blue">
                <img class="w-14 mb-4" src="https://assetscdn1.paytm.com/images/catalog/view_item/729998/1626259953707.png" alt="">
                <p class="text-white font-semibold">Car &<br>Bikes</p>
            </div>
            <div
                class="w-40 h-40 p-4 mr-8 rounded-lg hover:bg-blue hover:cursor-pointer hover:max-w-xs p-6 rounded-xl shadow-xl bg-bcg_blue">
                <img class="w-14 mb-4" src="https://assetscdn1.paytm.com/images/catalog/view_item/729999/1626259968563.png" alt="">
                <p class="text-white font-semibold">international<br>Flights</p>
            </div>
            
        </div>
    </section>

    <section class="">
        <div>
            <h1 class=" font-bold text-5xl text-center lg:text-left lg:ml-32 mt-16 lg:mt-32 mb-12">Paytm Payment
                Instruments</h1>
        </div>
        <div class="lg:w-5/6 bg-white m-auto flex justify-around rounded-xl flex-col sm:flex-row items-center ">
            <div class="flex flex-col items-center lg:items-start sm:ml-24">
                <div class="flex lg:mt-3 mt-3 ">
                    <img class=" w-24 h-24" src="https://assetscdn1.paytm.com/images/catalog/view/307185/1617861564011.png" alt="">
                    <div>
                        <h3 class=" font-semibold ml-4 mt-4 text-lg">Paytm <br>Wallet</h3>
                    </div>
                </div>
                <div class="ml-4">
                    <div>
                        <h1 class=" font-bold text-4xl mt-10 sm:text-left text-center">The Fastest Way to <br> Pay
                            In-store & Online.</h1>
                    </div>
                    <div>
                        <p class=" mt-12 font-semibold text-lg sm:text-left text-center">Load up your Paytm Wallet for
                            free and make payments <br> in a jiffy at over 21 million
                            stores, websites and apps.</p>
                    </div>
                    <span class="flex m-auto lg:ml-0 mt-8 p-2 border-solid border-2 hover:border-myblack w-64 rounded-full text-white bg-black 
                    hover:bg-white hover:text-black justify-center">
                    <a class="ml-" href="#">Download Paytm App</a>
                    <div class="ml-2 m-1"> <span><i class="fa-brands fa-apple"></i></div>
                        <div class="ml-2 m-1"><span><i class="fa-brands fa-google-play"></i></span></div>
                </span>
                </div>
            </div>
            <div>
                <img class="sm:max-w-xl mt-20 mb-16" src="https://assetscdn1.paytm.com/images/catalog/view_item/728701/1618577020961.png" alt="">
            </div>
        </div>
    </section>

    <section class=" mt-16">

        <div class="w-5/6 bg-white m-auto flex justify-around rounded-xl flex-col sm:flex-row items-center ">
            <div class="flex flex-col items-center sm:items-start sm:ml-24">
                <div class="flex sm:mt-3 mt-32 ">
                    <img class=" w-20 h-20" src="https://assetscdn1.paytm.com/images/catalog/view/307186/1615957674521.png" alt="">
                    <div>
                        <h3 class=" font-semibold ml-4 mt-4 text-lg">UPI Money<br>Transfer</h3>
                    </div>
                </div>
                <div>
                    <div>
                        <h1 class=" font-bold text-4xl mt-12 sm:text-left text-center">Pay anyone directly <br> from
                            your bank <br> account.</h1>
                    </div>
                    <div>
                        <p class=" mt-12 font-semibold text-lg sm:text-left text-center">Pay anyone, everywhere. Make
                            contactless & secure <br> payments in-stores or online using Paytm Wallet or <br> Directly
                            from your Bank Account. Plus, send & receive <br> money from anyone.</p>
                    </div>
                    <span class="flex m-auto lg:ml-0 mt-8 p-2 border-solid border-2 hover:border-myblack w-64 rounded-full text-white bg-black 
                    hover:bg-white hover:text-black justify-center">
                    <a class="ml-" href="#">Download Paytm App</a>
                    <div class="ml-2 m-1"> <span><i class="fa-brands fa-apple"></i></div>
                        <div class="ml-2 m-1"><span><i class="fa-brands fa-google-play"></i></span></div>
                </span>
                </div>
            </div>
            <div>
                <img class="sm:max-w-xl mt-20 mb-16" src="https://assetscdn1.paytm.com/images/catalog/view_item/728702/1626342071104.png" alt="">
            </div>
        </div>
    </section>



    <section class=" mt-16">

        <div class="w-5/6 bg-white m-auto flex justify-around rounded-xl flex-col sm:flex-row items-center ">
            <div class="flex flex-col items-center sm:items-start sm:ml-24">
                <div class="flex sm:mt-3 mt-32 ">
                    <img class="h-20" src="https://assetscdn1.paytm.com/images/catalog/view/307191/1613622537678.png" alt="">
                </div>
                <div>
                    <div>
                        <h1 class=" font-bold text-4xl mt-12 sm:text-left text-center">Want it? <br>
                            No more waiting for it.</h1>
                    </div>
                    <div>
                        <p class=" mt-12 font-semibold text-lg sm:text-left text-center">With Paytm Postpaid, your
                            wishlist doesn't have to be <br>
                            on the waitlist. Shop for the things you want today and <br> pay for them next month.</p>
                    </div>
                    <span
                        class="flex m-auto lg:ml-0 mt-8 p-4 hover:border-myblack w-44 rounded-full text-white bg-bcg_blue hover:bg-sky hover:text-white justify-center ">
                        <a class="ml-2" href="#">Learn More ></a>
                    </span>
                </div>
            </div>
            <div>
                <img class="sm:max-w-lg mt-20 mb-16" src="https://assetscdn1.paytm.com/images/catalog/view_item/850764/1626077030984.png" alt="">
            </div>
        </div>
    </section>


    <section class=" mt-16 ">

        <div class="w-5/6  m-auto flex justify-between rounded-xl flex-col sm:flex-row items-center ">
            <div class="left bg-white rounded-lg   flex flex-col items-center">
                <div class="content lg:mt-16 mt-8">
                    <div>
                        <img class=" w-64 lg:ml-12 m-auto " src="https://assetscdn1.paytm.com/images/catalog/view_item/853975/1640242865113.png" alt="">
                    </div>
                    <div class="lg:ml-12 m-12 text-center lg:text-left ">
                        <h1 class=" text-2xl lg:text-5xl font-bold mt-16 mb-8 ">Unlimited Cashback <br>Every time</h1>
                        <span class=" font-semibold text-xl ">Paytm HDFC Bank Select Credit Card. A card <br> with
                            assured Cashback and incredible offers<span>
                    </div>
                </div>
                <div class="image  ml-16 ">
                    <img class="lg:max-w-md max-w-xs" src="https://assetscdn1.paytm.com/images/catalog/view_item/853975/1640241561388.png" alt="">
                </div>
            </div>

            <div class="right bg-white rounded-lg lg:pl-16 lg:pr-16 lg:mt-2 mt-12">
                <div class="content mt-36">
                    <div>
                        <img class=" w-64 m-auto lg:m-0 " src="https://assetscdn1.paytm.com/images/catalog/view_item/853976/1640242163727.png" alt="">
                    </div>
                    <div class="lg:text-left text-center">
                        <h1 class="text-3xl  lg:text-5xl font-bold mt-16 mb-8 ">India's Most <br>Sincere Credit Card
                        </h1>
                        <span class=" font-semibold text-xl ">Paytm SBI Card Select - With Intelligent <br> Features &
                            Great Reward that Never Expire<span>
                    </div>
                </div>
                <div class="image mt-16  ml-4 ">
                    <img class="lg:max-w-md max-w-xs" src="https://assetscdn1.paytm.com/images/catalog/view_item/853976/1626079147084.png" alt="">
                </div>
            </div>

        </div>
    </section>


    <section class="bg-white w-full rounded-lg mt-16 h-fit">
        <div class="container flex justify-around lg:flex-row flex-col items-center">
            <div class="left lg:ml-16">
                <div class="heading mt-16 text-center">
                    <h1 class=" text-5xl lg:text-6xl font-bold  ">Financial Services by Paytm</h1>
                </div>
                <div class="image mt-16">
                    <img class="w-64 m-auto lg:m-0 " src="https://assetscdn1.paytm.com/images/catalog/view/307193/1617696576778.png" alt="">
                </div>
                <div class="content mt-16 text-center lg:text-left">
                    <h1 class=" font-bold text-5xl mb-8">India's most sincere <br> bank.</h1>
                    <span class=" lg:text-xl  font-semibold ">Paytm Payments Bank offers secure, transparent and <br>
                        risk-free banking at your fingertips. With instant <br> account opening, virtual debit card and
                        zero balance <br> requirements, experience the future of banking today.</span>
                    <span
                        class="flex m-auto lg:ml-0 mt-12 p-8 hover:border-myblack w-44 lg:w-52 rounded-lg text-white bg-bcg_blue hover:bg-sky hover:text-white justify-center lg:mb-24">
                        <a class="ml-2 lg:text-xl" href="#">Learn More ></a>
                    </span>
                </div>
            </div>
            <div class="right lg:mt-44 mt-20">
                <img class="lg:max-w-lg max-w-md" src="https://assetscdn1.paytm.com/images/catalog/view_item/728826/1626076427497.png" alt="">
            </div>
        </div>
    </section>

    <section class=" w-full rounded-lg mt-16">
        <div class="container flex justify-around lg:flex-row flex-col items-center">
            <div class="left mt-16 lg:ml-24">
                <img class="lg:max-w-lg max-w-md" src="https://assetscdn1.paytm.com/images/catalog/view_item/788781/1626077377376.png" alt="">
            </div>
            <div class="right lg:mr-24 ">
                <div class="image mt-12 ">
                    <img class="w-44 m-auto lg:m-0 " src="https://assetscdn1.paytm.com/images/catalog/view/308774/1617696247991.png" alt="">
                </div>
                <div class="content text-center lg:text-left mt-12">
                    <h1 class=" font-bold lg:text-5xl text-3xl mb-8 m-auto">Build Long-term <br> Wealth & Achieve <br>
                        your Goals.</h1>
                    <span class="font-semibold lg:text-xl ">Investing on Paytm Money is transparent, low-cost and <br>
                        commission-free. Buy stocks & mutual funds that can <br> help you create wealth & realise your
                        dreams.</span>
                    <span
                        class="flex m-auto lg:ml-0 mt-12 p-4 hover:border-myblack w-44 rounded-full text-white bg-bcg_blue hover:bg-sky hover:text-white justify-center">
                        <a class="ml-2" href="#">Learn More ></a>
                    </span>

                </div>
            </div>
        </div>
    </section>


    <section class="bg-white w-full rounded-lg mt-16 h-fit">
        <div class="container flex justify-around lg:flex-row flex-col items-center">
            <div class="right lg:mr-24 ">
                <div class="image mt-24 ">
                    <img class="w-44 m-auto lg:m-0 lg:ml-24" src="https://assetscdn1.paytm.com/images/catalog/view/308775/1653901470333.jpeg" alt="">
                </div>
                <div class="content text-center lg:text-left mt-12 lg:ml-24">
                    <h1 class=" font-bold lg:text-5xl text-3xl mb-8 m-auto">Insurance made easy.</h1>
                    <span class="font-semibold lg:text-xl ">Buying insurance does not have to be tedious, time-consuming
                        <br> & confusing. Paytm Insurance removes the <br> worry of getting insured by making it
                        simple,<br> convenient & easy-to-understand.</span>
                    <span
                        class="flex m-auto lg:ml-0 mt-12 p-4 hover:border-myblack w-44 rounded-full text-white bg-bcg_blue hover:bg-sky hover:text-white justify-center">
                        <a class="ml-2" href="#">Learn More ></a>
                    </span>

                </div>
            </div>
            <div class="left mt-24 lg:mr-24 mb-24">
                <img class="lg:max-w-lg max-w-md" src="https://assetscdn1.paytm.com/images/catalog/view_item/788790/1653913927257.png" alt="">
            </div>
        </div>

        <div class="container flex justify-around lg:flex-row flex-col items-center bg-lightgray">

            <div class="right mt-24 mb-24 mx-24">
                <img class="lg:max-w-lg max-w-md" src="https://assetscdn1.paytm.com/images/catalog/view_item/850765/1655987252365.png" alt="">
            </div>

            <div class="left lg:mr-24 ">
                <div class="image mt-24 ">
                    <img class="w-44 m-auto lg:m-0 lg:ml-24" src="https://assetscdn1.paytm.com/images/catalog/view/308777/1617695287770.png" alt="">
                </div>
                <div class="content text-center lg:text-left mt-12 lg:ml-24">
                    <h1 class=" font-bold lg:text-5xl text-3xl mb-8 m-auto">Get a Personal Loan in <br> 2 Minutes.</h1>
                    <span class="font-semibold lg:text-xl ">Paytm offers India's quickest multi-purpose, hassle-free loan. It <br> is 100% digital, transparent and paperless.</span>
                    <span
                        class="flex m-auto lg:ml-0 mt-12 p-4 hover:border-myblack w-44 rounded-full text-white bg-bcg_blue hover:bg-sky hover:text-white justify-center">
                        <a class="ml-2" href="#">Learn More ></a>
                    </span>

                </div>
            </div>
            
        </div>


    </section>


    <section class="bg-white w-full flex flex-col gap-10">
        <div class="w-5/6 m-auto font-bold lg:text-5xl text-3xl mb-16 text-center lg:text-left my-36">
            <h1 class="">
                Business Services by Paytm
            </h1>
        </div>
        <div class="top">
            <div
                class="main-container bg-[#f5f7fa] rounded-lg w-5/6 m-auto w-5/6 flex justify-between lg:flex-row flex-col items-center ">
                <div class="left">
                    <div class="content lg:pl-32  lg:mt-32 mt-12 text-center lg:text-left">
                        <h1 class=" font-bold text-5xl mb-12 ">Accept payments <br> online with ease</h1>
                        <span class="font-semibold ">Grow your business with the payment gateway that <br> powers
                            India’s largest brands and
                            even the Paytm App</span>
                        <span
                            class="flex m-auto lg:ml-0 mt-12 p-4 hover:border-myblack w-44 rounded-full text-white bg-bcg_blue hover:bg-sky hover:text-white justify-center">
                            <a class="ml-2" href="#">Learn More ></a>
                        </span>
                    </div>
                </div>
                <div class="right ">
                    <img class="lg:max-w-lg max-w-xs lg:mt-32 mt-16 mb-12" src="https://assetscdn1.paytm.com/images/catalog/view_item/853877/1626077000254.png" alt="">
                </div>
            </div>
        </div>
        <div class="bottom">
            <div
                class="main-container bg-[#f5f7fa] rounded-lg w-5/6 m-auto w-5/6 flex justify-between lg:flex-row flex-col items-center ">
                <div class="left">
                    <div class="content lg:pl-32 mt-12 text-center lg:text-left">
                        <h1 class=" font-bold text-5xl mb-12 ">In-shop payments <br> powered by Paytm.</h1>
                        <span class="font-semibold ">Millions of small & big businesses use Paytm to accept <br>
                            payments anywhere any time with a wide range of <br> solutions for all kind of
                            merchants</span>
                        <span
                            class="flex m-auto lg:ml-0 mt-12 p-4 hover:border-myblack w-44 rounded-full text-white bg-bcg_blue hover:bg-sky hover:text-white justify-center">
                            <a class="ml-2" href="#">Learn More ></a>
                        </span>
                    </div>
                </div>
                <div class="right ">
                    <img class="lg:max-w-xl max-w-xs lg:ml-0 mt-16 mb-12 " src="https://assetscdn1.paytm.com/images/catalog/view_item/853880/1656675942486.png" alt="">
                </div>
            </div>
        </div>
    </section>


    <section class="bg-white w-full">
        <div class="container flex flex-col gap-20 w-5/6 m-auto">
            <div class="heading font-bold lg:text-5xl text-3xl mt-16 text-center lg:text-left">
                <h1>Business Tools to help <br> your business grow</h1>
            </div>
            <div class="cards flex flex-wrap items-start items-center justify-center gap-10 ">
                <div
                    class="flex flex-col items-center justify-center  mb-32">
                    <img class=" w-52 ml-8" src="https://assetscdn1.paytm.com/images/catalog/view_item/854033/1626081565192.png" alt="">
                    <h2 class=" font-bold text-2xl text-center mt-8 ">POS Billing <br> Software</h2>
                    <p class="font-semibold mt-8 mb-4 text-center">Say Hello to Smart Retail <br> Business Management
                    </p>
                    <span class="font-bold hover:text-sky"><a href="#">Learn More</a></span>
                </div>
                <div
                    class="flex flex-col items-center justify-center  mb-32">
                    <img class=" w-52 ml-8" src="https://assetscdn1.paytm.com/images/catalog/view_item/854035/1626081071077.png" alt="">
                    <h2 class=" font-bold text-2xl text-center mt-8">Paytm for <br> Business App</h2>
                    <p class="font-semibold mt-4 mb-4 text-center">Everything you need to <br> manage your business <br>
                        on your phone</p>
                    <span class="font-bold hover:text-sky"><a href="#">Learn More</a></span>
                </div>
                <div
                    class="flex flex-col items-center justify-center  mb-32">
                    <img class=" w-52 ml-8" src="https://assetscdn1.paytm.com/images/catalog/view_item/854036/1656568216166.png" alt="">
                    <h2 class=" font-bold text-2xl text-center mt-8">Advertise on <br>
                        Paytm</h2>
                    <p class="font-semibold mt-4 mb-4 text-center">Grow your business by <br> advertising on India's
                        <br> largest mobile business</p>
                    <span class="font-bold hover:text-sky"><a href="#">Learn More</a></span>
                </div>
                <div
                    class="flex flex-col items-center justify-center  mb-32">
                    <img class=" w-52 ml-12" src="https://assetscdn1.paytm.com/images/catalog/view_item/854038/1626081814411.png" alt="">
                    <h2 class=" font-bold text-2xl text-center mt-8">Business <br>
                        Khata</h2>
                    <p class="font-semibold mt-8 mb-4 text-center">Managing Khata made <br> easy</p>
                    <span class="font-bold hover:text-sky"><a href="#">Learn More</a></span>
                </div>
            </div>
        </div>
    </section>

    <section class="bg-[#f0fbff] w-full flex flex-col gap-20">
        <div class="top bg-white w-5/6 m-auto mt-20 rounded-lg">
            <div class="cards flex flex-col lg:flex-row items-center justify-center flex-wrap gap-20 p-12">
                <div class="text-center lg:text-left">
                    <img class="w-36 m-auto lg:m-0" src="https://assetscdn1.paytm.com/images/catalog/view/307196/1626420555412.png" alt="">
                    <p class="mt-12 font-semibold mb-4">Get started on wealth <br> creation journey with Zero <br>
                        brokerage fee & no hidden charges.</p>
                    <span class="text-sky font-semibold hover:text-blue"><a href="#">Learn More</a></span>
                </div>
                <div class="card bg-sky p-2 rounded-md max-w-xs shadow-xl bg-[#66d6ff] h-52">
                    <img class="w-32" src="https://assetscdn1.paytm.com/images/catalog/view_item/728894/1618576143299.png" alt="">
                    <p class="font-bold text-center text-white">Invest in <br>Stocks</p>
                </div>
                <div class="card bg-sky p-2 rounded-md max-w-xs shadow-xl bg-[#66d6ff] h-52">
                    <img class="w-32" src="https://assetscdn1.paytm.com/images/catalog/view_item/728895/1618575899205.png" alt="">
                    <p class="font-bold text-center text-white">Apply for IPO</p>
                </div>
                <div class="card bg-sky p-2 rounded-md max-w-xs shadow-xl bg-[#66d6ff] h-52">
                    <img class="w-32" src="https://assetscdn1.paytm.com/images/catalog/view_item/800760/1618831809222.png" alt="">
                    <p class="font-bold text-center text-white">Invest in <b>ETFs</b></p>
                </div>
                <div class="card bg-sky p-2 rounded-md max-w-xs shadow-xl bg-[#66d6ff] h-52">
                    <img class="w-32" src="https://assetscdn1.paytm.com/images/catalog/view_item/728896/1618575990183.png" alt="">
                    <p class="font-bold text-center text-white">Buy Gold</b></p>
                </div>
            </div>
        </div>
        <div class="bottom bg-white w-5/6 m-auto rounded-lg mb-36">
            <div class="cards flex flex-col lg:flex-row items-center justify-center flex-wrap gap-10 p-12">
                <div class="lg:mr-24 m-auto text-center lg:text-left">
                    <img class="w-44 ml-16 lg:ml-0 lg:m-0" src="https://assetscdn1.paytm.com/images/catalog/view/307197/1626419838546.png" alt="">
                    <p class="mt-12 font-semibold mb-4 ">Best travel solutions with <br> quick ticket bookings, great
                        <br> offers and easy refunds</p>
                    <span class="text-sky font-semibold hover:text-blue"><a href="#">Learn More</a></span>
                </div>
                <div
                    class="card bg-sky p-6 rounded-md max-w-xs shadow-xl bg-[#66d6ff] h-52 text-white font-bold">
                    <img class="w-16 m-auto" src="https://assetscdn1.paytm.com/images/catalog/view_item/863734/1627552693557.png" alt="">
                    <h2 class=" text-lg  text-center mt-4">Flat 14% <br>Cashback</h2>
                    <p class="text-sm text-center ">with Code <br> WELCOMEFLIGHT</p>
                </div>
                <div
                    class="card bg-sky p-2 rounded-md max-w-xs shadow-xl bg-[#66d6ff] h-52 text-white font-bold">
                    <img class="w-16 m-auto" src="https://assetscdn1.paytm.com/images/catalog/view_item/864144/1627566096011.png" alt="">
                    <h2 class=" text-lg  text-center mt-4">100% Refund</h2>
                    <p class="text-sm text-center ">With Paytms's <br>Cancellation Protect</p>
                </div>
                <div
                    class="card bg-sky p-2 rounded-md max-w-xs shadow-xl bg-[#66d6ff] h-52 text-white font-bold">
                    <img class="w-16 m-auto" src="https://assetscdn1.paytm.com/images/catalog/view_item/864145/1627566172335.png" alt="">
                    <h2 class=" text-lg  text-center mt-4">Flat 100% <br>Cashback</h2>
                    <p class="text-sm text-center ">With Code HAPPYBUS</p>
                </div>
                <div
                    class="card bg-sky p-6 rounded-md max-w-xs shadow-xl bg-[#66d6ff] h-52 text-white font-bold">
                    <img class="w-16 m-auto" src="https://assetscdn1.paytm.com/images/catalog/view_item/864151/1627567062180.png" alt="">
                    <h2 class=" text-lg  text-center mt-4">Sanitised Bus <br>Options With <br>TravelSafe+</h2>
                </div>
            </div>
        </div>

    </section>
    <footer class="flex justify-around bg-white lg:flex-row flex-col items-center">
        <div class="left flex gap-5 mt-20 lg:mb-20 flex-col items-center lg:flex-row">
            <div>
                <p class="font-bold text-2xl lg:mb-0 mb-12">Download Paytm App <br> to Pay from anywhere</p>
            </div>
            <div class="flex gap-5 flex-col lg:flex-row">
                <img class="w-44" src="https://assetscdn1.paytm.com/frontendcommonweb/71229188.svg" alt="">
                <img class="w-44" src="https://assetscdn1.paytm.com/frontendcommonweb/33d9d7f1.svg" alt="">
            </div>
        </div>
        <div class="right flex gap-5 mt-20 mb-20 ">
            <div class="w-12"><img src="https://assetscdn1.paytm.com/frontendcommonweb/508b83d1.svg" alt="" srcset=""></div>
            <div class="w-12"><img src="https://assetscdn1.paytm.com/frontendcommonweb/f9c15a7a.svg" alt="" srcset=""></div>
            <div class="w-12"><img src="https://assetscdn1.paytm.com/frontendcommonweb/ad9d15ee.svg" alt=""></div>
            <div class="card">
        </div>
    </footer>
    <script src="script.js"></script>
</body>

</html>
Tap here for a quick preview on my project
