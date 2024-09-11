<script>
  import Spotlight from "$lib/components/spotlight.svelte";
  import Laptop from "../lib/components/laptop.svelte";
  import Faqtabs from "../lib/components/faqtabs.svelte";
  import Services from "../lib/components/services.svelte";
  import Intro from "$lib/components/sectionintro.svelte";
  import Footer from "../lib/components/footer.svelte";
  import AOS from "aos";
  import "aos/dist/aos.css";
  import { onMount } from "svelte";
  import { MetaTags } from "svelte-meta-tags";
  
  onMount(() => {
    AOS.init();
  });
</script>

<Spotlight id="home" />

<!-- Testimonial section -->
<div class="box-shadow h-auto min-h-[25rem] sm:min-h-[30rem] w-full bg-black bg-grid-small-white/[0.2] relative flex items-center justify-center">
  <div class="absolute pointer-events-none inset-0 flex items-center justify-center bg-black/60 [mask-image:radial-gradient(ellipse_at_center,transparent_50%,black)]"></div>
  
  <!-- <div class="flex flex-col px-4 sm:px-8 lg:px-16"> -->
  <div class="flex flex-col p-0">
    <Intro
      id="testimonials"
      name="Client Testimonials"
      desc="Esteemed clients share their experiences with Magnimonts tailored digital solutions."
    />
    <Laptop />
  </div>
</div>

<!-- Services -->
<div class="box-shadow min-h-screen w-full bg-black bg-dot-white/[0.2] rounded-md shadow-2xl relative flex flex-col items-center justify-center py-8">
  <div class="absolute pointer-events-none inset-0 flex items-center justify-center bg-black [mask-image:radial-gradient(ellipse_at_center,transparent_20%,black)]"></div>

  <Intro
    id="services"
    name="Our Expertise"
    desc="Innovative solutions"
    class="highlight"
  />
  
  <Services />
</div>

<!-- FAQ Section -->
<div class="box-shadow h-auto min-h-[25rem] sm:min-h-[30rem] w-full bg-black bg-grid-small-white/[0.2] relative flex flex-col items-center justify-center py-8">
  <div class="absolute pointer-events-none inset-0 flex items-center justify-center bg-black/60 [mask-image:radial-gradient(ellipse_at_center,transparent_50%,black)]"></div>
  
  <Intro
    name="Frequently Asked Questions"
    desc="Addressing your queries, simplifying your journey"
  />
  <Faqtabs />
</div>

<Footer />

<!-- Meta Tags -->
<MetaTags
  title="Magnimont"
  description="Magnimont description metatag"
  canonical="https://www.canonical.ie/"
  openGraph={{
    url: "https://www.url.ie/a",
    title: "Magnimont",
    description: "Magnimont is a leading digital agency specializing in custom web development, AI solutions, and tailored software. We craft innovative websites, intelligent chatbots, Discord bots, and custom applications to drive growth for businesses across industries. Our experts blend cutting-edge technologies with creative ingenuity to deliver digital experiences that captivate users and propel your brand forward.",
    images: [
      {
        url: "%sveltekit.assets%/favico.svg",
        width: 100,
        height: 100,
        alt: "Og Image Alt",
      },
    ],
    siteName: "Magnimont",
  }}
  twitter={{
    handle: "@magnimont",
    site: "@magnimont",
    cardType: "https://i.imgur.com/aTa8bjq.png",
    title: "Magnimont",
    description: "Magnimont is a leading digital agency specializing in custom web development, AI solutions, and tailored software. We craft innovative websites, intelligent chatbots, Discord bots, and custom applications to drive growth for businesses across industries. Our experts blend cutting-edge technologies with creative ingenuity to deliver digital experiences that captivate users and propel your brand forward.",
    image: "%sveltekit.assets%/favico.svg",
    imageAlt: "https://i.imgur.com/aTa8bjq.png",
  }}
/>
