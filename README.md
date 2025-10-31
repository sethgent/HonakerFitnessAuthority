index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Honaker Fitness Authority | Your Path to Strength</title>
    <!-- Load Tailwind CSS via CDN --><script src="https://cdn.tailwindcss.com"></script>
    <!-- Configure Tailwind to use Inter font and modern fitness-oriented colors (Black, White, Orange) --><style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap');
        body {
            font-family: 'Inter', sans-serif; /* FONT: Inter */
            background-color: #f8f8fb; /* Off-White Background */
            color: #1a1a2e; /* Dark Text */
            transition: background-color 0.3s;
        }
        /* Primary color is Orange (600) for high energy and impact */
        .primary-color {
            color: #ea580c; /* orange-600 */
        }
        .bg-primary {
            background-color: #ea580c; /* orange-600 */
        }
        .section-separator {
            content: '';
            display: block;
            width: 80px;
            height: 4px;
            background-color: #ea580c; /* orange-600 */
            margin: 16px auto 0;
            border-radius: 9999px;
        }
    </style>
</head>
<body class="min-h-screen antialiased">

    <!-- Header & Navigation (Darker) --><header class="sticky top-0 z-10 bg-gray-900 bg-opacity-95 backdrop-blur-sm shadow-xl">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8 py-4 flex justify-between items-center">
            <!-- Gym Name Only --><a href="#" class="flex items-center group">
                <span class="text-xl font-bold text-white group-hover:text-orange-600 transition duration-300">
                    Honaker Fitness Authority
                </span>
            </a>
            <!-- Updated Navigation Links Order --><nav class="space-x-4 text-gray-300 hidden md:flex text-sm lg:text-base">
                <a href="#" class="hover:text-orange-600 transition duration-150 font-medium whitespace-nowrap">Home</a>
                <a href="#pricing" class="hover:text-orange-600 transition duration-150 font-medium whitespace-nowrap">Contracts and Pricing</a>
                <a href="#equipment" class="hover:text-orange-600 transition duration-150 font-medium whitespace-nowrap">Equipment</a>
                <a href="#daypass" class="hover:text-orange-600 transition duration-150 font-medium whitespace-nowrap">Day Pass Program</a>
                <a href="#silversneakers" class="hover:text-orange-600 transition duration-150 font-medium whitespace-nowrap">Silver Sneakers Program</a>
                <a href="#how-to-join" class="hover:text-orange-600 transition duration-150 font-medium whitespace-nowrap">How to Join</a>
                <a href="#contact" class="hover:text-orange-600 transition duration-150 font-medium whitespace-nowrap">Contact Info</a>
            </nav>
            <!-- Mobile Menu Placeholder --><button class="md:hidden p-2 text-white hover:text-orange-600 rounded-lg transition duration-150 focus:outline-none">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="4" x2="20" y1="12" y2="12"/><line x1="4" x2="20" y1="6" y2="6"/><line x1="4" x2="20" y1="18" y2="18"/></svg>
            </button>
        </div>
    </header>

    <main class="container mx-auto max-w-6xl px-4 sm:px-6 lg:px-8">

        <!-- 1. Hero / Introduction Section (Home) --><section class="py-20 md:py-32 text-center">
            <h1 class="text-5xl md:text-6xl font-extrabold text-gray-900 mb-2">
                <!-- Heading in black --><span class="text-gray-900">Honaker Fitness Authority</span>
            </h1>
            <p class="text-3xl md:text-4xl font-extrabold primary-color mb-8">
                Open 24/7
            </p>
            <p class="text-xl text-gray-600 mb-8 font-light">
                <!-- Updated Tagline -->Tuff times don't last. Tuff people do.
            </p>
            <div class="flex justify-center space-x-4">
                <a href="#daypass" class="bg-orange-600 text-white font-semibold py-3 px-6 rounded-xl shadow-lg hover:bg-orange-700 transition duration-300 transform hover:scale-105">
                    Get a Day Pass (Only $5)
                </a>
                <a href="#pricing" class="border border-orange-600 text-orange-600 font-semibold py-3 px-6 rounded-xl shadow-md hover:bg-orange-50 transition duration-300 transform hover:scale-105">
                    View Contracts & Pricing
                </a>
            </div>
        </section>
        
        <!-- Supporting Section: Why Honaker Fitness Authority? (#about) --><section id="about" class="py-16">
            <h2 class="text-4xl font-bold text-center text-gray-900">Why Honaker Fitness Authority?</h2>
            <div class="section-separator"></div>
            <div class="mt-12 max-w-3xl mx-auto bg-white p-8 md:p-12 rounded-2xl shadow-xl">
                <p class="text-lg text-gray-700 leading-relaxed mb-6">
                    We are an all-inclusive communal environment where everyone is equally welcome. We offer a clean facility with a unique atmosphere of members willing to help when called upon. Our gym features 24/7 access for easy scheduling to fit your busy life.
                </p>
                <p class="text-lg text-gray-700 leading-relaxed">
                    Offering a multitude of contracts and options, let us help you decide what will work best for you and your fitness journey without any pressure. Push yourself to new limits—because fitness should fit your life, not the other way around.
                </p>
            </div>
        </section>

        <!-- 2. Contracts and Pricing Section (#pricing) --><section id="pricing" class="py-16 md:py-24 bg-gray-50 rounded-2xl">
            <h2 class="text-4xl font-bold text-center text-gray-900">Contracts and Pricing</h2>
            <div class="section-separator"></div>
            
            <div class="mt-8 max-w-4xl mx-auto grid grid-cols-1 md:grid-cols-2 gap-8">
                
                <!-- Pricing Card: Annual Contracts --><div class="bg-white p-8 rounded-xl shadow-2xl border-t-4 border-orange-600 text-center transition duration-300 transform scale-100 md:scale-[1.03]">
                    <h3 class="text-2xl font-bold text-gray-800 mb-6">Annual Contracts</h3>
                    <div class="overflow-x-auto">
                        <table class="min-w-full text-left text-gray-700 mb-6 border-collapse">
                            <thead>
                                <tr class="bg-orange-100 border-b border-orange-300">
                                    <th class="py-3 px-4 font-extrabold text-gray-900">Membership Type</th>
                                    <th class="py-3 px-4 font-extrabold text-gray-900 text-right">Rate Per Month</th>
                                </tr>
                            </thead>
                            <tbody>
                                <tr class="border-b">
                                    <td class="py-3 px-4">Single</td>
                                    <td class="py-3 px-4 font-bold text-right primary-color">$30</td>
                                </tr>
                                <tr class="border-b">
                                    <td class="py-3 px-4">Couples</td>
                                    <td class="py-3 px-4 font-bold text-right primary-color">$50</td>
                                </tr>
                                <tr class="border-b">
                                    <td class="py-3 px-4">Family of 3</td>
                                    <td class="py-3 px-4 font-bold text-right primary-color">$75</td>
                                </tr>
                                <tr>
                                    <td class="py-3 px-4">Family of 4</td>
                                    <td class="py-3 px-4 font-bold text-right primary-color">$90</td>
                                </tr>
                            </tbody>
                        </table>
                    </div>
                    <a href="#contact" class="bg-orange-600 text-white font-semibold py-3 px-6 rounded-lg w-full block hover:bg-orange-700 transition duration-300">Enroll in Annual Contract</a>
                </div>

                <!-- Pricing Card: 6 Month Contracts --><div class="bg-white p-8 rounded-xl shadow-xl border-t-4 border-gray-400 text-center transition duration-300 hover:shadow-2xl">
                    <h3 class="text-2xl font-bold text-gray-800 mb-6">6 Month Contracts</h3>
                    <div class="overflow-x-auto">
                        <table class="min-w-full text-left text-gray-700 mb-6 border-collapse">
                            <thead>
                                <tr class="bg-gray-100 border-b border-gray-300">
                                    <th class="py-3 px-4 font-extrabold text-gray-900">Membership Type</th>
                                    <th class="py-3 px-4 font-extrabold text-gray-900 text-right">Rate Per Month</th>
                                </tr>
                            </thead>
                            <tbody>
                                <tr class="border-b">
                                    <td class="py-3 px-4">Single</td>
                                    <td class="py-3 px-4 font-bold text-right primary-color">$40</td>
                                </tr>
                                <tr class="border-b">
                                    <td class="py-3 px-4">Couples</td>
                                    <td class="py-3 px-4 font-bold text-right primary-color">$60</td>
                                </tr>
                                <tr class="border-b">
                                    <td class="py-3 px-4">Family of 3</td>
                                    <td class="py-3 px-4 font-bold text-right primary-color">$75</td>
                                </tr>
                                <tr>
                                    <td class="py-3 px-4">Family of 4</td>
                                    <td class="py-3 px-4 font-bold text-right primary-color">$90</td>
                                </tr>
                            </tbody>
                        </table>
                    </div>
                    <a href="#contact" class="bg-gray-800 text-white font-semibold py-3 px-6 rounded-lg w-full block hover:bg-gray-700 transition duration-300">Choose 6 Month</a>
                </div>

            </div>
            
            <!-- Discount/Special Program Callouts --><div class="mt-12 text-center space-y-4 max-w-4xl mx-auto">
                <div class="bg-orange-100 p-6 rounded-xl shadow-md border border-orange-300">
                    <h4 class="text-2xl font-extrabold primary-color mb-2">Special Discounts Available!</h4>
                    <p class="text-gray-700 font-semibold mb-2">
                        Annual Student Contracts are available for $25/mo.
                    </p>
                    <p class="text-gray-600 text-sm">
                        Discounted memberships for Military, Police, Fire Dpt., EMT, Teachers, Students, Couples & Families. Contact us for details!
                    </p>
                </div>
            </div>
        </section>

        <!-- 3. Equipment Section (#equipment) --><section id="equipment" class="py-16 md:py-24">
            <h2 class="text-4xl font-bold text-center text-gray-900">Our Equipment & Facilities</h2>
            <div class="section-separator"></div>
            <div class="mt-12 max-w-xl mx-auto"> <!-- Narrowed container for cleaner list appearance -->
                <div class="bg-white p-8 md:p-12 rounded-2xl shadow-2xl border-t-4 border-orange-600">
                    <h3 class="text-2xl font-bold text-gray-800 mb-6 text-center">Equipment Highlights:</h3>
                    <ul class="space-y-3 text-xl text-gray-700 list-inside list-disc">
                        <li class="primary-color">
                            <span class="text-gray-900 font-semibold ml-2">Free Weights</span>
                        </li>
                        <li class="primary-color">
                            <span class="text-gray-900 font-semibold ml-2">Treadmills</span>
                        </li>
                        <li class="primary-color">
                            <span class="text-gray-900 font-semibold ml-2">Elliptical</span>
                        </li>
                        <li class="primary-color">
                            <span class="text-gray-900 font-semibold ml-2">Smith Machines</span>
                        </li>
                        <li class="primary-color">
                            <span class="text-gray-900 font-semibold ml-2">Isolation Machines</span>
                        </li>
                        <li class="primary-color">
                            <span class="text-orange-600 font-extrabold ml-2">...And More!</span>
                        </li>
                    </ul>
                    <p class="mt-8 text-center text-lg text-gray-600">
                        Everything you need to reach your strength and cardio goals, available 24/7.
                    </p>
                </div>
            </div>
        </section>

        <!-- 4. Day Pass Program (#daypass) --><section id="daypass" class="py-16 md:py-24 bg-orange-50 rounded-2xl mb-12">
            <h2 class="text-4xl font-bold text-center text-gray-900">$5 Day Passes</h2>
            <div class="section-separator"></div>
            <div class="mt-12 max-w-xl mx-auto text-center">
                <!-- Start new user-requested content block --><div class="bg-white p-8 rounded-2xl shadow-2xl border-t-4 border-orange-600">
                    <h3 class="text-3xl font-extrabold primary-color mb-4">Wanna come and try us out?</h3>
                    <p class="text-xl text-gray-700 mb-8 leading-relaxed font-medium">
                        We offer <span class="font-bold">$5 Day Passes</span> available to the public. 
                        We have <span class="font-bold">envelopes at the front door</span>. 
                        Just place your name and date on one with $5 inside the envelope and slide it into our red drop box and you're good to go for the day. 
                        <span class="font-bold">It's that easy!!</span>
                    </p>
                    <a href="#contact" class="bg-orange-600 text-white font-bold py-3 px-8 rounded-xl hover:bg-orange-700 transition duration-300 shadow-lg transform hover:scale-[1.01]">
                        Need More Info? Contact Us
                    </a>
                </div>
                <!-- End new user-requested content block -->
            </div>
        </section>

        <!-- 5. Silver Sneakers Program (#silversneakers) --><section id="silversneakers" class="py-16 md:py-24 bg-gray-900 text-white rounded-2xl">
            <h2 class="text-4xl font-bold text-center text-orange-600">Silver Sneakers Program</h2>
            <div class="section-separator bg-white"></div>
            <div class="mt-12 max-w-3xl mx-auto text-center">
                <p class="text-xl text-gray-300 mb-6 font-medium leading-relaxed">
                    We are a <strong>proud affiliate with Silver Sneakers</strong>, meaning that you could qualify for an <strong>absolutely free membership</strong>. Reach out to us today to see if you are eligible and start taking advantage of everything we have to offer at no cost to you. That's right, qualifying members are <strong>completely covered by insurance!</strong>
                </p>
                <div class="bg-orange-600 p-8 rounded-2xl inline-block shadow-lg">
                    <h3 class="text-2xl font-bold mb-4">Click the link below to see if you qualify and get your Silver Sneakers ID number!!</h3>
                    <a href="https://tools.silversneakers.com/Eligibility/CheckEligibility" target="_blank" class="inline-block bg-white text-gray-900 font-extrabold text-lg py-3 px-8 rounded-lg hover:bg-gray-100 transition duration-300 transform hover:scale-105 shadow-xl">
                        Check Your Eligibility Now!
                    </a>
                </div>
                <p class="text-sm text-gray-500 mt-6">
                    All you need to do is provide us with your 16 digit Silver Sneaker ID number.
                </p>
            </div>
        </section>

        <!-- 6. New Section: How to Join (#how-to-join) --><section id="how-to-join" class="py-16 md:py-24 bg-gray-900 text-white rounded-2xl mb-12">
            <h2 class="text-4xl font-bold text-center text-orange-600">How to Join Honaker Fitness Authority</h2>
            <div class="section-separator bg-white"></div>
            <p class="text-center text-xl text-gray-400 mt-6 mb-12">
                Follow these 6 simple steps to become a 24/7 member and start your fitness journey.
            </p>
            
            <!-- 6 Step Grid --><div class="mt-8 max-w-4xl mx-auto space-y-12">
                <!-- Step 1: Contact Us --><div class="flex items-start md:items-center space-x-6">
                    <div class="flex-shrink-0 w-12 h-12 bg-orange-600 text-white rounded-full flex items-center justify-center text-2xl font-extrabold shadow-xl">1</div>
                    <div class="flex-1 p-5 bg-white text-gray-800 rounded-xl shadow-lg border-l-4 border-orange-600">
                        <h3 class="text-2xl font-bold primary-color mb-2">Contact Us</h3>
                        <p>You can Message us on Facebook or Call or Text: (276) 971-2345.</p>
                    </div>
                </div>

                <!-- Step 2: Make an Appointment --><div class="flex items-start md:items-center space-x-6 md:justify-end">
                    <div class="flex-1 p-5 bg-white text-gray-800 rounded-xl shadow-lg border-r-4 border-orange-600 order-2 md:order-1">
                        <h3 class="text-2xl font-bold primary-color mb-2">Make an Appointment</h3>
                        <p>We'll work with you on setting up a time and date that works best for you.</p>
                    </div>
                    <div class="flex-shrink-0 w-12 h-12 bg-orange-600 text-white rounded-full flex items-center justify-center text-2xl font-extrabold shadow-xl order-1 md:order-2">2</div>
                </div>

                <!-- Step 3: Choose a Plan --><div class="flex items-start md:items-center space-x-6">
                    <div class="flex-shrink-0 w-12 h-12 bg-orange-600 text-white rounded-full flex items-center justify-center text-2xl font-extrabold shadow-xl">3</div>
                    <div class="flex-1 p-5 bg-white text-gray-800 rounded-xl shadow-lg border-l-4 border-orange-600">
                        <h3 class="text-2xl font-bold primary-color mb-2">Choose a Plan</h3>
                        <p>We'll help you determine which of our options work best for you, your goals, and your lifestyle.</p>
                    </div>
                </div>

                <!-- Step 4: Registration --><div class="flex items-start md:items-center space-x-6 md:justify-end">
                    <div class="flex-1 p-5 bg-white text-gray-800 rounded-xl shadow-lg border-r-4 border-orange-600 order-2 md:order-1">
                        <h3 class="text-2xl font-bold primary-color mb-2">Registration</h3>
                        <p>We'll create an online profile for you. We auto-draft. We require 2 forms of payment along with account and routing numbers.</p>
                    </div>
                    <div class="flex-shrink-0 w-12 h-12 bg-orange-600 text-white rounded-full flex items-center justify-center text-2xl font-extrabold shadow-xl order-1 md:order-2">4</div>
                </div>
                
                <!-- Step 5: Tour the Facility --><div class="flex items-start md:items-center space-x-6">
                    <div class="flex-shrink-0 w-12 h-12 bg-orange-600 text-white rounded-full flex items-center justify-center text-2xl font-extrabold shadow-xl">5</div>
                    <div class="flex-1 p-5 bg-white text-gray-800 rounded-xl shadow-lg border-l-4 border-orange-600">
                        <h3 class="text-2xl font-bold primary-color mb-2">Tour the Facility</h3>
                        <p>Once registration is complete, let us make things easier by showing you around and explaining the machines, equipment, and answering any questions you might have.</p>
                    </div>
                </div>
                
                <!-- Step 6: You're Now a Member! --><div class="flex items-start md:items-center space-x-6 md:justify-end">
                    <div class="flex-1 p-5 bg-white text-gray-800 rounded-xl shadow-lg border-r-4 border-orange-600 order-2 md:order-1">
                        <h3 class="text-2xl font-bold primary-color mb-2">You're Now a Member</h3>
                        <p>Start to enjoy increased physical & mental health along with more energy, mobility, and flexibility. There are no bad days in the gym.</p>
                    </div>
                    <div class="flex-shrink-0 w-12 h-12 bg-orange-600 text-white rounded-full flex items-center justify-center text-2xl font-extrabold shadow-xl order-1 md:order-2">6</div>
                </div>
                
                <div class="text-center pt-8">
                    <a href="#contact" class="bg-orange-600 text-white font-bold py-3 px-8 rounded-xl hover:bg-orange-700 transition duration-300 shadow-lg transform hover:scale-[1.01] text-xl">
                        Ready to Join? Contact Us Now!
                    </a>
                </div>
            </div>
        </section>

        <!-- 7. Contact Information (#contact) --><section id="contact" class="py-16 md:py-24 bg-gray-900 text-white rounded-2xl mb-12">
            <h2 class="text-4xl font-bold text-center text-orange-600">Contact & Enrollment</h2>
            <div class="section-separator bg-white"></div>
            <div class="mt-12 max-w-xl mx-auto">
                <p class="text-center text-xl text-gray-300 mb-8 font-semibold">
                    The road to nowhere is paved with excuses! Get in touch to start today.
                </p>
                
                <!-- Contact Info Card --><div class="bg-orange-600 p-8 rounded-2xl shadow-2xl text-center space-y-6">
                    <h3 class="text-3xl font-extrabold text-white">Message or Call Us</h3>
                    <!-- Facebook link updated with "Message us at" --><p class="text-2xl font-extrabold text-white">Message us at <a href="https://www.facebook.com/profile.php?id=100066918311022" target="_blank" class="underline hover:text-gray-900 transition duration-300">Honaker Fitness Authority</a></p>
                    <p class="text-2xl font-extrabold text-white">Or Call or Text:</p>
                    <!-- Phone Number is text-5xl (mobile) and sm:text-6xl (desktop) --><p class="text-5xl sm:text-6xl font-mono font-extrabold text-gray-900 leading-none tracking-wider">
                        <a href="tel:2769712345" class="hover:text-gray-100 transition duration-300">(276) 971-2345</a>
                    </p>
                </div>
                <!-- End Contact Info Card -->
            </div>
        </section>
        
    </main>
    
    <!-- Footer --><footer class="bg-gray-800 text-white py-8">
        <div class="container mx-auto max-w-6xl px-4 sm:px-6 lg:px-8 text-center">
            <p class="text-xl font-bold mb-4">Honaker Fitness Authority</p>
            <!-- Owner/Operator Information -->
            <p class="text-sm text-gray-400">Owner & Operator: Seth Gent</p>
            <p class="text-sm text-gray-400 mt-2">&copy; 2026. All rights reserved. | Honaker, VA</p>
        </div>
    </footer>

</body>
</html>
