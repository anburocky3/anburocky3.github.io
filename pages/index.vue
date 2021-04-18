<template>
  <div class="bg-gray-900 selection:text-yellow-500">
    <section id="hero-section" class="p-0 sm:pt-24 container mx-auto">
      <!-- Left section -->
      <div class="relative hidden sm:block">
        <div
          class="absolute left-10 top-40 flex flex-col space-y-6 items-center text-white"
        >
          <a
            :href="social.facebook"
            class="hover:text-yellow-500 cursor-pointer"
            target="_blank"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              xmlns:xlink="http://www.w3.org/1999/xlink"
              aria-hidden="true"
              class="w-6 h-6"
              viewBox="0 0 32 32"
            >
              <path
                d="M19.254 2C15.312 2 13 4.082 13 8.826V13H8v5h5v12h5V18h4l1-5h-5V9.672C18 7.885 18.583 7 20.26 7H23V2.205C22.526 2.141 21.145 2 19.254 2z"
                fill="currentColor"
              ></path>
            </svg>
          </a>
          <a
            :href="social.twitter"
            class="hover:text-yellow-500 cursor-pointer"
            target="_blank"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              xmlns:xlink="http://www.w3.org/1999/xlink"
              aria-hidden="true"
              class="w-6 h-6"
              viewBox="0 0 32 32"
            >
              <path
                d="M28 8.559a9.813 9.813 0 0 1-2.828.773a4.94 4.94 0 0 0 2.164-2.723a9.92 9.92 0 0 1-3.125 1.196a4.924 4.924 0 0 0-8.52 3.367c0 .387.043.762.13 1.121A13.957 13.957 0 0 1 5.67 7.148a4.885 4.885 0 0 0-.667 2.477c0 1.707.867 3.215 2.191 4.098a4.895 4.895 0 0 1-2.23-.618v.063a4.922 4.922 0 0 0 3.95 4.828a4.902 4.902 0 0 1-2.224.086a4.932 4.932 0 0 0 4.598 3.422A9.875 9.875 0 0 1 4 23.539a13.924 13.924 0 0 0 7.547 2.215c9.058 0 14.012-7.504 14.012-14.012c0-.21-.008-.426-.016-.637A10.085 10.085 0 0 0 28 8.56z"
                fill="currentColor"
              ></path>
            </svg>
          </a>
          <a
            :href="social.linkedin"
            class="hover:text-yellow-500 cursor-pointer"
            target="_blank"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              xmlns:xlink="http://www.w3.org/1999/xlink"
              aria-hidden="true"
              class="w-6 h-6"
              viewBox="0 0 32 32"
            >
              <path
                d="M8.643 4A2.641 2.641 0 0 0 6 6.64C6 8.1 7.183 9.31 8.64 9.31c1.459 0 2.643-1.21 2.643-2.668A2.64 2.64 0 0 0 8.643 4zm12.892 7c-2.219 0-3.488 1.16-4.098 2.314h-.064v-2.003H13V26h4.557v-7.271c0-1.916.144-3.768 2.515-3.768c2.337 0 2.371 2.185 2.371 3.889V26H27v-8.068C27 13.984 26.151 11 21.535 11zm-15.172.31V26h4.56V11.31h-4.56z"
                fill="currentColor"
              ></path>
            </svg>
          </a>
          <a
            :href="social.github"
            class="hover:text-yellow-500 cursor-pointer"
            target="_blank"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              xmlns:xlink="http://www.w3.org/1999/xlink"
              aria-hidden="true"
              class="w-6 h-6"
              viewBox="0 0 32 32"
            >
              <path
                fill-rule="evenodd"
                d="M16 4C9.371 4 4 9.371 4 16c0 5.3 3.438 9.8 8.207 11.387c.602.11.82-.258.82-.578c0-.286-.011-1.04-.015-2.04c-3.34.723-4.043-1.609-4.043-1.609c-.547-1.387-1.332-1.758-1.332-1.758c-1.09-.742.082-.726.082-.726c1.203.086 1.836 1.234 1.836 1.234c1.07 1.836 2.808 1.305 3.492 1c.11-.777.422-1.305.762-1.605c-2.664-.301-5.465-1.332-5.465-5.93c0-1.313.469-2.383 1.234-3.223c-.121-.3-.535-1.523.117-3.175c0 0 1.008-.32 3.301 1.23A11.487 11.487 0 0 1 16 9.805c1.02.004 2.047.136 3.004.402c2.293-1.55 3.297-1.23 3.297-1.23c.656 1.652.246 2.875.12 3.175c.77.84 1.231 1.91 1.231 3.223c0 4.61-2.804 5.621-5.476 5.922c.43.367.812 1.101.812 2.219c0 1.605-.011 2.898-.011 3.293c0 .32.214.695.824.578C24.566 25.797 28 21.3 28 16c0-6.629-5.371-12-12-12z"
                fill="currentColor"
              ></path>
            </svg>
          </a>
        </div>
      </div>

      <div class="flex justify-between">
        <div class="p-10 pb-16 sm:pl-36 max-w-xl mt-20">
          <span class="text-yellow-400 text-xl font-weight">Hi, I am</span>
          <h1
            class="mt-2 font-weight text-6xl text-white cursor-pointer font-lato"
          >
            Anbuselvan
            <!-- <svg
              xmlns="http://www.w3.org/2000/svg"
              xmlns:xlink="http://www.w3.org/1999/xlink"
              aria-hidden="true"
              role="img"
              class="ml-2 w-8 h-8 inline-block hover:text-yellow-500"
              preserveAspectRatio="xMidYMid meet"
              viewBox="0 0 256 256"
            >
              <path
                d="M218.472 104.988l-20-34.64a26.002 26.002 0 0 0-45.597 1.023l-19.044-32.985a25.987 25.987 0 0 0-45.906 1.666A26 26 0 0 0 46.156 70.53l9.055 15.683a25.979 25.979 0 0 0-23.696 38.958l38 65.818a86 86 0 1 0 148.957-86zm-3 62.153a74 74 0 0 1-135.565 17.847l-38-65.818a14 14 0 0 1 24.249-14l18 31.178a6.136 6.136 0 0 0 .41.612c.046.059.093.115.14.172q.167.206.349.394c.05.052.1.105.152.155a6.018 6.018 0 0 0 .529.455c.019.015.04.026.058.04a6.004 6.004 0 0 0 .527.345c.065.038.131.072.197.108q.222.118.452.218c.064.028.128.057.193.083a6.083 6.083 0 0 0 .65.216c.028.007.056.011.083.018a6.007 6.007 0 0 0 .601.118c.07.01.14.017.21.025c.175.019.35.03.524.034c.043 0 .085.008.127.008c.021 0 .041-.004.062-.004a5.97 5.97 0 0 0 .694-.045c.018-.002.037-.007.056-.01a5.95 5.95 0 0 0 .632-.123c.067-.017.133-.037.199-.056q.254-.072.503-.169c.064-.025.129-.048.192-.075a5.993 5.993 0 0 0 2.853-8.52l-38-65.818a14 14 0 1 1 24.248-14l34 58.89a6 6 0 1 0 10.392-6l-26-45.033a14 14 0 0 1 24.25-14l29.997 51.957l.002.005l7.193 12.457a46.019 46.019 0 0 0-11.834 59.504a6 6 0 1 0 10.392-6a34 34 0 0 1 12.446-46.445a6.04 6.04 0 0 0 .955-.685l.007-.005a5.952 5.952 0 0 0 .795-.85l.004-.005a5.98 5.98 0 0 0 .61-.979l.01-.02a6.034 6.034 0 0 0 .412-1.093l.003-.006c.014-.055.022-.11.035-.164c.032-.135.065-.27.088-.408c.01-.061.013-.123.022-.184c.018-.133.036-.266.045-.4c.003-.05.002-.1.003-.15a5.98 5.98 0 0 0 .007-.44c0-.034-.006-.068-.007-.102a5.938 5.938 0 0 0-.04-.483c-.003-.027-.01-.054-.014-.082a5.947 5.947 0 0 0-.09-.494c-.008-.033-.02-.066-.028-.1a5.853 5.853 0 0 0-.132-.463c-.022-.064-.05-.127-.074-.19c-.045-.12-.088-.24-.141-.358q-.123-.273-.274-.535L163.83 90.345a14 14 0 0 1 24.249-13.997l20 34.64a73.511 73.511 0 0 1 7.393 56.153zm-129.448 76.28a5.999 5.999 0 0 1-8.35 1.513a116.964 116.964 0 0 1-34.87-37.943a6 6 0 0 1 10.392-6a105.05 105.05 0 0 0 31.317 34.081a6 6 0 0 1 1.511 8.35zM170 30.996A6 6 0 0 1 176 25h.006a58.205 58.205 0 0 1 50.216 29.004a6 6 0 1 1-10.393 6A46.17 46.17 0 0 0 175.994 37A6 6 0 0 1 170 30.995z"
                fill="currentColor"
              ></path>
            </svg> -->
          </h1>
          <h4 class="mt-5 font-semibold text-2xl text-white">
            Creative Programmer
          </h4>
          <p class="mt-3 text-gray-300 font-weight">
            A hyperactive human following his passion. Have invented few
            innovative products. Helping the open source communities for an
            decade. Love to teach others.
          </p>

          <div class="mt-10 space-x-4">
            <a
              href="#"
              class="bg-yellow-500 rounded-full py-3 px-8 text-white font-bold text-sm hover:bg-yellow-600 shadow-lg"
              >Download CV</a
            >
            <a
              href="#"
              class="border-2 border-yellow-500 rounded-full py-3 px-8 text-yellow-500 font-bold text-sm hover:bg-yellow-600 hover:text-white shadow-lg"
              >Contact Me</a
            >
          </div>
        </div>
        <!-- Right section -->
        <div class="hidden xl:block">
          <!-- <img
            class="max-w-sm mr-20"
            src="https://stalinani.com/assets/images/header/s-m-right.png"
            alt="s"
          /> -->
          <img
            class="-mt-24 max-w-md mr-20"
            src="/img/anbuselvan-rocky.png"
            alt="s"
          />
        </div>
      </div>
    </section>

    <div class="relative max-w-3xl mx-auto hidden sm:block">
      <div
        class="absolute -top-16 bg-pink-900 px-16 py-8 rounded-full flex space-x-6 text-white shadow-lg"
      >
        <div class="flex items-center space-x-4">
          <div
            class="mt-2 rounded-full bg-yellow-500 flex items-center justify-center h-16 w-16"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              xmlns:xlink="http://www.w3.org/1999/xlink"
              aria-hidden="true"
              role="img"
              class="iconify iconify--fa-solid"
              width="24"
              height="32"
              preserveAspectRatio="xMidYMid meet"
              viewBox="0 0 384 512"
            >
              <path
                d="M97.12 362.63c-8.69-8.69-4.16-6.24-25.12-11.85c-9.51-2.55-17.87-7.45-25.43-13.32L1.2 448.7c-4.39 10.77 3.81 22.47 15.43 22.03l52.69-2.01L105.56 507c8 8.44 22.04 5.81 26.43-4.96l52.05-127.62c-10.84 6.04-22.87 9.58-35.31 9.58c-19.5 0-37.82-7.59-51.61-21.37zM382.8 448.7l-45.37-111.24c-7.56 5.88-15.92 10.77-25.43 13.32c-21.07 5.64-16.45 3.18-25.12 11.85c-13.79 13.78-32.12 21.37-51.62 21.37c-12.44 0-24.47-3.55-35.31-9.58L252 502.04c4.39 10.77 18.44 13.4 26.43 4.96l36.25-38.28l52.69 2.01c11.62.44 19.82-11.27 15.43-22.03zM263 340c15.28-15.55 17.03-14.21 38.79-20.14c13.89-3.79 24.75-14.84 28.47-28.98c7.48-28.4 5.54-24.97 25.95-45.75c10.17-10.35 14.14-25.44 10.42-39.58c-7.47-28.38-7.48-24.42 0-52.83c3.72-14.14-.25-29.23-10.42-39.58c-20.41-20.78-18.47-17.36-25.95-45.75c-3.72-14.14-14.58-25.19-28.47-28.98c-27.88-7.61-24.52-5.62-44.95-26.41c-10.17-10.35-25-14.4-38.89-10.61c-27.87 7.6-23.98 7.61-51.9 0c-13.89-3.79-28.72.25-38.89 10.61c-20.41 20.78-17.05 18.8-44.94 26.41c-13.89 3.79-24.75 14.84-28.47 28.98c-7.47 28.39-5.54 24.97-25.95 45.75c-10.17 10.35-14.15 25.44-10.42 39.58c7.47 28.36 7.48 24.4 0 52.82c-3.72 14.14.25 29.23 10.42 39.59c20.41 20.78 18.47 17.35 25.95 45.75c3.72 14.14 14.58 25.19 28.47 28.98C104.6 325.96 106.27 325 121 340c13.23 13.47 33.84 15.88 49.74 5.82a39.676 39.676 0 0 1 42.53 0c15.89 10.06 36.5 7.65 49.73-5.82zM97.66 175.96c0-53.03 42.24-96.02 94.34-96.02s94.34 42.99 94.34 96.02s-42.24 96.02-94.34 96.02s-94.34-42.99-94.34-96.02z"
                fill="currentColor"
              ></path>
            </svg>
          </div>
          <div>
            <h3 class="font-bold">8 Years Job</h3>
            <span class="text-yellow-500 font-semibold text-sm"
              >Experience</span
            >
          </div>
        </div>
        <div>
          <hr class="border-r border-opacity-30 h-full" />
        </div>

        <div class="flex items-center space-x-4">
          <div
            class="mt-2 rounded-full bg-yellow-500 flex items-center justify-center h-16 w-16"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              xmlns:xlink="http://www.w3.org/1999/xlink"
              aria-hidden="true"
              role="img"
              class="iconify iconify--clarity"
              width="32"
              height="32"
              preserveAspectRatio="xMidYMid meet"
              viewBox="0 0 36 36"
            >
              <path
                class="clr-i-outline clr-i-outline-path-1"
                d="M29.29 34H6.71A1.7 1.7 0 0 1 5 32.31V6.69A1.75 1.75 0 0 1 7 5h2v2H7v25h22V7h-2V5h2.25A1.7 1.7 0 0 1 31 6.69v25.62A1.7 1.7 0 0 1 29.29 34z"
                fill="currentColor"
              ></path>
              <path
                class="clr-i-outline clr-i-outline-path-2"
                d="M16.66 25.76L11.3 20.4a1 1 0 0 1 1.42-1.4l3.94 3.94l8.64-8.64a1 1 0 0 1 1.41 1.41z"
                fill="currentColor"
              ></path>
              <path
                class="clr-i-outline clr-i-outline-path-3"
                d="M26 11H10V7.33A2.34 2.34 0 0 1 12.33 5h1.79a4 4 0 0 1 7.75 0h1.79A2.34 2.34 0 0 1 26 7.33zM12 9h12V7.33a.33.33 0 0 0-.33-.33H20V6a2 2 0 0 0-4 0v1h-3.67a.33.33 0 0 0-.33.33z"
                fill="currentColor"
              ></path>
            </svg>
          </div>
          <div>
            <h3 class="font-bold">500+ Projects</h3>
            <span class="text-yellow-500 font-semibold text-sm"
              >Experience</span
            >
          </div>
        </div>
        <div>
          <hr class="border-r border-opacity-30 h-full" />
        </div>
        <div class="flex items-center space-x-4">
          <div
            class="mt-2 rounded-full bg-yellow-500 flex items-center justify-center h-16 w-16"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              xmlns:xlink="http://www.w3.org/1999/xlink"
              aria-hidden="true"
              role="img"
              class="iconify iconify--ic"
              width="32"
              height="32"
              preserveAspectRatio="xMidYMid meet"
              viewBox="0 0 24 24"
            >
              <path
                d="M11 23.59v-3.6c-5.01-.26-9-4.42-9-9.49C2 5.26 6.26 1 11.5 1S21 5.26 21 10.5c0 4.95-3.44 9.93-8.57 12.4l-1.43.69zM11.5 3C7.36 3 4 6.36 4 10.5S7.36 18 11.5 18H13v2.3c3.64-2.3 6-6.08 6-9.8C19 6.36 15.64 3 11.5 3zm-1 11.5h2v2h-2zm2-1.5h-2c0-3.25 3-3 3-5c0-1.1-.9-2-2-2s-2 .9-2 2h-2c0-2.21 1.79-4 4-4s4 1.79 4 4c0 2.5-3 2.75-3 5z"
                fill="currentColor"
              ></path>
            </svg>
          </div>
          <div>
            <h3 class="font-bold">Online Help</h3>
            <span class="text-yellow-500 font-semibold text-sm">Facebook</span>
          </div>
        </div>
      </div>
    </div>

    <!-- exp card -->
    <section class="bg-indigo-900 py-16 sm:pt-48 sm:pb-32 px-10 text-white">
      <div
        class="flex flex-col sm:flex-row items-center jusstify-start sm:justify-evenly space-y-10 sm:space-y-0"
      >
        <div class="bg-white p-1 max-w-md">
          <!-- src="https://www.cyberdudenetworks.com/assets/img/training/authors/anbuselvan-rocky.png" -->
          <img
            class="object-cover object-center"
            src="/img/anbu-2.jpg"
            alt="Anbuselvan Rocky"
          />
        </div>
        <div class="max-w-md">
          <h6 class="font-semibold text-xl text-yellow-500">My Intro</h6>
          <h2
            class="text-4xl font-black font-lato"
          >
            About Me
          </h2>
          <p class="mt-4 text-sm tracking-wide">
            Hello My name is Anbuselvan Annamalai, I have been coding for an
            decade & have tried dozens of tech stacks. Have created several
            public helping apps such as
            <a
              href="#"
              class="text-yellow-500 hover:text-yellow-600 font-semibold"
              >Chennaities</a
            >,
            <a
              href="#"
              class="text-yellow-500 hover:text-yellow-600 font-semibold"
            >
              Boo Music Player</a
            >,
            <a
              href="#"
              class="text-yellow-500 hover:text-yellow-600 font-semibold"
            >
              Avadi City.
            </a>
            If you so curious, give it a try.
            <br />
            <br />
            Have developed few smart prototypes such as
            <a
              href="#"
              class="text-yellow-500 hover:text-yellow-600 font-semibold"
              >SMAC</a
            >
            systems. Currently learning new stuffs and
            <a
              href="#"
              class="text-yellow-500 hover:text-yellow-600 font-semibold"
              >teaching the community</a
            >.
          </p>

          <div class="mt-8">
            <div class="font-semibold text-sm space-y-3">
              <div class="flex">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  class="h-5 w-5 text-yellow-500 mr-2"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z"
                  />
                </svg>
                <span>Name</span>
                <span class="px-4 sm:px-20">:</span>
                <span
                  ><a
                    href="http://www.google.com/search?q=Anbuselvan+Rocky"
                    target="_blank"
                    >Anbuselvan</a
                  ></span
                >
              </div>
              <div class="flex">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  class="h-5 w-5 text-yellow-500 mr-2"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"
                  />
                </svg>
                <span>Phone</span>
                <span class="px-4 sm:px-20">:</span>
                <span><a href="tel:918939738801">+91 8939738801</a></span>
              </div>

              <div class="flex">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  class="h-5 w-5 text-yellow-500 mr-2"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"
                  />
                </svg>
                <span>E-mail</span>
                <span class="px-4 sm:px-20">:</span>
                <span
                  ><a href="mailto:anbu@cyberdudenetworks.com"
                    >anbuceo@gmail.com</a
                  ></span
                >
              </div>
            </div>
          </div>

          <div class="mt-8">
            <h4 class="font-bold text-xl">My Interest</h4>
            <div class="mt-4 flex items-center space-x-10">
              <a href="#" class="cursor-pointer">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  class="h-7 w-7 text-yellow-500 inline-block mr-1 hover:animate-spin"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M9 19V6l12-3v13M9 19c0 1.105-1.343 2-3 2s-3-.895-3-2 1.343-2 3-2 3 .895 3 2zm12-3c0 1.105-1.343 2-3 2s-3-.895-3-2 1.343-2 3-2 3 .895 3 2zM9 10l12-3"
                  />
                </svg>

                <span class="font-semibold text-sm">Music</span>
              </a>
              <a href="#" class="cursor-pointer">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  class="h-7 w-7 text-yellow-500 inline-block mr-1 hover:animate-spin"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M21 13.255A23.931 23.931 0 0112 15c-3.183 0-6.22-.62-9-1.745M16 6V4a2 2 0 00-2-2h-4a2 2 0 00-2 2v2m4 6h.01M5 20h14a2 2 0 002-2V8a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"
                  />
                </svg>

                <span class="font-semibold text-sm">Travel</span>
              </a>
              <a href="#" class="cursor-pointer">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  class="h-7 w-7 text-yellow-500 inline-block mr-1 hover:animate-spin"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M7 4v16M17 4v16M3 8h4m10 0h4M3 12h18M3 16h4m10 0h4M4 20h16a1 1 0 001-1V5a1 1 0 00-1-1H4a1 1 0 00-1 1v14a1 1 0 001 1z"
                  />
                </svg>

                <span class="font-semibold text-sm">Movie</span>
              </a>
              <a href="#" class="cursor-pointer">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  class="h-7 w-7 text-yellow-500 inline-block mr-1 hover:animate-spin"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M3 9a2 2 0 012-2h.93a2 2 0 001.664-.89l.812-1.22A2 2 0 0110.07 4h3.86a2 2 0 011.664.89l.812 1.22A2 2 0 0018.07 7H19a2 2 0 012 2v9a2 2 0 01-2 2H5a2 2 0 01-2-2V9z"
                  />
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M15 13a3 3 0 11-6 0 3 3 0 016 0z"
                  />
                </svg>

                <span class="font-semibold text-sm">Photo</span>
              </a>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- end exp card -->

    <!-- exp area section -->
    <section class="p-10 sm:p-20 text-white bg-gray-800">
      <div class="text-center">
        <h4 class="text-lg text-yellow-500 font-semibold">Why Choose Me</h4>
        <h1
          class="mt-2 font-weight text-4xl text-white font-lato"
        >
          My Expertise Area
        </h1>
      </div>
      <div
        class="mt-10 flex flex-col sm:flex-row sm:justify-evenly space-x-0 sm:space-x-16 font-semibold text-sm px-0 sm:px-44"
      >
        <div class="w-full">
          <div class="mb-8">
            <div class="flex justify-between">
              <h4>Facebook Marketing</h4>
              <span>90%</span>
            </div>
            <div class="my-4 relative">
              <div
                class="overflow-hidden h-3 mb-4 text-xs flex rounded-full bg-yellow-200"
              >
                <div
                  style="width: 30%"
                  class="shadow-none flex flex-col text-center whitespace-nowrap text-white justify-center bg-yellow-500"
                ></div>
              </div>
            </div>
          </div>
          <div class="my-8">
            <div class="flex justify-between">
              <h4>Search Engine Optimizations</h4>
              <span>80%</span>
            </div>
            <div class="my-4 relative">
              <div
                class="overflow-hidden h-3 mb-4 text-xs flex rounded-full bg-yellow-200"
              >
                <div
                  style="width: 80%"
                  class="shadow-none flex flex-col text-center whitespace-nowrap text-white justify-center bg-yellow-500"
                ></div>
              </div>
            </div>
          </div>
          <div class="my-8">
            <div class="flex justify-between">
              <h4>Content Writing</h4>
              <span>90%</span>
            </div>
            <div class="my-4 relative">
              <div
                class="overflow-hidden h-3 mb-4 text-xs flex rounded-full bg-yellow-200"
              >
                <div
                  style="width: 90%"
                  class="shadow-none flex flex-col text-center whitespace-nowrap text-white justify-center bg-yellow-500"
                ></div>
              </div>
            </div>
          </div>
          <div class="my-8">
            <div class="flex justify-between">
              <h4>YouTube Marketing</h4>
              <span>85%</span>
            </div>
            <div class="my-4 relative">
              <div
                class="overflow-hidden h-3 mb-4 text-xs flex rounded-full bg-yellow-200"
              >
                <div
                  style="width: 85%"
                  class="shadow-none flex flex-col text-center whitespace-nowrap text-white justify-center bg-yellow-500"
                ></div>
              </div>
            </div>
          </div>
        </div>
        <div class="w-full">
          <div class="mb-8">
            <div class="flex justify-between">
              <h4>Affiliate Marketing</h4>
              <span>90%</span>
            </div>
            <div class="my-4 relative">
              <div
                class="overflow-hidden h-3 mb-4 text-xs flex rounded-full bg-yellow-200"
              >
                <div
                  style="width: 30%"
                  class="shadow-none flex flex-col text-center whitespace-nowrap text-white justify-center bg-yellow-500"
                ></div>
              </div>
            </div>
          </div>
          <div class="my-8">
            <div class="flex justify-between">
              <h4>Graphic Design</h4>
              <span>80%</span>
            </div>
            <div class="my-4 relative">
              <div
                class="overflow-hidden h-3 mb-4 text-xs flex rounded-full bg-yellow-200"
              >
                <div
                  style="width: 80%"
                  class="shadow-none flex flex-col text-center whitespace-nowrap text-white justify-center bg-yellow-500"
                ></div>
              </div>
            </div>
          </div>
          <div class="my-8">
            <div class="flex justify-between">
              <h4>Web UI Design</h4>
              <span>90%</span>
            </div>
            <div class="my-4 relative">
              <div
                class="overflow-hidden h-3 mb-4 text-xs flex rounded-full bg-yellow-200"
              >
                <div
                  style="width: 90%"
                  class="shadow-none flex flex-col text-center whitespace-nowrap text-white justify-center bg-yellow-500"
                ></div>
              </div>
            </div>
          </div>
          <div class="my-8">
            <div class="flex justify-between">
              <h4>Web Design</h4>
              <span>85%</span>
            </div>
            <div class="my-4 relative">
              <div
                class="overflow-hidden h-3 mb-4 text-xs flex rounded-full bg-yellow-200"
              >
                <div
                  style="width: 85%"
                  class="shadow-none flex flex-col text-center whitespace-nowrap text-white justify-center bg-yellow-500"
                ></div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- end exp area section -->

    <!-- qualification -->
    <section class="text-white bg-gray-900 p-10 sm:p-20">
      <div class="text-center">
        <h4 class="text-yellow-500 font-semibold">My Qualification</h4>
        <h1 class="mt-1 text-4xl font-bold font-lato">
          Exciting Journey
        </h1>
      </div>
      <div
        class="mt-10 grid grid-cols-1 sm:grid-cols-2 gap-0 sm:gap-4 px-0 sm:px-40 mx-auto"
      >
        <div class="">
          <div class="flex items-center space-x-4">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-10 w-10"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path d="M12 14l9-5-9-5-9 5 9 5z" />
              <path
                d="M12 14l6.16-3.422a12.083 12.083 0 01.665 6.479A11.952 11.952 0 0012 20.055a11.952 11.952 0 00-6.824-2.998 12.078 12.078 0 01.665-6.479L12 14z"
              />
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M12 14l9-5-9-5-9 5 9 5zm0 0l6.16-3.422a12.083 12.083 0 01.665 6.479A11.952 11.952 0 0012 20.055a11.952 11.952 0 00-6.824-2.998 12.078 12.078 0 01.665-6.479L12 14zm-4 6v-7.5l4-2.222"
              />
            </svg>
            <span class="text-xl font-black">Education</span>
          </div>

          <div class="py-8">
            <div class="flex space-x-8">
              <div class="relative">
                <div class="border border-yellow-500 rounded-full p-1">
                  <div class="w-4 h-4 rounded-full bg-yellow-500"></div>
                </div>
                <div class="h-12 w-px bg-yellow-500 absolute left-3"></div>
              </div>
              <div>
                <h1 class="text-lg font-bold">
                  Master of Business Administration
                </h1>
                <span class="font-semibold tracking-wide text-xs uppercase"
                  >Business, PG Degree</span
                >
                <div
                  class="mt-3 flex items-center text-yellow-500 font-medium text-xs space-x-2"
                >
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="h-4 w-4"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z"
                    />
                  </svg>
                  <span>2022-2014</span>
                </div>
              </div>
            </div>

            <div class="my-8 flex space-x-8">
              <div class="relative">
                <div class="border border-yellow-500 rounded-full p-1">
                  <div class="w-4 h-4 rounded-full bg-yellow-500"></div>
                </div>
                <div class="h-12 w-px bg-yellow-500 absolute left-3"></div>
              </div>
              <div>
                <h1 class="text-lg font-bold">
                  B. E (Computer Science & Engineering)
                </h1>
                <span class="font-semibold tracking-wide text-xs uppercase"
                  >Engineering, Under Graduate</span
                >
                <div
                  class="mt-3 flex items-center text-yellow-500 font-medium text-xs space-x-2"
                >
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="h-4 w-4"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z"
                    />
                  </svg>
                  <span>2013-2017</span>
                </div>
              </div>
            </div>

            <div class="my-8 flex space-x-8">
              <div class="relative">
                <div class="border border-yellow-500 rounded-full p-1">
                  <div class="w-4 h-4 rounded-full bg-yellow-500"></div>
                </div>
                <div class="h-12 w-px bg-yellow-500 absolute left-3"></div>
              </div>
              <div>
                <h1 class="text-lg font-bold">
                  Nazareth Matric. Hr. Sec. School
                </h1>
                <span class="font-semibold tracking-wide text-xs uppercase"
                  >Higher Schooling</span
                >
                <div
                  class="mt-3 flex items-center text-yellow-500 font-medium text-xs space-x-2"
                >
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="h-4 w-4"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z"
                    />
                  </svg>
                  <span>2000-2012</span>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="">
          <div class="flex items-center space-x-4">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-10 w-10"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M21 13.255A23.931 23.931 0 0112 15c-3.183 0-6.22-.62-9-1.745M16 6V4a2 2 0 00-2-2h-4a2 2 0 00-2 2v2m4 6h.01M5 20h14a2 2 0 002-2V8a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"
              />
            </svg>
            <span class="text-xl font-black">Experience</span>
          </div>

          <div class="py-8">
            <div class="flex space-x-8">
              <div class="relative">
                <div class="border border-yellow-500 rounded-full p-1">
                  <div class="w-4 h-4 rounded-full bg-yellow-500"></div>
                </div>
                <div class="h-12 w-px bg-yellow-500 absolute left-3"></div>
              </div>
              <div>
                <h1 class="text-lg font-bold">
                  Founder & Chief Executive Officer
                </h1>
                <span class="font-semibold tracking-wide text-xs uppercase"
                  >CyberDude Networks Pvt. Ltd.</span
                >
                <div
                  class="mt-3 flex items-center text-yellow-500 font-medium text-xs space-x-2"
                >
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="h-4 w-4"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z"
                    />
                  </svg>
                  <span>2016-current</span>
                </div>
              </div>
            </div>

            <div class="my-8 flex space-x-8">
              <div class="relative">
                <div class="border border-yellow-500 rounded-full p-1">
                  <div class="w-4 h-4 rounded-full bg-yellow-500"></div>
                </div>
                <div class="h-12 w-px bg-yellow-500 absolute left-3"></div>
              </div>
              <div>
                <h1 class="text-lg font-bold">Open Source Contributor</h1>
                <span class="font-semibold tracking-wide text-xs uppercase"
                  >Github Packages
                </span>
                <div
                  class="mt-3 flex items-center text-yellow-500 font-medium text-xs space-x-2"
                >
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="h-4 w-4"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z"
                    />
                  </svg>
                  <span>2011-2014</span>
                </div>
              </div>
            </div>

            <div class="mt-8 flex space-x-8">
              <div class="relative">
                <div class="border border-yellow-500 rounded-full p-1">
                  <div class="w-4 h-4 rounded-full bg-yellow-500"></div>
                </div>
                <div class="h-12 w-px bg-yellow-500 absolute left-3"></div>
              </div>
              <div>
                <h1 class="text-lg font-bold">
                  Former Intern @Google (Analytics)
                </h1>
                <span class="font-semibold tracking-wide text-xs uppercase"
                  >Google Inc.</span
                >
                <div
                  class="mt-3 flex items-center text-yellow-500 font-medium text-xs space-x-2"
                >
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="h-4 w-4"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z"
                    />
                  </svg>
                  <span>2011-2014</span>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- end qualification -->

    <!-- project hire -->
    <section class="p-10 sm:p-20 bg-indigo-900 text-white">
      <div
        class="flex flex-col sm:flex-row items-center space-y-8 sm:space-x-16"
      >
        <div>
          <img
            class="max-w-md rounded-full w-48 h-48 sm:w-64 sm:h-64 object-cover object-center"
            src="/img/anbu-pose.jpg"
            alt=""
          />
        </div>
        <div class="space-y-3">
          <h1 class="text-4xl font-bold">Have a Project on Your Mind?</h1>
          <p>
            Everyone has the next generation innovative idea through which they
            can introduce their ideas straight into the market. If you are so
            creative and would like to work with us, Let's Talk. <br /><br />
            Remember I'm always
            <strong class="text-yellow-500">free for those who need me</strong>,
          </p>
          <div class="py-5 text-center sm:text-left">
            <a
              href="#"
              class="py-3 px-6 rounded-full bg-white text-gray-900 font-semibold text-sm"
              >Contact Me
            </a>
          </div>
        </div>
      </div>
    </section>
    <!-- end project hire -->

    <!-- contact me -->
    <section class="p-10 sm:p-20 bg-gray-900 text-white">
      <div class="text-center">
        <h3 class="text-yellow-500 font-semibold">Contact Me</h3>
        <h1 class="mt-2 text-4xl font-bold">Get in Touch</h1>
      </div>

      <div
        class="mt-8 flex flex-col sm:flex-row max-w-4xl mx-auto space-y-10 sm:space-x-10"
      >
        <div class="w-full">
          <!-- Contact Form -->
          <form action="">
            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
              <div>
                <input
                  type="text"
                  placeholder="Name"
                  class="py-2 px-6 bg-gray-900 border border-white border-opacity-40 w-full"
                />
              </div>
              <div>
                <input
                  type="email"
                  placeholder="you@great.com"
                  class="py-2 px-6 bg-gray-900 border border-white border-opacity-40 w-full"
                />
              </div>
              <div class="sm:col-span-2">
                <input
                  type="text"
                  placeholder="Subject"
                  class="py-2 px-6 bg-gray-900 border border-white border-opacity-40 w-full"
                />
              </div>
              <div class="sm:col-span-2">
                <textarea
                  class="py-2 px-6 bg-gray-900 border border-white border-opacity-40 w-full resize-none"
                  placeholder="Message"
                  rows="8"
                >
                </textarea>
              </div>
            </div>

            <div class="mt-6">
              <button
                class="py-3 px-6 bg-yellow-500 rounded-full text-sm font-semibold hover:bg-yellow-600 w-full sm:w-auto"
              >
                Send Message
              </button>
            </div>
          </form>
        </div>
        <div class="w-full">
          <div class="flex space-x-6">
            <div
              class="mt-2 rounded-full bg-yellow-500 flex items-center justify-center h-12 w-12"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="h-5 w-5"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"
                />
              </svg>
            </div>

            <div class="font-medium">
              <h3 class="text-xl font-bold">Call Me</h3>
              <div class="mt-2 text-sm text-gray-400">
                <span class="">+91 8939738801</span> <br />
                <span class="">+91 8939738801</span>
              </div>
            </div>
          </div>

          <div class="my-8 flex space-x-6">
            <div
              class="mt-2 rounded-full bg-yellow-500 flex items-center justify-center h-12 w-12"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="h-5 w-5"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"
                />
              </svg>
            </div>

            <div class="font-medium">
              <h3 class="text-xl font-bold">E-mail</h3>
              <div class="mt-2 text-sm text-gray-400">
                <span class="">hello@anbuselvanrocky.in</span> <br />
                <span class="">anbu@cyberdudenetworks.com</span>
              </div>
            </div>
          </div>

          <div class="my-8 flex space-x-6">
            <div
              class="mt-2 rounded-full bg-yellow-500 flex items-center justify-center h-12 w-12"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="h-5 w-5"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"
                />
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"
                />
              </svg>
            </div>

            <div class="font-medium">
              <h3 class="text-xl font-bold">Location</h3>
              <div class="mt-2 text-sm text-gray-400">
                <span class="">Chennai, Tamil Nadu, India</span> <br />
                <span class="">Planet Earth</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- end contact me -->

    <!-- footer -->
    <footer class="bg-indigo-900 text-center text-white">
      <div class="py-10 px-10 max-w-xl mx-auto">
        <h1 class="text-2xl font-bold text-yellow-500">Anbuselvan Annamalai</h1>
        <p class="mt-3 text-sm text-gray-300 font-semibold">
          Thank you for taking your time and reading my site, If you have any
          suggestions or if you want to contact me for any reason. <br /><br />
          Feel free to contact me over the social networks.
        </p>

        <div class="mt-8 flex justify-center space-x-4">
          <div class="bg-yellow-500 rounded p-1">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              xmlns:xlink="http://www.w3.org/1999/xlink"
              aria-hidden="true"
              class="w-6 h-6"
              viewBox="0 0 32 32"
            >
              <path
                d="M19.254 2C15.312 2 13 4.082 13 8.826V13H8v5h5v12h5V18h4l1-5h-5V9.672C18 7.885 18.583 7 20.26 7H23V2.205C22.526 2.141 21.145 2 19.254 2z"
                fill="currentColor"
              ></path>
            </svg>
          </div>
          <div class="bg-yellow-500 rounded p-1">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              xmlns:xlink="http://www.w3.org/1999/xlink"
              aria-hidden="true"
              class="w-6 h-6"
              viewBox="0 0 32 32"
            >
              <path
                d="M28 8.559a9.813 9.813 0 0 1-2.828.773a4.94 4.94 0 0 0 2.164-2.723a9.92 9.92 0 0 1-3.125 1.196a4.924 4.924 0 0 0-8.52 3.367c0 .387.043.762.13 1.121A13.957 13.957 0 0 1 5.67 7.148a4.885 4.885 0 0 0-.667 2.477c0 1.707.867 3.215 2.191 4.098a4.895 4.895 0 0 1-2.23-.618v.063a4.922 4.922 0 0 0 3.95 4.828a4.902 4.902 0 0 1-2.224.086a4.932 4.932 0 0 0 4.598 3.422A9.875 9.875 0 0 1 4 23.539a13.924 13.924 0 0 0 7.547 2.215c9.058 0 14.012-7.504 14.012-14.012c0-.21-.008-.426-.016-.637A10.085 10.085 0 0 0 28 8.56z"
                fill="currentColor"
              ></path>
            </svg>
          </div>
          <div class="bg-yellow-500 rounded p-1">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              xmlns:xlink="http://www.w3.org/1999/xlink"
              aria-hidden="true"
              class="w-6 h-6"
              viewBox="0 0 32 32"
            >
              <path
                d="M8.643 4A2.641 2.641 0 0 0 6 6.64C6 8.1 7.183 9.31 8.64 9.31c1.459 0 2.643-1.21 2.643-2.668A2.64 2.64 0 0 0 8.643 4zm12.892 7c-2.219 0-3.488 1.16-4.098 2.314h-.064v-2.003H13V26h4.557v-7.271c0-1.916.144-3.768 2.515-3.768c2.337 0 2.371 2.185 2.371 3.889V26H27v-8.068C27 13.984 26.151 11 21.535 11zm-15.172.31V26h4.56V11.31h-4.56z"
                fill="currentColor"
              ></path>
            </svg>
          </div>
          <div class="bg-yellow-500 rounded p-1">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              xmlns:xlink="http://www.w3.org/1999/xlink"
              aria-hidden="true"
              class="w-6 h-6"
              viewBox="0 0 32 32"
            >
              <path
                fill-rule="evenodd"
                d="M16 4C9.371 4 4 9.371 4 16c0 5.3 3.438 9.8 8.207 11.387c.602.11.82-.258.82-.578c0-.286-.011-1.04-.015-2.04c-3.34.723-4.043-1.609-4.043-1.609c-.547-1.387-1.332-1.758-1.332-1.758c-1.09-.742.082-.726.082-.726c1.203.086 1.836 1.234 1.836 1.234c1.07 1.836 2.808 1.305 3.492 1c.11-.777.422-1.305.762-1.605c-2.664-.301-5.465-1.332-5.465-5.93c0-1.313.469-2.383 1.234-3.223c-.121-.3-.535-1.523.117-3.175c0 0 1.008-.32 3.301 1.23A11.487 11.487 0 0 1 16 9.805c1.02.004 2.047.136 3.004.402c2.293-1.55 3.297-1.23 3.297-1.23c.656 1.652.246 2.875.12 3.175c.77.84 1.231 1.91 1.231 3.223c0 4.61-2.804 5.621-5.476 5.922c.43.367.812 1.101.812 2.219c0 1.605-.011 2.898-.011 3.293c0 .32.214.695.824.578C24.566 25.797 28 21.3 28 16c0-6.629-5.371-12-12-12z"
                fill="currentColor"
              ></path>
            </svg>
          </div>
        </div>
      </div>
      <div class="py-4 bg-gray-900 text-gray-300 w-full text-sm">
        &copy; {{ new Date().getFullYear() }}
        <a href="#" class="font-semibold hover:text-yellow-500"
          >Coded with Love</a
        >
        - All Rights Reserved
      </div>
    </footer>
    <!-- end footer -->
  </div>
</template>

<script>
export default {
  data() {
    return {
      social: {
        facebook: 'https://facebook.com/anburocky3',
        twitter: 'https://twitter.com/anbuselvanrocky',
        linkedin: 'https://linkedin.com/anbuselvanrocky',
        github: 'https://github.com/anburocky3',
      },
    }
  },
}
</script>

<style>
</style>
