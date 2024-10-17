<script>
import { MetaTags } from "svelte-meta-tags";
</script>

<!-- <Nav /> Navbar -->

<main class="px-8 py-16 text-gray-900 text-center"> <!-- Center the text using text-center -->
  <h1 class="privacy-heading mb-6 golden-text">Privacy Policy</h1>

  <p class="policy-text mb-4">
    At Magnimont™, we respect your privacy and are committed to protecting any personal information you may share with us. This Privacy Policy explains what personal data we collect, how we use it, and the steps we take to ensure it is protected.
  </p>

  <h2 class="policy-subheading mb-4">1. Information We Collect</h2>
  <p class="policy-text mb-4">
    We collect the following types of information when you interact with our website:
  </p>
  <ul class="policy-text list-disc list-inside mb-6">
    <li>Personal identification information (such as name, email address, phone number)</li>
    <li>Usage data (such as browsing history, preferences, and interactions)</li>
    <li>Technical data (such as IP address, browser type, and device information)</li>
  </ul>

  <h2 class="policy-subheading mb-4">2. How We Use Your Information</h2>
  <p class="policy-text mb-4">
    We may use your personal information for the following purposes:
  </p>
  <ul class="policy-text list-disc list-inside mb-6">
    <li>To improve our website and services</li>
    <li>To communicate with you regarding updates, offers, and customer support</li>
    <li>To personalize your experience on our platform</li>
    <li>To ensure the security of our services</li>
  </ul>

  <h2 class="policy-subheading mb-4">3. Data Protection and Security</h2>
  <p class="policy-text mb-4">
    We implement appropriate technical and organizational security measures to protect your data from unauthorized access, disclosure, alteration, or destruction.
  </p>

  <h2 class="policy-subheading mb-4">4. Sharing Your Information</h2>
  <p class="policy-text mb-4">
    We do not sell or share your personal data with third parties for marketing purposes. However, we may share your information with trusted service providers to assist in delivering services to you, under strict confidentiality agreements.
  </p>

  <h2 class="policy-subheading mb-4">5. Your Data Protection Rights</h2>
  <p class="policy-text mb-4">
    You have the right to request access to, correction, or deletion of your personal information. You can also withdraw your consent to data processing at any time. To exercise your rights, contact us at <a href="mailto:hi@magnimont.com" class="text-amber-500">hi@magnimont.com</a>.
  </p>

  <h2 class="policy-subheading mb-4">6. Changes to this Privacy Policy</h2>
  <p class="policy-text mb-4">
    We may update this Privacy Policy periodically to reflect changes in our practices or applicable laws. The latest version will always be available on our website.
  </p>

  <h2 class="policy-subheading mb-4">7. Contact Us</h2>
  <p class="policy-text mb-4">
    If you have any questions or concerns about this Privacy Policy, please contact us at <a href="mailto:hi@magnimont.com" class="text-amber-500">hi@magnimont.com</a> or call us at <a href="tel:+91 8076974315" class="text-amber-500">+91 8076974315</a>.
  </p>
</main>
<MetaTags
  title="Magnimont | Privacy Policy"
  description="Magnimont description metatag"
  canonical="https://www.canonical.ie/"
  openGraph={{
    url: "https://www.url.ie/a",
    title: "Magnimont | Privacy Policy",
    description: "Magnimont is a leading digital agency specializing in custom web development, AI solutions, and tailored software. We craft innovative websites, intelligent chatbots, Discord bots, and custom applications to drive growth for businesses across industries. Our experts blend cutting-edge technologies with creative ingenuity to deliver digital experiences that captivate users and propel your brand forward.",
    images: [
      {
        url: "%sveltekit.assets%/favico.svg",
        width: 100,
        height: 100,
        alt: "Og Image Alt",
      },
    ],
    siteName: "Magnimont | Privacy Policy",
  }}
  twitter={{
    handle: "@magnimont",
    site: "@magnimont",
    cardType: "https://i.imgur.com/aTa8bjq.png",
    title: "Magnimont | Privacy Policy",
    description: "Magnimont is a leading digital agency specializing in custom web development, AI solutions, and tailored software. We craft innovative websites, intelligent chatbots, Discord bots, and custom applications to drive growth for businesses across industries. Our experts blend cutting-edge technologies with creative ingenuity to deliver digital experiences that captivate users and propel your brand forward.",
    image: "%sveltekit.assets%/favico.svg",
    imageAlt: "https://i.imgur.com/aTa8bjq.png",
  }}
MetaTags/>

<style>
  main {
    background-color: #000000;
  }

  .privacy-heading {
    font-family: ui-sans-serif, system-ui, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
    font-weight: 700;
     color:aliceblue;/* The specified color */
    font-size: 44px;
    line-height: 72px;
    margin-bottom: 40px;
    text-align: center;
  }

  .policy-text {
    font-family: 'Inter', "system-ui", sans-serif;
    font-weight: 400;
    
color:rgb(163, 163, 163); /* The specified text color */
    font-size: 16px;
    line-height: 24px;
    text-align: center; /* Centering the text */
  }

  .policy-subheading {
    font-family: 'Inter', "system-ui", sans-serif;
    font-weight: 600;
    color: whitesmoke; /* Subheading color */
    font-size: 24px;
    line-height: 32px;
    margin-top: 32px;
    text-align: center;
  }

  a {
    text-decoration: underline;
    color: #ffecb3;
  }

  ul {
    list-style-position: inside;
    padding-left: 0;
  }

  .golden-text {
    background: linear-gradient(to bottom, #cfc09f 27%, #ffecb3 40%, #3a2c0f 78%);
    -webkit-background-clip: text;
    background-clip: text;
    -webkit-text-fill-color: transparent;
    color: transparent;
    position: relative;
  }
</style>
