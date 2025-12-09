<script>
  import { onMount } from 'svelte';

  let isScrolled = false;

  onMount(() => {
    const handleScroll = () => {
      isScrolled = window.scrollY > 10;
    };
    window.addEventListener('scroll', handleScroll);
    return () => window.removeEventListener('scroll', handleScroll);
  });
</script>

<header class="fixed top-0 left-0 right-0 z-50 transition-all duration-300 {isScrolled ? 'bg-white shadow-sm py-3' : 'bg-transparent py-5'}">
  <div class="max-w-[1440px] mx-auto px-6 lg:px-12 flex items-center justify-between">
    <!-- Logo -->
    <div class="flex items-center">
      <a href="/" class="text-2xl font-bold tracking-tight flex items-center gap-1">
        <svg viewBox="0 0 24 24" class="w-6 h-6 fill-current" aria-label="Brex Logo">
            <path d="M3 3h6c3.31 0 6 2.69 6 6 0 2.16-1.15 4.05-2.85 5.15C13.85 15.25 15 17.06 15 19c0 3.31-2.69 6-6 6H3V3zm6 9c1.66 0 3-1.34 3-3s-1.34-3-3-3H6v6h3zm0 10c1.66 0 3-1.34 3-3s-1.34-3-3-3H6v6h3z" fill="currentColor"/>
        </svg>
        <span>Brex</span>
      </a>
    </div>

    <!-- Navigation -->
    <nav class="hidden lg:flex items-center gap-8 text-[15px] font-medium text-gray-700">
      <button class="flex items-center gap-1 hover:text-black transition-colors group">
        Products
        <svg class="w-3 h-3 text-gray-500 group-hover:text-black transition-transform group-hover:rotate-180" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7" />
        </svg>
      </button>
      <button class="flex items-center gap-1 hover:text-black transition-colors group">
        Solutions
        <svg class="w-3 h-3 text-gray-500 group-hover:text-black transition-transform group-hover:rotate-180" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7" />
        </svg>
      </button>
      <button class="flex items-center gap-1 hover:text-black transition-colors group">
        Resources
        <svg class="w-3 h-3 text-gray-500 group-hover:text-black transition-transform group-hover:rotate-180" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7" />
        </svg>
      </button>
      <a href="#" class="hover:text-black transition-colors">Customers</a>
      <a href="#" class="hover:text-black transition-colors">Pricing</a>
    </nav>

    <!-- Right Actions -->
    <div class="flex items-center gap-6 text-[15px] font-medium">
      <a href="#" class="hidden lg:block text-gray-700 hover:text-black transition-colors">Sign in</a>
      <a href="#" class="hidden lg:block text-gray-700 hover:text-black transition-colors">See a demo</a>
      <a href="#" class="bg-[#F45D22] hover:bg-[#E04F1A] text-white px-5 py-2.5 rounded-md transition-colors font-semibold">
        Get started
      </a>
      <!-- Mobile Menu Button -->
      <button class="lg:hidden text-gray-700">
        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
        </svg>
      </button>
    </div>
  </div>
</header>
