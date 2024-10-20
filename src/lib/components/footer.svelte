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
  <div class="bg-black text-white p-8 rounded-lg shadow-lg">
    <div class="flex flex-col md:flex-row gap-8 justify-center">
      <!-- Image, Description, Copyright -->
      <div class="flex flex-col items-center md:items-start flex-1">
        <!-- Image -->
        <img
          src="https://images-ext-1.discordapp.net/external/Fck1ccubcCLfJ_sL7BuIG3Q6c5uU_MFZ3XbEAme0jBQ/%3Fsize%3D512/https/cdn.discordapp.com/icons/876113814314164256/0e0f35f8cd793beefafbdec39382f1db.png"
          alt="Company Image"
          class="w-32 h-32 mb-4 rounded-full border-2 border-amber-200"
        />

        <!-- Description -->
        <div class="text-center md:text-left">
          <p class="text-white text-lg font-bold mb-4">Innovating since binary age!</p>
        </div>

        <!-- Copyright -->
        <FooterCopyright
          spanClass="text-xs text-amber-200 sm:text-center"
          href="/"
          by="Magnimont™"
        />
      </div>

      <!-- Horizontal Sections -->
      <div class="flex flex-col md:flex-row gap-8 flex-1 justify-between">
        <!-- Magnimont -->
        <div class="flex flex-col space-y-2">
          <h2 class="text-amber-200 font-bold uppercase mb-2">Magnimont</h2>
          <FooterLinkGroup ulClass="space-y-2">
            <FooterLink href="/">About</FooterLink>
            <FooterLink href="https://forum.magnimont.com">Forum</FooterLink>
            <FooterLink href="https://host.magnimont.com">Hosting</FooterLink>
            <FooterLink href="/">Career</FooterLink>
          </FooterLinkGroup>
        </div>

        <!-- Socials -->
        <div class="flex flex-col space-y-2">
          <h2 class="text-amber-200 font-bold uppercase mb-2">Socials</h2>
          <FooterLinkGroup ulClass="space-y-2">
            <FooterLink href="https://discord.gg/magnimont-876113814314164256">Discord Server</FooterLink>
            <FooterLink href="https://www.linkedin.com/company/magnimont/">Linkedin</FooterLink>
            <FooterLink href="https://github.com/Magnimont">Github</FooterLink>
            <FooterLink href="https://www.youtube.com/@Magnimont/videos">Youtube</FooterLink>
          </FooterLinkGroup>
        </div>

        <!-- Legal -->
        <div class="flex flex-col space-y-2">
          <h2 class="text-amber-200 font-bold uppercase mb-2">Legal</h2>
          <FooterLinkGroup ulClass="space-y-2">
            <FooterLink href="/privacy-policy">Privacy Policy</FooterLink>
            <FooterLink href="/">Licensing</FooterLink>
            <FooterLink href="/terms-of-service">Terms & Conditions</FooterLink>
          </FooterLinkGroup>
        </div>

        <!-- Connect -->
        <div class="flex flex-col space-y-2">
          <h2 class="text-amber-200 font-bold uppercase mb-2">Connect</h2>
          <FooterLinkGroup ulClass="space-y-2">
            <FooterLink href="tel:+91 8076974315">+91 8076974315</FooterLink>
            <FooterLink href="mailto:hi@magnimont.com">hi@magnimont.com</FooterLink>
          </FooterLinkGroup>
        </div>
      </div>
    </div>

    <!-- Payment Options with reduced overall scale -->
    <div class="flex flex-row justify-center items-center mt-6" style="transform: scale(0.8);"> <!-- Adjust scale here -->
      <img src="https://i.imghippo.com/files/0lR9W1729434470.png" alt="PayPal" class="w-10 h-10 mx-1.5" />
      <img src="https://i.imghippo.com/files/FfEeo1729443120.png" alt="Xoom" class="w-10 h-10 mx-1.5" />
      <img src="https://i.imghippo.com/files/Ee3ed1729434490.png" alt="UPI" class="w-10 h-10 mx-1.5" />
      <img src="https://i.imghippo.com/files/0qfF61729441941.png" alt="Visa" class="w-10 h-10 mx-1.5" />
      <img src="https://i.imghippo.com/files/DJMED1729434451.png" alt="Mastercard" class="w-10 h-10 mx-1.5" />
      <img src="https://i.imghippo.com/files/dYdmk1729442965.png" alt="Google Pay" class="w-10 h-10 mx-1.5" />
      <img src="https://i.imghippo.com/files/t84Rd1729443149.png" alt="Crypto" class="w-10 h-10 mx-1.5" />
      <img src="https://i.imghippo.com/files/QwzZm1729443014.png" alt="Solana" class="w-10 h-10 mx-1.5" />
    </div>
  </div>
</Footer>
