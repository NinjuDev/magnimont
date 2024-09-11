<script>
  import Button from "./button.svelte";
</script>

<!-- Wrapper to center content with responsive padding -->
<div class="flex items-center justify-center py-4 md:pb-3">
  <!-- Flex container for the titles, responsive layout -->
  <div
    class="flex flex-col md:flex-row items-center justify-between lg:gap-7 md:gap-4 sm:gap-2 self-center"
  >
    <!-- "Introducing" text with responsive font sizes -->
    <div
      data-aos-delay="0"
      data-aos-duration="500"
      data-aos="fade-up"
      class="staggered font-calsans text-3xl sm:text-4xl md:text-5xl xl:text-7xl font-bold text-center text-transparent bg-clip-text bg-gradient-to-b from-neutral-50 to-neutral-400"
    >
      Introducing
    </div>

    <!-- "MAGNIMONT" text with responsive font sizes -->
    <h1
      data-aos-delay="0"
      data-aos-duration="500"
      data-aos="fade-up"
      class="golden-text staggered font-calsans text-3xl sm:text-5xl md:text-6xl xl:text-7xl font-bold text-center text-transparent bg-clip-text bg-gradient-to-b from-neutral-50 to-neutral-400"
    >
      MAGNIMONT
    </h1>
  </div>
</div>

<!-- Paragraph text with responsive margins, max width, and text sizes -->
<p
  data-aos-delay="500"
  data-aos-duration="1000"
  data-aos="fade"
  class="font-inter mt-4 font-normal text-xs sm:text-sm md:text-base lg:text-lg text-neutral-400 max-w-[90%] sm:max-w-[75%] md:max-w-[60%] tracking-wider text-center mx-auto"
>
  Magnimont offers tailored digital solutions to elevate brands and drive
  success. Our experts craft custom websites, intelligent chatbots for platforms
  like Discord and Telegram, branded visuals and marketing assets, and
  seamlessly integrated bot systems. Whatever your vision, we leverage
  cutting-edge tech and creative prowess to develop captivating digital
  experiences aligned with your unique goals and audience. Unlock your potential
  with Magnimont's innovative, full-service digital solutions.

  <br />
  <b>So what are you waiting for?</b>
  <br />

  <!-- Button component with responsive margin -->
</p>
<div class="flex justify-center mt-6">
  <Button />
</div>
