<script>
  import {
    Footer,
    FooterLinkGroup,
    FooterLink,
    FooterIcon,
    FooterCopyright,
  } from "flowbite-svelte";
  import {
    DiscordSolid,
    LinkedinSolid,
    GithubSolid,
    YoutubeSolid,
  } from "flowbite-svelte-icons";
</script>

<Footer footerType="sitemap">
  <div class="grid grid-cols-1 md:grid-cols-2 gap-8 pt-12 px-6 place-content-center bg-black">
    <!-- Left Side: Image, Description, Copyright -->
    <div class="flex flex-col items-center md:items-start">
      <!-- Image -->
      <img src="/path-to-your-image.png" alt="Company Image" class="w-32 h-32 mb-4" />
      
      <!-- Description -->
      <div class="text-center md:text-left">
        <p class="text-white text-sm mb-4">The best Discord bot to bootstrap and grow your Discord server.</p>
      </div>

      <!-- Copyright -->
      <FooterCopyright
        spanClass="text-xs text-amber-200 sm:text-center"
        href="/"
        by="Sidescroll Ventures™"
      />
    </div>

    <!-- Right Side: Horizontal Sections -->
    <div class="flex flex-wrap md:flex-row md:space-x-12 justify-between w-full">
      <!-- Magnimont -->
      <div class="mb-8 md:mb-0 flex flex-col items-center md:items-start">
        <h2 class="text-sm font-semibold text-amber-200 uppercase mb-4">Magnimont</h2>
        <FooterLinkGroup ulClass="text-gray-300 text-xs">
          <FooterLink liClass="mb-2" href="/">About</FooterLink>
          <FooterLink liClass="mb-2" href="https://forum.magnimont.com">Forum</FooterLink>
          <FooterLink liClass="mb-2" href="https://host.magnimont.com">Hosting</FooterLink>
          <FooterLink liClass="mb-2" href="/">Career</FooterLink>
        </FooterLinkGroup>
      </div>

      <!-- Socials -->
      <div class="mb-8 md:mb-0 flex flex-col items-center md:items-start">
        <h2 class="text-sm font-semibold text-amber-200 uppercase mb-4">Socials</h2>
        <FooterLinkGroup ulClass="text-gray-300 text-xs">
          <FooterLink liClass="mb-2" href="https://discord.gg/magnimont-876113814314164256">Discord Server</FooterLink>
          <FooterLink liClass="mb-2" href="https://www.linkedin.com/company/magnimont/">Linkedin</FooterLink>
          <FooterLink liClass="mb-2" href="https://github.com/Magnimont">Github</FooterLink>
          <FooterLink liClass="mb-2" href="https://www.youtube.com/@Magnimont/videos">Youtube</FooterLink>
        </FooterLinkGroup>
      </div>

      <!-- Legal -->
      <div class="mb-8 md:mb-0 flex flex-col items-center md:items-start">
        <h2 class="text-sm font-semibold text-amber-200 uppercase mb-4">Legal</h2>
        <FooterLinkGroup ulClass="text-gray-300 text-xs">
          <FooterLink liClass="mb-2" href="/privacy-policy">Privacy Policy</FooterLink>
          <FooterLink liClass="mb-2" href="/">Licensing</FooterLink>
          <FooterLink liClass="mb-2" href="/terms-of-service">Terms & Conditions</FooterLink>
        </FooterLinkGroup>
      </div>

      <!-- Connect -->
      <div class="flex flex-col items-center md:items-start">
        <h2 class="text-sm font-semibold text-amber-200 uppercase mb-4">Connect</h2>
        <FooterLinkGroup ulClass="text-gray-300 text-xs">
          <FooterLink liClass="mb-4" href="tel:+91 8076974315">+91 8076974315</FooterLink>
          <FooterLink liClass="mb-4" href="mailto:hi@magnimont.com">hi@magnimont.com</FooterLink>
        </FooterLinkGroup>
      </div>
    </div>
  </div>
</Footer>
