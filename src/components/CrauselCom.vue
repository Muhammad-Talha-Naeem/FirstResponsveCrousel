<template>
  <div>
    <Splide :options="options" aria-label="My Favorite Images">
      <SplideSlide>
        <section class="text-gray-600 body-font">
          <div
            class="container mx-auto flex px-5 py-2 md:flex-row lg:flex-row flex-col-reverse items-center"
          >
            <div
              class="lg:flex-grow md:w-1/2 lg:pr-24 md:pr-16 flex flex-col md:items-start md:text-left mb-16 md:mb-0 items-center text-center"
            >
              <h1 class="title-font sm:text-4xl text-3xl mb-4 font-medium text-gray-900">
                Before they sold out readymade gluten
              </h1>
              <div>
                <p class="mb-8 leading-relaxed text-justify">
                  Copper mug try-hard pitchfork pour-over freegan heirloom neutra air
                  plant cold-pressed tacos poke beard tote bag. Heirloom echo park mlkshk
                  tote bag selvage hot chicken authentic tumeric truffaut hexagon try-hard
                  chambray.
                </p>
              </div>
              <div class="flex justify-center">
                <div
                  class="p-2 rounded focus:outline-none hover:bg-indigo-600 w-32 flex justify-around items-center"
                >
                  <font-awesome-icon icon="fas fa-cart-plus" />
                  <button class="text-gray-100 border-0 px-3 focus:outline-none text-lg">
                    Add cart
                  </button>
                </div>
                <div
                  class="ml-4 w-24 focus:outline-none hover:bg-indigo-600 rounded p-2 flex justify-around items-center"
                >
                  <font-awesome-icon icon="far fa-credit-card" />
                  <button
                    class="text-gray-100 border-0 px-3 focus:outline-none rounded text-lg"
                  >
                    Buy
                  </button>
                </div>
              </div>
            </div>
            <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6">
              <img
                class="object-cover object-center rounded"
                alt="hero"
                src="https://dummyimage.com/720x600/e8d8e8/0011ff.jpg&text=product+Image"
              />
            </div>
          </div>
        </section>
      </SplideSlide>
      <SplideSlide>
        <section class="text-gray-600 body-font">
          <div
            class="container mx-auto flex px-5 py-2 md:flex-row lg:flex-row flex-col-reverse items-center"
          >
            <div
              class="lg:flex-grow md:w-1/2 lg:pr-24 md:pr-16 flex flex-col md:items-start md:text-left mb-16 md:mb-0 items-center text-center"
            >
              <h1 class="title-font sm:text-4xl text-3xl mb-4 font-medium text-gray-900">
                Before they sold out readymade gluten
              </h1>
              <div>
                <p class="mb-8 leading-relaxed text-justify">
                  Copper mug try-hard pitchfork pour-over freegan heirloom neutra air
                  plant cold-pressed tacos poke beard tote bag. Heirloom echo park mlkshk
                  tote bag selvage hot chicken authentic tumeric truffaut hexagon try-hard
                  chambray.
                </p>
              </div>
              <div class="flex justify-center">
                <div
                  class="p-2 rounded focus:outline-none hover:bg-indigo-600 w-32 flex justify-around items-center"
                >
                  <font-awesome-icon icon="fas fa-cart-plus" />
                  <button class="text-gray-100 border-0 px-3 focus:outline-none text-lg">
                    Add cart
                  </button>
                </div>
                <div
                  class="ml-4 w-24 focus:outline-none hover:bg-indigo-600 rounded p-2 flex justify-around items-center"
                >
                  <font-awesome-icon icon="far fa-credit-card" />
                  <button
                    class="text-gray-100 border-0 px-3 focus:outline-none rounded text-lg"
                  >
                    Buy
                  </button>
                </div>
              </div>
            </div>
            <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6">
              <img
                class="object-cover object-center rounded"
                alt="hero"
                src="https://dummyimage.com/720x600/e8d8e8/0011ff.jpg&text=product+Image"
              />
            </div>
          </div>
        </section>
      </SplideSlide>
      <SplideSlide>
        <section class="text-gray-600 body-font">
          <div
            class="container mx-auto flex px-5 py-2 md:flex-row lg:flex-row flex-col-reverse items-center"
          >
            <div
              class="lg:flex-grow md:w-1/2 lg:pr-24 md:pr-16 flex flex-col md:items-start md:text-left mb-16 md:mb-0 items-center text-center"
            >
              <h1 class="title-font sm:text-4xl text-3xl mb-4 font-medium text-gray-900">
                Before they sold out readymade gluten
              </h1>
              <div>
                <p class="mb-8 leading-relaxed text-justify">
                  Copper mug try-hard pitchfork pour-over freegan heirloom neutra air
                  plant cold-pressed tacos poke beard tote bag. Heirloom echo park mlkshk
                  tote bag selvage hot chicken authentic tumeric truffaut hexagon try-hard
                  chambray.
                </p>
              </div>
              <div class="flex justify-center">
                <div
                  class="p-2 rounded focus:outline-none hover:bg-indigo-600 w-32 flex justify-around items-center"
                >
                  <font-awesome-icon icon="fas fa-cart-plus" />
                  <button class="text-gray-100 border-0 px-3 focus:outline-none text-lg">
                    Add cart
                  </button>
                </div>
                <div
                  class="ml-4 w-24 focus:outline-none hover:bg-indigo-600 rounded p-2 flex justify-around items-center"
                >
                  <font-awesome-icon icon="far fa-credit-card" />
                  <button
                    class="text-gray-100 border-0 px-3 focus:outline-none rounded text-lg"
                  >
                    Buy
                  </button>
                </div>
              </div>
            </div>
            <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6">
              <img
                class="object-cover object-center rounded"
                alt="hero"
                src="https://dummyimage.com/720x600/e8d8e8/0011ff.jpg&text=product+Image"
              />
            </div>
          </div>
        </section>
      </SplideSlide>
    </Splide>
  </div>
</template>

<script>
import { defineComponent } from "vue";
import { Splide, SplideSlide } from "@splidejs/vue-splide";

export default defineComponent({
  components: {
    Splide,
    SplideSlide,
  },

  setup() {
    const options = {
      rewind: true,
      gap: "1rem",
    };
    return { options };
  },
});
</script>
