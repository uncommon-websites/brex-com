<script>
    import { onMount } from 'svelte';
</script>

<main class="font-body text-[#111827]">
    <!-- Hero Section -->
    <section class="relative bg-[#F3F3F1] pt-32 pb-20 lg:pt-48 lg:pb-32 overflow-hidden">
        <div class="max-w-[1440px] mx-auto px-6 lg:px-12 grid lg:grid-cols-2 gap-12 items-center">
            <div class="max-w-xl relative z-10">
                <h1 class="text-5xl lg:text-[64px] leading-[1.1] font-bold tracking-tight mb-6">
                    Finance built for<br>speed and control.
                </h1>
                <p class="text-xl text-gray-600 mb-10 leading-relaxed max-w-md">
                    Modern cards, banking, expenses, accounting, and more — in 120+ countries.
                </p>
                
                <div class="flex flex-col sm:flex-row gap-4 mb-8 max-w-md">
                    <input type="email" placeholder="Enter your work email" class="flex-1 px-4 py-3 rounded-md border border-gray-300 focus:outline-none focus:ring-2 focus:ring-[#F45D22] focus:border-transparent" />
                    <button class="bg-[#F45D22] hover:bg-[#E04F1A] text-white px-6 py-3 rounded-md font-semibold transition-colors whitespace-nowrap">
                        Get started
                    </button>
                </div>

                <a href="#" class="inline-flex items-center gap-2 text-[#F45D22] font-medium hover:underline">
                    <svg class="w-5 h-5 border border-[#F45D22] rounded-full p-1" viewBox="0 0 24 24" fill="currentColor">
                        <path d="M8 5v14l11-7z" />
                    </svg>
                    See Brex in action
                </a>

                <p class="mt-20 text-[11px] text-gray-500 max-w-xs leading-snug">
                    Brex is a financial technology company, not a bank. Checking and banking services provided by Column N.A., Member FDIC.
                </p>
            </div>

            <div class="relative lg:absolute lg:right-0 lg:top-0 lg:bottom-0 lg:w-1/2 overflow-hidden pointer-events-none">
                <!-- Abstract representation of the hero image -->
                <div class="relative h-full w-full flex items-center justify-center lg:justify-start lg:pl-20">
                     <!-- Background shape/blob -->
                     <div class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-[120%] h-[120%] bg-gradient-to-br from-orange-50/80 via-gray-100/50 to-transparent rounded-full blur-3xl"></div>
                     
                     <!-- Phone Mockup -->
                     <div class="relative z-10 w-[280px] h-[580px] bg-black rounded-[40px] border-[8px] border-gray-900 shadow-2xl transform rotate-[-10deg] translate-x-10 translate-y-10 overflow-hidden">
                        <!-- Screen Content -->
                        <div class="w-full h-full bg-white flex flex-col">
                            <!-- Status Bar -->
                            <div class="h-6 w-full bg-black text-white text-[10px] flex justify-between px-4 items-center">
                                <span>9:41</span>
                                <div class="flex gap-1">
                                    <div class="w-3 h-3 bg-white rounded-full opacity-20"></div>
                                    <div class="w-3 h-3 bg-white rounded-full opacity-20"></div>
                                </div>
                            </div>
                            <!-- App Header -->
                            <div class="p-4 bg-black text-white">
                                <div class="text-xs text-gray-400">Wallet</div>
                                <div class="font-bold text-lg mt-1">$1,240,500.00</div>
                            </div>
                            <!-- App Body -->
                            <div class="flex-1 bg-gray-50 p-4 space-y-3">
                                <div class="bg-white p-3 rounded-xl shadow-sm flex items-center gap-3">
                                    <div class="w-8 h-8 bg-orange-100 rounded-full flex items-center justify-center text-orange-500 text-xs">✈️</div>
                                    <div class="flex-1">
                                        <div class="text-xs font-bold">United Airlines</div>
                                        <div class="text-[10px] text-gray-500">Travel</div>
                                    </div>
                                    <div class="text-xs font-bold">-$450.00</div>
                                </div>
                                <div class="bg-white p-3 rounded-xl shadow-sm flex items-center gap-3">
                                    <div class="w-8 h-8 bg-blue-100 rounded-full flex items-center justify-center text-blue-500 text-xs">💻</div>
                                    <div class="flex-1">
                                        <div class="text-xs font-bold">Apple Store</div>
                                        <div class="text-[10px] text-gray-500">Equipment</div>
                                    </div>
                                    <div class="text-xs font-bold">-$2,100.00</div>
                                </div>
                                 <div class="bg-white p-3 rounded-xl shadow-sm flex items-center gap-3">
                                    <div class="w-8 h-8 bg-green-100 rounded-full flex items-center justify-center text-green-500 text-xs">🍔</div>
                                    <div class="flex-1">
                                        <div class="text-xs font-bold">Doordash</div>
                                        <div class="text-[10px] text-gray-500">Meals</div>
                                    </div>
                                    <div class="text-xs font-bold">-$45.20</div>
                                </div>
                            </div>
                        </div>
                     </div>

                     <!-- Card Mockup -->
                     <div class="absolute z-20 w-[320px] h-[200px] bg-gradient-to-br from-gray-800 to-black rounded-xl shadow-2xl transform rotate-[15deg] -translate-x-10 translate-y-32 flex flex-col justify-between p-6 text-white border border-gray-700">
                        <div class="flex justify-between items-start">
                            <div class="font-bold text-lg tracking-widest">Brex</div>
                            <div class="w-8 h-5 bg-yellow-500/80 rounded-sm"></div>
                        </div>
                        <div class="flex justify-between items-end">
                            <div class="text-xs tracking-widest opacity-80">•••• •••• •••• 4242</div>
                            <div class="w-8 h-8 rounded-full bg-white/10"></div>
                        </div>
                     </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Logos Section -->
    <section class="py-16 bg-white">
        <div class="max-w-[1440px] mx-auto px-6 lg:px-12 text-center">
            <h2 class="text-2xl lg:text-3xl font-bold mb-12">Trusted by 35,000+ top companies.</h2>
            <div class="grid grid-cols-2 md:grid-cols-4 lg:grid-cols-8 gap-8 items-center opacity-60 grayscale hover:grayscale-0 transition-all duration-500">
                <!-- Using text for logos for now as placeholders, ideally SVGs -->
                <div class="flex justify-center font-bold text-xl">TikTok</div>
                <div class="flex justify-center font-bold text-xl">substack</div>
                <div class="flex justify-center font-bold text-xl">ServiceTitan</div>
                <div class="flex justify-center font-bold text-xl">SEATGEEK</div>
                <div class="flex justify-center font-bold text-xl">LULU AND GEORGIA</div>
                <div class="flex justify-center font-bold text-xl">PLAID</div>
                <div class="flex justify-center font-bold text-xl">dispatchhealth</div>
                <div class="flex justify-center font-bold text-xl">GONG</div>
                <div class="flex justify-center font-bold text-xl">DOORDASH</div>
                <div class="flex justify-center font-bold text-xl">CURSOR</div>
                <div class="flex justify-center font-bold text-xl">SONOS</div>
                <div class="flex justify-center font-bold text-xl">ANTHROPIC</div>
            </div>
        </div>
    </section>

    <!-- Cards Section (The card is just the start) -->
    <section class="py-20 bg-white">
        <div class="max-w-[1440px] mx-auto px-6 lg:px-12">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <h2 class="text-4xl lg:text-5xl font-bold mb-6">The card is just the start.</h2>
                <p class="text-xl text-gray-600">Everything you need to boost spending power and control — and eliminate manual work.</p>
            </div>

            <div class="grid md:grid-cols-3 lg:grid-cols-5 gap-6">
                <!-- Card 1 -->
                <div class="bg-[#F9FAFB] p-6 rounded-xl hover:shadow-md transition-shadow h-full flex flex-col">
                    <h3 class="font-bold text-lg mb-2">Corporate cards</h3>
                    <p class="text-sm text-gray-600 mb-6">Spend smart globally with powerful cards and built-in controls.</p>
                    <div class="mt-auto">
                        <div class="bg-gray-800 h-24 rounded-lg w-full relative overflow-hidden">
                            <div class="absolute top-2 left-2 text-white text-[10px]">Brex</div>
                             <div class="absolute bottom-2 left-2 w-6 h-4 bg-yellow-500 rounded-sm opacity-50"></div>
                        </div>
                    </div>
                </div>

                <!-- Card 2 -->
                <div class="bg-[#F9FAFB] p-6 rounded-xl hover:shadow-md transition-shadow h-full flex flex-col">
                    <h3 class="font-bold text-lg mb-2">Expense management</h3>
                    <p class="text-sm text-gray-600 mb-6">Use AI to automate approvals and expense reports. Track in real time.</p>
                    <div class="mt-auto flex gap-2 overflow-hidden">
                        <div class="bg-white p-2 rounded shadow-sm text-[10px] w-full">JetBlue Airlines</div>
                        <div class="bg-white p-2 rounded shadow-sm text-[10px] w-full">Google Cloud</div>
                    </div>
                </div>

                <!-- Card 3 -->
                <div class="bg-[#F9FAFB] p-6 rounded-xl hover:shadow-md transition-shadow h-full flex flex-col">
                    <h3 class="font-bold text-lg mb-2">Travel</h3>
                    <p class="text-sm text-gray-600 mb-6">Simplify global travel with in-app booking and management.</p>
                    <div class="mt-auto">
                         <div class="bg-white p-2 rounded shadow-sm text-[10px] flex justify-between items-center">
                            <span>PHX</span>
                            <span class="text-orange-500">✈</span>
                            <span>AUS</span>
                         </div>
                    </div>
                </div>

                <!-- Card 4 -->
                <div class="bg-[#F9FAFB] p-6 rounded-xl hover:shadow-md transition-shadow h-full flex flex-col">
                    <h3 class="font-bold text-lg mb-2">Bill pay</h3>
                    <p class="text-sm text-gray-600 mb-6">Save time with AI-powered invoice entry and payment automation.</p>
                    <div class="mt-auto">
                         <div class="bg-white p-2 rounded shadow-sm text-[10px] border-l-4 border-green-500">
                            <div>Invoice</div>
                            <div class="text-right font-bold">$23,112.00</div>
                         </div>
                    </div>
                </div>

                <!-- Card 5 -->
                <div class="bg-[#F9FAFB] p-6 rounded-xl hover:shadow-md transition-shadow h-full flex flex-col">
                    <h3 class="font-bold text-lg mb-2">Banking and treasury</h3>
                    <p class="text-sm text-gray-600 mb-6">Save, spend, and grow your cash with up to 3.97%* — from day one.</p>
                    <div class="mt-auto relative h-20">
                         <div class="absolute bottom-0 left-0 right-0 h-16 bg-orange-100 rounded-t-full flex items-end justify-center pb-2">
                             <span class="font-bold text-orange-600">$500.00</span>
                         </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Solutions Section -->
    <section class="py-20 bg-[#F3F3F1]">
        <div class="max-w-[1440px] mx-auto px-6 lg:px-12">
            <h2 class="text-4xl lg:text-5xl font-bold mb-16 text-center">Solutions for every stage of growth.</h2>
            
            <div class="grid md:grid-cols-3 gap-8">
                <!-- Solution 1 -->
                <div class="group cursor-pointer">
                    <div class="aspect-[4/3] bg-gray-200 rounded-xl overflow-hidden mb-6 relative">
                        <img src="https://placehold.co/600x450/orange/white?text=Startups" alt="Startups" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500" />
                    </div>
                    <h3 class="text-2xl font-bold mb-3">Startups</h3>
                    <p class="text-gray-600 mb-4">Get the only complete financial stack designed to help start and scale your business.</p>
                    <a href="#" class="text-[#F45D22] font-medium flex items-center gap-1 hover:gap-2 transition-all">
                        Learn more <span class="text-lg">→</span>
                    </a>
                </div>

                <!-- Solution 2 -->
                <div class="group cursor-pointer">
                    <div class="aspect-[4/3] bg-gray-200 rounded-xl overflow-hidden mb-6 relative">
                        <img src="https://placehold.co/600x450/blue/white?text=Mid-size" alt="Mid-size companies" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500" />
                    </div>
                    <h3 class="text-2xl font-bold mb-3">Mid-size companies</h3>
                    <p class="text-gray-600 mb-4">Spend smarter worldwide with AI-powered budgets, expenses, payments, and travel.</p>
                    <a href="#" class="text-[#F45D22] font-medium flex items-center gap-1 hover:gap-2 transition-all">
                        Learn more <span class="text-lg">→</span>
                    </a>
                </div>

                <!-- Solution 3 -->
                <div class="group cursor-pointer">
                    <div class="aspect-[4/3] bg-gray-200 rounded-xl overflow-hidden mb-6 relative">
                        <img src="https://placehold.co/600x450/green/white?text=Enterprises" alt="Enterprises" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500" />
                    </div>
                    <h3 class="text-2xl font-bold mb-3">Enterprises</h3>
                    <p class="text-gray-600 mb-4">Simplify global travel and expenses with automation that makes compliance easy.</p>
                    <a href="#" class="text-[#F45D22] font-medium flex items-center gap-1 hover:gap-2 transition-all">
                        Learn more <span class="text-lg">→</span>
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section class="py-32 bg-white">
        <div class="max-w-[1440px] mx-auto px-6 lg:px-12">
            <div class="text-center max-w-3xl mx-auto mb-24">
                <h2 class="text-4xl lg:text-5xl font-bold mb-6">Supercharge your financial operations.</h2>
                <p class="text-xl text-gray-600">Maximize every resource with AI-powered controls, payments, and accounting.</p>
            </div>

            <div class="space-y-32">
                <!-- Feature 1 -->
                <div class="grid lg:grid-cols-2 gap-16 items-center">
                    <div class="bg-[#F3F4F6] rounded-2xl p-12 flex items-center justify-center">
                        <!-- Mockup: Marketing offsite -->
                        <div class="bg-white rounded-xl shadow-sm p-6 w-full max-w-sm">
                            <div class="flex justify-between items-center mb-4">
                                <span class="font-semibold">Marketing offsite</span>
                                <div class="w-6 h-6 bg-gray-200 rounded-full"></div>
                            </div>
                            <div class="w-full bg-gray-100 rounded-full h-2 mb-2">
                                <div class="bg-blue-500 h-2 rounded-full w-1/3"></div>
                            </div>
                            <div class="flex justify-between text-sm text-gray-500 mb-4">
                                <span>$150k</span>
                                <span>$500k</span>
                            </div>
                            <div class="flex gap-2">
                                <span class="bg-green-100 text-green-700 px-2 py-1 rounded text-xs font-medium">✓ In policy</span>
                                <div class="flex -space-x-2">
                                    <div class="w-6 h-6 rounded-full bg-gray-300 border-2 border-white"></div>
                                    <div class="w-6 h-6 rounded-full bg-gray-400 border-2 border-white"></div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div>
                        <h3 class="text-3xl lg:text-4xl font-bold mb-6">Control spend before it happens.</h3>
                        <p class="text-lg text-gray-600 mb-8 leading-relaxed">
                            Set budgets and allocate spend limits with auto-enforced controls that empower employees to spend wisely. Track and adjust in real time to keep everyone on budget and maximize impact.
                        </p>
                        <a href="#" class="text-[#F45D22] font-medium flex items-center gap-1 hover:gap-2 transition-all">
                            Explore Brex cards <span class="text-lg">→</span>
                        </a>
                    </div>
                </div>

                <!-- Feature 2 -->
                <div class="grid lg:grid-cols-2 gap-16 items-center">
                    <div class="order-2 lg:order-1">
                        <h3 class="text-3xl lg:text-4xl font-bold mb-6">Make doing your expenses easy.</h3>
                        <p class="text-lg text-gray-600 mb-8 leading-relaxed">
                            Make expenses a breeze for employees and managers with automated receipts, an AI-powered expense assistant, in-app travel bookings and itinerary changes. All in a five-star mobile app.
                        </p>
                        <a href="#" class="text-[#F45D22] font-medium flex items-center gap-1 hover:gap-2 transition-all">
                            Explore Brex expense management <span class="text-lg">→</span>
                        </a>
                    </div>
                    <div class="bg-[#F3F4F6] rounded-2xl p-12 flex items-center justify-center order-1 lg:order-2">
                        <!-- Mockup: Rideshare Receipt -->
                        <div class="bg-white rounded-xl shadow-sm p-6 w-full max-w-sm relative">
                             <div class="absolute -top-4 right-8 bg-purple-100 text-purple-700 px-3 py-1 rounded-full text-xs font-medium">Receipt</div>
                             <div class="flex items-center gap-4 mb-4">
                                 <div class="w-10 h-10 bg-black rounded flex items-center justify-center text-white font-bold text-xs">Uber</div>
                                 <div>
                                     <div class="font-bold">Rideshare</div>
                                     <div class="text-xs text-gray-500">Today, 4:32 PM</div>
                                 </div>
                                 <div class="ml-auto font-bold text-lg">$43</div>
                             </div>
                             <div class="bg-green-100 text-green-700 px-2 py-1 rounded text-xs font-medium inline-block">✓ In policy</div>
                        </div>
                    </div>
                </div>

                <!-- Feature 3 -->
                <div class="grid lg:grid-cols-2 gap-16 items-center">
                    <div class="bg-[#F3F4F6] rounded-2xl p-12 flex items-center justify-center">
                        <!-- Mockup: Treasury Graph -->
                        <div class="bg-white rounded-xl shadow-sm p-6 w-full max-w-sm">
                            <div class="flex justify-between items-center mb-6">
                                <span class="font-semibold">Treasury account</span>
                            </div>
                            <div class="flex gap-4 mb-4">
                                <div class="bg-green-100 text-green-700 px-3 py-1 rounded text-sm font-bold">+ $85,225</div>
                                <div class="text-sm text-gray-500 py-1">Same-hour liquidity</div>
                            </div>
                            <!-- Simple SVG Graph -->
                            <svg viewBox="0 0 300 100" class="w-full h-24 text-blue-500 fill-current opacity-20">
                                <path d="M0,100 L0,80 C20,80 40,60 60,70 C80,80 100,40 120,50 C140,60 160,30 180,40 C200,50 220,20 240,30 C260,40 280,10 300,20 L300,100 Z" />
                            </svg>
                             <svg viewBox="0 0 300 100" class="w-full h-24 text-blue-500 stroke-current fill-none stroke-2 absolute bottom-6 left-6 w-[calc(100%-3rem)]">
                                <path d="M0,80 C20,80 40,60 60,70 C80,80 100,40 120,50 C140,60 160,30 180,40 C200,50 220,20 240,30 C260,40 280,10 300,20" />
                            </svg>
                        </div>
                    </div>
                    <div>
                        <h3 class="text-3xl lg:text-4xl font-bold mb-6">Maximize your spending power.</h3>
                        <p class="text-lg text-gray-600 mb-8 leading-relaxed">
                            Unlock up to 3.97%*, fast global payments, up to 30x higher credit limits, and cash back with a Brex business account. Plus, safeguard your capital with up to $6M in additional FDIC insurance through our program banks.
                        </p>
                        <a href="#" class="text-[#F45D22] font-medium flex items-center gap-1 hover:gap-2 transition-all">
                            Explore Brex business accounts <span class="text-lg">→</span>
                        </a>
                    </div>
                </div>

                <!-- Feature 4 -->
                <div class="grid lg:grid-cols-2 gap-16 items-center">
                    <div class="order-2 lg:order-1">
                        <h3 class="text-3xl lg:text-4xl font-bold mb-6">Pay vendors faster and easier.</h3>
                        <p class="text-lg text-gray-600 mb-8 leading-relaxed">
                            Save time with AI-powered automation of invoice entry, approval, and payments. Issue vendor-specific cards for any teams with per-transaction limits and procurement approval flows.
                        </p>
                        <a href="#" class="text-[#F45D22] font-medium flex items-center gap-1 hover:gap-2 transition-all">
                            Explore Brex bill pay <span class="text-lg">→</span>
                        </a>
                    </div>
                    <div class="bg-[#F3F4F6] rounded-2xl p-12 flex items-center justify-center order-1 lg:order-2">
                        <!-- Mockup: AWS Invoice -->
                        <div class="bg-white rounded-xl shadow-sm p-6 w-full max-w-sm">
                            <div class="flex gap-4 mb-4">
                                <div class="w-10 h-10 bg-purple-100 rounded flex items-center justify-center text-purple-600 font-bold text-xs">AWS</div>
                                <div class="flex-1">
                                    <div class="flex justify-between">
                                        <span class="text-xs text-gray-500">Vendor</span>
                                        <span class="text-xs text-gray-500">Due</span>
                                    </div>
                                    <div class="flex justify-between font-medium">
                                        <span>AWS</span>
                                        <span>May 07</span>
                                    </div>
                                </div>
                            </div>
                            <div class="border-t pt-4">
                                <div class="flex justify-between items-center">
                                    <span class="text-sm text-gray-500">Total</span>
                                    <span class="font-bold text-lg">$10,000</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Feature 5 -->
                <div class="grid lg:grid-cols-2 gap-16 items-center">
                    <div class="bg-[#F3F4F6] rounded-2xl p-12 flex items-center justify-center">
                         <div class="grid grid-cols-2 gap-4 w-full max-w-sm">
                             <div class="bg-white p-6 rounded-xl shadow-sm flex items-center justify-center font-bold text-gray-400">Sage</div>
                             <div class="bg-white p-6 rounded-xl shadow-sm flex items-center justify-center font-bold text-gray-400">ORACLE<br>NetSuite</div>
                             <div class="bg-white p-6 rounded-xl shadow-sm flex items-center justify-center font-bold text-gray-400">intuit<br>quickbooks</div>
                             <div class="bg-white p-6 rounded-xl shadow-sm flex items-center justify-center font-bold text-gray-400">W</div>
                         </div>
                    </div>
                    <div>
                        <h3 class="text-3xl lg:text-4xl font-bold mb-6">Accelerate accounting with AI.</h3>
                        <p class="text-lg text-gray-600 mb-8 leading-relaxed">
                            Save time with AI-generated suggestions and 1,000s of two-way ERP integrations. Book accruals for incomplete expenses with one click to close the books every day and automate GL coding by entity globally.
                        </p>
                        <a href="#" class="text-[#F45D22] font-medium flex items-center gap-1 hover:gap-2 transition-all">
                            Explore Brex accounting automation <span class="text-lg">→</span>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Stats Section -->
    <section class="py-20 bg-white">
        <div class="max-w-[1440px] mx-auto px-6 lg:px-12">
            <h2 class="text-4xl lg:text-5xl font-bold mb-16 text-center">Save and earn more, only with Brex.</h2>
            <div class="grid md:grid-cols-3 gap-12 text-center md:text-left border-t border-gray-200 pt-12">
                <div>
                    <h3 class="font-bold text-lg mb-2">AI-powered automation</h3>
                    <div class="text-5xl lg:text-6xl font-bold text-[#F45D22] mb-4">4,250 hours</div>
                    <p class="text-gray-600 text-sm">Average time saved per year with Brex's expense and accounting automation.</p>
                </div>
                <div>
                    <h3 class="font-bold text-lg mb-2">Best-in-class treasury</h3>
                    <div class="text-5xl lg:text-6xl font-bold text-[#F45D22] mb-4">Up to 3.97%+</div>
                    <p class="text-gray-600 text-sm">Same-hour liquidity and built-in treasury that makes you money.</p>
                </div>
                <div>
                    <h3 class="font-bold text-lg mb-2">Superior policy compliance</h3>
                    <div class="text-5xl lg:text-6xl font-bold text-[#F45D22] mb-4">99%</div>
                    <p class="text-gray-600 text-sm">Average rate of expense policy compliance by employees on Brex.</p>
                </div>
            </div>
            <p class="text-[10px] text-gray-400 mt-12 text-center">These metrics are based on internal metrics from December 2024. Past performance does not guarantee future results, which may vary.</p>
        </div>
    </section>

    <!-- Testimonial Section -->
    <section class="py-20 bg-[#F3F3F1]">
        <div class="max-w-[1440px] mx-auto px-6 lg:px-12">
            <!-- Tabs -->
            <div class="flex justify-center border-b border-gray-300 mb-12">
                <button class="px-8 py-4 text-gray-500 hover:text-black font-medium border-b-2 border-transparent hover:border-gray-300">DoorDash</button>
                <button class="px-8 py-4 text-black font-medium border-b-2 border-black">SeatGeek</button>
                <button class="px-8 py-4 text-gray-500 hover:text-black font-medium border-b-2 border-transparent hover:border-gray-300">Lemonade</button>
            </div>

            <div class="grid lg:grid-cols-2 gap-12 items-center">
                <div class="aspect-[4/3] rounded-2xl overflow-hidden">
                    <img src="https://placehold.co/800x600/333/999?text=SeatGeek+Executive" alt="SeatGeek Executive" class="w-full h-full object-cover" />
                </div>
                <div>
                    <div class="text-[#F45D22] font-bold text-2xl mb-6">SEAT<br>GEEK</div>
                    <blockquote class="text-3xl lg:text-4xl font-serif mb-8 leading-tight">
                        "We've gone from spending 20 hours a month on close to under 2 hours, while achieving over 99% employee compliance."
                    </blockquote>
                    <div class="mb-8">
                        <div class="font-medium underline decoration-gray-300 underline-offset-4">Teddy Collins</div>
                        <div class="text-gray-600 mt-1">Vice President of Corporate Finance at SeatGeek</div>
                    </div>
                    <a href="#" class="text-[#F45D22] font-medium flex items-center gap-1 hover:gap-2 transition-all">
                        Read the case study <span class="text-lg">→</span>
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- CTA Section -->
    <section class="bg-[#050505] text-white overflow-hidden">
        <div class="max-w-[1440px] mx-auto grid lg:grid-cols-2">
            <div class="px-6 lg:px-12 py-24 lg:py-32 flex flex-col justify-center">
                <h2 class="text-4xl lg:text-6xl font-bold mb-6">See what Brex<br>can do for you.</h2>
                <p class="text-xl text-gray-400 mb-10 max-w-md">Learn how our intelligent finance platform can help your company spend smarter and move faster.</p>
                <div>
                    <a href="#" class="bg-[#F45D22] hover:bg-[#E04F1A] text-white px-8 py-4 rounded-md font-semibold transition-colors inline-block">
                        Get started
                    </a>
                </div>
            </div>
            <div class="relative h-64 lg:h-auto bg-[#F45D22]">
                 <img src="https://placehold.co/800x800/orange/white?text=App+Mockup" alt="Brex App" class="w-full h-full object-cover mix-blend-overlay opacity-50" />
                 <!-- Diagonal overlay effect -->
                 <div class="absolute inset-0 bg-gradient-to-r from-[#050505] to-transparent lg:w-1/3"></div>
            </div>
        </div>
    </section>

    <!-- Insights Section -->
    <section class="py-24 bg-white">
        <div class="max-w-[1440px] mx-auto px-6 lg:px-12">
            <h2 class="text-3xl lg:text-4xl font-bold mb-12">Trending insights on intelligent finance.</h2>
            
            <div class="grid md:grid-cols-3 gap-8">
                <!-- Post 1 -->
                <div class="group cursor-pointer">
                    <div class="aspect-video bg-gray-200 rounded-xl overflow-hidden mb-6">
                        <img src="https://placehold.co/600x340/333/white?text=Intelligent+Finance" alt="Blog Post" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500" />
                    </div>
                    <h3 class="text-xl font-bold mb-3 group-hover:text-[#F45D22] transition-colors">What is intelligent finance? 8 reasons to switch to AI-powered financial operations</h3>
                    <p class="text-sm text-gray-600 line-clamp-3">Intelligent finance uses AI to eliminate manual expense reports, reviews, and policy enforcement. Learn how it automates finance, boosts compliance, and more.</p>
                </div>

                <!-- Post 2 -->
                <div class="group cursor-pointer">
                    <div class="aspect-video bg-gray-200 rounded-xl overflow-hidden mb-6">
                        <img src="https://placehold.co/600x340/444/white?text=Global+Cards" alt="Blog Post" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500" />
                    </div>
                    <h3 class="text-xl font-bold mb-3 group-hover:text-[#F45D22] transition-colors">Reimagining global cards and travel management for the enterprise</h3>
                    <p class="text-sm text-gray-600 line-clamp-3">The CEOs of Brex and Navan discuss how their partnership unlocks 100% travel payment reconciliation for enterprise companies.</p>
                </div>

                <!-- Post 3 -->
                <div class="group cursor-pointer">
                    <div class="aspect-video bg-gray-200 rounded-xl overflow-hidden mb-6">
                        <img src="https://placehold.co/600x340/555/white?text=Procurement" alt="Blog Post" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500" />
                    </div>
                    <h3 class="text-xl font-bold mb-3 group-hover:text-[#F45D22] transition-colors">The future of procurement is automated and integrated</h3>
                    <p class="text-sm text-gray-600 line-clamp-3">How modern companies approach procurement as part of a unified spend management system.</p>
                </div>
            </div>

            <div class="flex gap-4 mt-12">
                <button class="w-10 h-10 rounded-full border border-gray-300 flex items-center justify-center hover:bg-gray-50 transition-colors">
                    ←
                </button>
                <button class="w-10 h-10 rounded-full border border-gray-300 flex items-center justify-center hover:bg-gray-50 transition-colors">
                    →
                </button>
            </div>
        </div>
    </section>

    <!-- Chat Widget -->
    <div class="fixed bottom-6 right-6 z-50">
        <button class="bg-[#F45D22] text-white p-4 rounded-full shadow-lg hover:bg-[#E04F1A] transition-colors">
            <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 10h.01M12 10h.01M16 10h.01M9 16H5a2 2 0 01-2-2V6a2 2 0 012-2h14a2 2 0 012 2v8a2 2 0 01-2 2h-5l-5 5v-5z" />
            </svg>
        </button>
    </div>

</main>

