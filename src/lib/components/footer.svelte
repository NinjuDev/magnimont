<script>
  import {
    Footer,
    FooterLinkGroup,
    FooterLink,
    FooterBrand,
    FooterIcon,
    FooterCopyright,
  } from "flowbite-svelte";
  import {
    FacebookSolid,
    GithubSolid,
    DiscordSolid,
    TwitterSolid,
    LinkedinSolid,
    YoutubeSolid,
  } from "flowbite-svelte-icons";
</script>

<Footer footerType="sitemap">
  <div
    class="grid grid-cols-2 gap-8 pt-12 px-6 md:grid-cols-4 place-content-center bg-black"
  >
    <div>
      <h2 class="mb-6 text-sm font-semibold text-amber-200 uppercase">
        Magnimont
      </h2>
      <FooterLinkGroup ulClass="text-gray-300 text-xs">
        <FooterLink liClass="mb-2" href="/">About</FooterLink>
        <FooterLink liClass="mb-2" href="https://forum.magnimont.com">Forum</FooterLink>
        <FooterLink liClass="mb-2" href="https://host.magnimont.com">Hosting</FooterLink>
        <FooterLink liClass="mb-2" href="/">Career</FooterLink>
      </FooterLinkGroup>
    </div>
    <div>
      <h2 class="mb-6 text-sm font-semibold uppercase text-amber-200">
        Socials
      </h2>
      <FooterLinkGroup ulClass="text-gray-300 text-xs">
        <FooterLink liClass="mb-2" href="https://discord.gg/magnimont-876113814314164256">Discord Server</FooterLink>
        <FooterLink liClass="mb-2" href="https://www.linkedin.com/company/magnimont/">Linkedin</FooterLink>
        <FooterLink liClass="mb-2" href="https://github.com/Magnimont">Github</FooterLink>
        <FooterLink liClass="mb-2" href="https://www.youtube.com/@Magnimont/videos">Youtube</FooterLink>
      </FooterLinkGroup>
    </div>
    <div>
      <h2 class="mb-6 text-sm font-semibold uppercase text-amber-200">Legal</h2>
      <FooterLinkGroup ulClass="text-gray-300 text-xs">
        <FooterLink liClass="mb-2" href="/privacy-policy">Privacy Policy</FooterLink>
        <FooterLink liClass="mb-2" href="/">Licensing</FooterLink>
        <FooterLink liClass="mb-2" href="/terms-of-service">Terms & Conditions</FooterLink>
      </FooterLinkGroup>
    </div>
    <div>
      <h2 class="mb-6 text-sm font-semibold uppercase text-amber-200">
        Connect
      </h2>
      <FooterLinkGroup ulClass="text-gray-300 text-xs">
        <FooterLink liClass="mb-4" href="tel:+91 8076974315">+91 8076974315</FooterLink>
        <FooterLink liClass="mb-4" href="mailto:hi@magnimont.com">hi@magnimont.com</FooterLink>
      </FooterLinkGroup>
    </div>
  </div>

  <!-- Add the image part here -->
  <div class="flex justify-center md:justify-between bg-black">
    <img src="https://cdn.discordapp.com/icons/876113814314164256/0e0f35f8cd793beefafbdec39382f1db.png" alt="The One Stop Tech Store" class="w-1/2 md:w-1/4 p-4" />
    <div class="flex flex-col justify-center space-y-4">
      <div>
        <h3 class="text-sm font-semibold text-amber-200">Company</h3>
        <FooterLinkGroup ulClass="text-gray-300 text-xs">
          <FooterLink liClass="mb-2" href="/">Careers</FooterLink>
          <FooterLink liClass="mb-2" href="/">Terms of use</FooterLink>
          <FooterLink liClass="mb-2" href="/">Privacy Policy</FooterLink>
          <FooterLink liClass="mb-2" href="/">Bug bounty program</FooterLink>
          <FooterLink liClass="mb-2" href="/">Contact</FooterLink>
        </FooterLinkGroup>
      </div>
      <FooterCopyright
        spanClass="text-xs text-amber-200 sm:text-center"
        href="/"
        by="Sidescroll Ventures™"
      />
    </div>
  </div>
</Footer>
