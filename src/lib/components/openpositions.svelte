<script>
  // OpenPositions.svelte
  export let positions = [
    {
      title: "Backend Developer",
      location: "Remote Location",
      description:
        "Join our team of backend developers and help us build the next generation of our product. Should have experience with Node.js, Express...",
      requirements: "None",
      image: "/images/backend.JPG",
    },
  ];
</script>

<section class="py-16 px-4">
  <h1 class="text-4xl font-bold text-center mb-12 golden-text">
    Open positions
  </h1>

  <div
    class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 max-w-7xl mx-auto"
  >
    {#each positions as position}
      <div
        class="bg-white rounded-lg overflow-hidden shadow-lg transition-transform hover:-translate-y-2"
      >
        <img
          src={position.image}
          alt={position.title}
          class="w-full h-48 object-cover"
        />
        <div class="p-6">
          <h3 class="text-xl font-bold mb-2 text-[#1a1a1a]">
            {position.title}
          </h3>
          <p class="text-gray-600 mb-4">{position.location}</p>
          <p class="text-gray-700 mb-4 line-clamp-3">{position.description}</p>
          <a href="https://forms.gle/oENrR24zutvBgWpa6"
            ><button
              class="bg-blue-600 text-white px-6 py-2 rounded-full hover:bg-blue-700 transition-colors"
            >
              Apply Now
            </button></a
          >
        </div>
      </div>
    {/each}
  </div>
</section>

<style>
  .golden-text {
    background: linear-gradient(
      to bottom,
      #cfc09f 27%,
      #ffecb3 40%,
      #3a2c0f 78%
    );
    -webkit-background-clip: text;
    background-clip: text;
    -webkit-text-fill-color: transparent;
    color: transparent;
  }
</style>
