<script>
  // Import the required components if they are from other files
  export let Footer;
  export let FooterLinkGroup;
  export let FooterLink;
  export let FooterCopyright;
</script>

<Footer footerType="sitemap">
  <div class="bg-black text-white p-8 rounded-lg shadow-lg">
    <div class="flex flex-col md:flex-row gap-8 justify-center">
      
      <!-- Company Information -->
      <div class="flex flex-col items-center md:items-start flex-1">
        <img
          src="https://images-ext-1.discordapp.net/external/Fck1ccubcCLfJ_sL7BuIG3Q6c5uU_MFZ3XbEAme0jBQ/%3Fsize%3D512/https/cdn.discordapp.com/icons/876113814314164256/0e0f35f8cd793beefafbdec39382f1db.png"
          alt="Company Image"
        />
        <FooterCopyright
          spanClass="text-xs text-amber-200 sm:text-center"
          href="/"
        />
      </div>

      <!-- Magnimont Links Section -->
      <div class="flex flex-col space-y-2">
        <h2 class="text-amber-200 font-bold uppercase mb-2">Magnimont</h2>
        <FooterLinkGroup ulClass="space-y-2">
          <FooterLink href="/">About</FooterLink>
          <FooterLink href="https://forum.magnimont.com">Forum</FooterLink>
          <FooterLink href="https://host.magnimont.com">Hosting</FooterLink>
          <FooterLink href="/">Career</FooterLink>
        </FooterLinkGroup>
      </div>

      <!-- Socials Section -->
      <div class="flex flex-col space-y-2">
        <h2 class="text-amber-200 font-bold uppercase mb-2">Socials</h2>
        <FooterLinkGroup ulClass="space-y-2">
          <FooterLink href="https://discord.gg/magnimont-876113814314164256">Discord Server</FooterLink>
          <FooterLink href="https://www.linkedin.com/company/magnimont/">LinkedIn</FooterLink>
          <FooterLink href="https://github.com/Magnimont">GitHub</FooterLink>
          <FooterLink href="https://www.youtube.com/@Magnimont/videos">YouTube</FooterLink>
        </FooterLinkGroup>
      </div>

      <!-- Legal Section -->
      <div class="flex flex-col space-y-2">
        <h2 class="text-amber-200 font-bold uppercase mb-2">Legal</h2>
        <FooterLinkGroup ulClass="space-y-2">
          <FooterLink href="/privacy-policy">Privacy Policy</FooterLink>
          <FooterLink href="/">Licensing</FooterLink>
          <FooterLink href="/terms-of-service">Terms & Conditions</FooterLink>
        </FooterLinkGroup>
      </div>

      <!-- Payment Section -->
      <div class="flex flex-col space-y-2">
        <h2 class="text-amber-200 font-bold uppercase mb-2">Payments</h2>
        <FooterLinkGroup ulClass="space-y-2">
          <FooterLink href="/payment-methods">Payment Methods</FooterLink>
          <FooterLink href="/refund-policy">Refund Policy</FooterLink>
          <FooterLink href="/pricing">Pricing</FooterLink>
        </FooterLinkGroup>

        <!-- Payment Logos (example with some common payment logos) -->
        <div class="flex space-x-4 mt-4">
          <img
            class="h-8"
            src="https://upload.wikimedia.org/wikipedia/commons/4/41/Visa_Logo.png"
            alt="Visa"
          />
          <img
            class="h-8"
            src="https://upload.wikimedia.org/wikipedia/commons/0/04/Mastercard-logo.png"
            alt="MasterCard"
          />
          <img
            class="h-8"
            src="https://upload.wikimedia.org/wikipedia/commons/3/39/PayPal_logo.png"
            alt="PayPal"
          />
        </div>
      </div>
    </div>
  </div>
</Footer>

<style>
  /* Add custom styles if needed */
</style>
