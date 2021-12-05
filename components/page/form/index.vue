<template>
  <div>
    <section class="relative pt-16 bg-blueGray-50">
      <div class="container mx-auto">
        <div class="flex flex-wrap items-center">
          <div
            class="w-10/12 md:w-6/12 lg:w-4/12 px-12 md:px-4 mr-auto ml-auto -mt-78"
          >
            <div
              class="min-h-screen flex flex-col items-center justify-center"
            >
              <div
                class="flex flex-col bg-white shadow-md px-4 sm:px-6 md:px-8 lg:px-10 py-8 rounded-3xl w-50 max-w-md"
              >
                <div
                  class="font-medium self-center text-xl sm:text-3xl text-gray-800"
                >
                  Create Menu Now
                </div>
                <div class="mt-4 self-center text-xl sm:text-sm text-gray-800">
                  Enter your credentials to get access account
                </div>

                <div class="mt-10">
                  <form action="#">
                    <div class="flex flex-col mb-5">
                      <label
                        for="email"
                        class="mb-1 text-xs tracking-wide text-gray-600"
                        >Name:</label
                      >
                      <div class="relative">
                        <div
                          class="inline-flex items-center justify-center absolute left-0 top-0 h-full w-10 text-gray-400"
                        >
                          <i class="fas fa-user text-blue-500"></i>
                        </div>

                        <input
                          id="email"
                          type="email"
                          name="email"
                          class="text-sm placeholder-gray-500 pl-10 pr-4 rounded-2xl border border-gray-400 w-full py-2 focus:outline-none focus:border-blue-400"
                          placeholder="Enter your name"
                        />
                      </div>
                    </div>
                    <div class="flex flex-col mb-5">
                      <label
                        for="email"
                        class="mb-1 text-xs tracking-wide text-gray-600"
                        >E-Mail Address:</label
                      >
                      <div class="relative">
                        <div
                          class="inline-flex items-center justify-center absolute left-0 top-0 h-full w-10 text-gray-400"
                        >
                          <i class="fas fa-at text-blue-500"></i>
                        </div>

                        <input
                          id="email"
                          type="email"
                          name="email"
                          class="text-sm placeholder-gray-500 pl-10 pr-4 rounded-2xl border border-gray-400 w-full py-2 focus:outline-none focus:border-blue-400"
                          placeholder="Enter your email"
                        />
                      </div>
                    </div>
                    <div class="flex flex-col mb-6">
                      <label
                        for="password"
                        class="mb-1 text-xs sm:text-sm tracking-wide text-gray-600"
                        >Password:</label
                      >
                      <div class="relative">
                        <div
                          class="inline-flex items-center justify-center absolute left-0 top-0 h-full w-10 text-gray-400"
                        >
                          <span>
                            <i class="fas fa-lock text-blue-500"></i>
                          </span>
                        </div>

                        <input
                          id="password"
                          type="password"
                          name="password"
                          class="text-sm placeholder-gray-500 pl-10 pr-4 rounded-2xl border border-gray-400 w-full py-2 focus:outline-none focus:border-blue-400"
                          placeholder="Enter your password"
                        />
                      </div>
                    </div>

                    <div class="flex w-full">
                      <button
                        type="submit"
                        class="flex mt-2 items-center justify-center focus:outline-none text-white text-sm sm:text-base bg-blue-500 hover:bg-blue-600 rounded-2xl py-2 w-full transition duration-150 ease-in"
                      >
                        <span class="mr-2 uppercase">Create Now</span>
                        <span>
                          <svg
                            class="h-6 w-6"
                            fill="none"
                            stroke-linecap="round"
                            stroke-linejoin="round"
                            stroke-width="2"
                            viewBox="0 0 24 24"
                            stroke="currentColor"
                          >
                            <path
                              d="M13 9l3 3m0 0l-3 3m3-3H8m13 0a9 9 0 11-18 0 9 9 0 0118 0z"
                            />
                          </svg>
                        </span>
                      </button>
                    </div>
                  </form>
                </div>
              </div>
              <div class="flex justify-center items-center mt-6">
                <a
                  href="#"
                  target="_blank"
                  class="inline-flex items-center text-gray-700 font-medium text-xs text-center"
                >
                  <span class="ml-2"
                    >You have an account?
                    <a href="#" class="text-xs ml-2 text-blue-500 font-semibold"
                      >Login here</a
                    ></span
                  >
                </a>
              </div>
            </div>
          </div>

          <div class="w-full md:w-6/12 px-4">
            <div class="flex flex-wrap">
              <div class="w-full md:w-6/12 px-4">
                <div class="relative flex flex-col mt-4">
                  <div class="px-4 py-5 flex-auto">
                    <div
                      class="text-blueGray-500 p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-white"
                    >
                      <i class="fas fa-sitemap"></i>
                    </div>
                    <h6 class="text-xl mb-1 font-semibold">CSS Components</h6>
                    <p class="mb-4 text-blueGray-500">
                      Notus JS comes with a huge number of Fully Coded CSS
                      components.
                    </p>
                  </div>
                </div>
                <div class="relative flex flex-col min-w-0">
                  <div class="px-4 py-5 flex-auto">
                    <div
                      class="text-blueGray-500 p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-white"
                    >
                      <i class="fas fa-drafting-compass"></i>
                    </div>
                    <h6 class="text-xl mb-1 font-semibold">
                      JavaScript Components
                    </h6>
                    <p class="mb-4 text-blueGray-500">
                      We also feature many dynamic components for React, NextJS,
                      Vue and Angular.
                    </p>
                  </div>
                </div>
              </div>
              <div class="w-full md:w-6/12 px-4">
                <div class="relative flex flex-col min-w-0 mt-4">
                  <div class="px-4 py-5 flex-auto">
                    <div
                      class="text-blueGray-500 p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-white"
                    >
                      <i class="fas fa-newspaper"></i>
                    </div>
                    <h6 class="text-xl mb-1 font-semibold">Pages</h6>
                    <p class="mb-4 text-blueGray-500">
                      This extension also comes with 3 sample pages. They are
                      fully coded so you can start working instantly.
                    </p>
                  </div>
                </div>
                <div class="relative flex flex-col min-w-0">
                  <div class="px-4 py-5 flex-auto">
                    <div
                      class="text-blueGray-500 p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-white"
                    >
                      <i class="fas fa-file-alt"></i>
                    </div>
                    <h6 class="text-xl mb-1 font-semibold">Documentation</h6>
                    <p class="mb-4 text-blueGray-500">
                      Built by developers for developers. You will love how easy
                      is to to work with Notus JS.
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <footer class="relative bg-blueGray-50 pt-8 pb-6 mt-2">
        <div class="container mx-auto px-4">
          <div
            class="flex flex-wrap items-center md:justify-between justify-center"
          >
            <div class="w-full md:w-6/12 px-4 mx-auto text-center">
              <div class="text-sm text-blueGray-500 font-semibold py-1">
                Made with
                <a
                  href="https://www.creative-tim.com/product/notus-js"
                  class="text-blueGray-500 hover:text-gray-800"
                  target="_blank"
                  >Notus JS</a
                >
                by
                <a
                  href="https://www.creative-tim.com"
                  class="text-blueGray-500 hover:text-blueGray-800"
                  target="_blank"
                >
                  Creative Tim</a
                >.
              </div>
            </div>
          </div>
        </div>
      </footer>
    </section>
  </div>
</template>
<script lang="ts">
import Vue from "vue";
export default Vue.extend({});
</script>
