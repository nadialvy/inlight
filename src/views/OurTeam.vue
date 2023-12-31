<script setup>
import ElementBackground from "../components/common/ElementBackground.vue";
import OurTeamCard from "../components/ourTeam/OurTeamCard.vue";
import Footer from "../components/common/Footer.vue";
import NavBar from "../components/common/NavBar/NavBar.vue";
</script>

<template>
  <NavBar />
  <div
    class="relatie m-auto mt-20 max-w-sm sm:max-w-[540px] md:max-w-[668px] lg:mt-28 lg:max-w-[980px] xl:mt-40 xl:max-w-[1200px] 2xl:max-w-[1400px]"
  >
    <ElementBackground position="left" />
    <div class="z-50 lg:grid lg:grid-cols-2 lg:gap-x-5 xl:gap-x-10">
      <h2 class="leading-tight">About The Team Indonesia Timber Lighting</h2>
      <p class="my-4 text-gray-500 opacity-80 lg:my-0">
        Inlight Lighting consists of a team of makers and designers based in
        Currumbin, Queensland. We design and craft bespoke timber lighting with
        a growing collection of pendant and wall light designs. We have been
        crafting our timber pendants since 2018 and look forward to continuing
        to offer the highest quality timber lighting.
      </p>
    </div>
  </div>
  <img
    src="/ourTeam/ourteam.png"
    alt="our team"
    class="mt-16 w-full object-cover 2xl:h-[60vh]"
  />

  <div
    class="relatie m-auto mt-16 max-w-sm sm:max-w-[540px] md:max-w-[668px] lg:max-w-[980px] xl:max-w-[1200px] 2xl:max-w-[1400px]"
  >
    <div class="lg:grid lg:grid-cols-2 lg:gap-x-10">
      <p class="text-gray-500">
        Our pendants are unique to the market, offering bespoke options and
        high-quality craftsmanship. Our lighting range is designed to suit both
        residential and commercial projects and can be customised to complement
        many interior styles and budgets.
      </p>
      <p class="mt-6 text-gray-500 lg:mt-0">
        Our design office and dedicated electrical workshop are located in
        Currumbin, Queensland. It is important to us to support other Australian
        businesses, so we have partnered with a select group of makers across
        Queensland and New South Wales who support us in crafting the timber for
        our pendants and creating our custom finishings. We are a registered
        Australian Made Campaign business.
      </p>
    </div>

    <div class="mt-16 lg:mt-24">
      <h2 class="text-center font-semibold">Meet Our Amazing Team</h2>
      <div class="lg:grid lg:grid-cols-2 lg:gap-4 xl:grid-cols-3 xl:gap-x-4">
        <OurTeamCard
          img="/ourTeam/team1.png"
          peopleName="Shari"
          peoplePosition="Director & Designer"
        />
        <OurTeamCard
          img="/ourTeam/team2.png"
          peopleName="Rury Paramita"
          peoplePosition="Product Manager"
        />
        <OurTeamCard
          img="/ourTeam/team3.png"
          peopleName="Shurki Wataka"
          peoplePosition="Head of Production"
        />
      </div>
    </div>

    <div class="mt-16 lg:mt-24">
      <h2 class="font-semibold">Collaboration</h2>
      <div class="lg:grid lg:grid-cols-2 lg:gap-x-10">
        <div>
          <p class="mt-4 text-gray-500">
            Our products are sustainably crafted to be enduring and of the
            highest quality. The use of solid timber is no coincidence, our team
            of experienced makers have been working with timber for over 2
            years. We are proud of our collaboration with Currumbin Woodworks,
            founded and run by Shari’s dad, Chris (top left above). Chris and
            Shari developed the original Inlight range of pendants together and
            now the team at Currumbin Woodworks craft our Tenn and Hollow
            Pendants, and complete all of our timber crafting and finishing work
            at their timber workshop in Currumbin. Timi (top right above) is on
            the workshop team and manages the Inlight timber production at
            Currumbin Woodworks.
          </p>
          <p class="mt-6 text-gray-500">
            With a deep understanding of the material, our team handcraft
            contemporary and high quality pendants from solid timber. Driven by
            a love for the craft, our makers create unique lighting which
            showcases the natural variations of Australian hardwood timbers.
          </p>
        </div>
        <img
          src="/ourTeam/collab.png"
          alt="collaboration"
          class="mt-4 w-full"
        />
      </div>
    </div>
  </div>
  <Footer />
</template>
