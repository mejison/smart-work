<template>
  <div class="container mx-auto">
    <Navbar />
    <section class="flex max-h-3 mb-17 main">
      <div class="flex align-center justify-center w-7/12">
        <img src="/assets/images/main.svg" class="image" alt="main-image" />
      </div>
      <div class="flex flex-col justify-center w-5/12">
        <h1
          class="font-bold leading-tight mb-5 text-custom-black title font-custom-bold"
        >
          Work Smart, <br />
          Not Hard.
        </h1>
        <p class="text-custom-gray-light max-w-2xl description">
          When your team needs to kick off a project, hire a new employee,
          deploy some code, review a sales contract, finalize next year's
          budget, measure an A/B test, plan your next office opening, and more,
          Slack has you covered.
        </p>
      </div>
    </section>
    <div class="separator mx-auto"></div>
    <section class="pb-20 features">
      <div class="text-center mt-10 mb-20">
        <h2 class="mb-2 font-bold text-custom-black title font-custom-bold">
          The hub for your team and your work
        </h2>
        <p class="text-custom-gray-light max-w-4xl mx-auto sub-title">
          Slack is a place where your team comes together to collaborate,
          important information can be <br />
          found by the right people, and your tools pipe in information when and
          where you need it.
        </p>
      </div>
      <div class="grid gap-2 grid-cols-2">
        <div
          v-for="(transport, index) in transports"
          :key="`transport-${index}`"
          class="mb-10"
        >
          <div class="flex items-center">
            <div>
              <img :src="transport.image" alt="image" />
            </div>
            <div class="max-w-xs">
              <h3 class="font-semibold text-custom-black mb-2 font-custom-bold">
                {{ transport.title }}
              </h3>
              <p
                class="text-custom-gray-light"
                v-html="transport.description"
              ></p>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  data() {
    return {
      transports: [
        {
          title: "Rapid Transport",
          image: "/assets/images/rapid-1.svg",
          description:
            "Integrate the <a href='#' class='text-custom-green-light'>latest technologies</a> with an innovative platform that’s always getting better and launching new features weekly. We fit your needs as you grow.",
        },
        {
          title: "Rapid Transport",
          image: "/assets/images/rapid-2.svg",
          description:
            "Integrate the <a href='#' class='text-custom-green-light'>latest technologies</a> with an innovative platform that’s always getting better and launching new features weekly. We fit your needs as you grow.",
        },
        {
          title: "Rapid Transport",
          image: "/assets/images/rapid-1.svg",
          description:
            "Integrate the <a href='#' class='text-custom-green-light'>latest technologies</a> with an innovative platform that’s always getting better and launching new features weekly. We fit your needs as you grow.",
        },
        {
          title: "Rapid Transport",
          image: "/assets/images/rapid-1.svg",
          description:
            "Integrate the <a href='#' class='text-custom-green-light'>latest technologies</a> with an innovative platform that’s always getting better and launching new features weekly. We fit your needs as you grow.",
        },
      ],
    };
  },
  head() {
    return {
      title: "Landkit",
    };
  },
};
</script>

<style>
.main .title {
  font-size: 70px;
}

.main .description {
  font-size: 20px;
}

.main .image {
  object-fit: contain;
  object-position: center 100px;
}

.features .title {
  font-size: 31px;
}

.features .sub-title {
  font-size: 19px;
}

.separator {
  opacity: 0.4;
  border: 1px solid #cfdae5;
  width: 72px;
}
</style>
