<script setup>
//import { ref, reactive } from 'vue'
//import  from '.'

</script>

<template>
    <div class="">
        <header class="lg:w-[626px] h-[144px] hidden lg:block p-[30px] ml-auto mb-10 rounded-[16px] bg-white dark:bg-[#111111] ">
        <nav class="hidden lg:block">
          <ul class="flex ">
            <RouterLink to="/" :class="{ 'lg:text-white lg:dark:text-white lg:bg-gradient-to-r from-[#FA5252] to-[#DD2476]': $route.path === '/' }"
              class="w-full h-20 rounded-[10px]  cursor-pointer  font-poppins  bg-[#F3F6F6]  font-medium mx-2.5  text-xtiny text-gray-lite dark:text-[#A6A6A6]    justify-center flex flex-col items-center   transition-all duration-300 ease-in-out dark:hover:text-white dark:bg-[#212425] hover:text-white   hover:bg-gradient-to-r from-[#FA5252] to-[#DD2476]
              ">
              <span class="text-xl mb-1">
                <svg fill=currentColor height=1em stroke=currentColor stroke-width=0 viewBox="0 0 1024 1024" width=1em
                  xmlns=http://www.w3.org/2000/svg>
                  <path
                    d="M946.5 505L560.1 118.8l-25.9-25.9a31.5 31.5 0 0 0-44.4 0L77.5 505a63.9 63.9 0 0 0-18.8 46c.4 35.2 29.7 63.3 64.9 63.3h42.5V940h691.8V614.3h43.4c17.1 0 33.2-6.7 45.3-18.8a63.6 63.6 0 0 0 18.7-45.3c0-17-6.7-33.1-18.8-45.2zM568 868H456V664h112v204zm217.9-325.7V868H632V640c0-22.1-17.9-40-40-40H432c-22.1 0-40 17.9-40 40v228H238.1V542.3h-96l370-369.7 23.1 23.1L882 542.3h-96.1z">
                  </path>
                </svg>
            </span>
            Home
          </RouterLink>
          <RouterLink to="/resume" :class="{ 'lg:text-white lg:dark:text-white lg:bg-gradient-to-r from-[#FA5252] to-[#DD2476]': $route.path === '/resume' }"
            class="w-full h-20 rounded-[10px]  cursor-pointer  font-poppins  bg-[#F3F6F6]  font-medium mx-2.5  text-xtiny text-gray-lite dark:text-[#A6A6A6]    justify-center flex flex-col items-center   transition-all duration-300 ease-in-out dark:hover:text-white dark:bg-[#212425] hover:text-white   hover:bg-gradient-to-r from-[#FA5252] to-[#DD2476] ">
            <span class="text-xl mb-1">
              <svg fill=none height=1em stroke=currentColor stroke-width=0 viewBox="0 0 24 24" width=1em
                xmlns=http://www.w3.org/2000/svg>
                <path
                  d="M6 6C6 5.44772 6.44772 5 7 5H17C17.5523 5 18 5.44772 18 6C18 6.55228 17.5523 7 17 7H7C6.44771 7 6 6.55228 6 6Z"
                  fill=currentColor></path>
                <path
                  d="M6 10C6 9.44771 6.44772 9 7 9H17C17.5523 9 18 9.44771 18 10C18 10.5523 17.5523 11 17 11H7C6.44771 11 6 10.5523 6 10Z"
                  fill=currentColor></path>
                <path
                  d="M7 13C6.44772 13 6 13.4477 6 14C6 14.5523 6.44771 15 7 15H17C17.5523 15 18 14.5523 18 14C18 13.4477 17.5523 13 17 13H7Z"
                  fill=currentColor></path>
                <path
                  d="M6 18C6 17.4477 6.44772 17 7 17H11C11.5523 17 12 17.4477 12 18C12 18.5523 11.5523 19 11 19H7C6.44772 19 6 18.5523 6 18Z"
                  fill=currentColor></path>
                <path
                  d="M2 4C2 2.34315 3.34315 1 5 1H19C20.6569 1 22 2.34315 22 4V20C22 21.6569 20.6569 23 19 23H5C3.34315 23 2 21.6569 2 20V4ZM5 3H19C19.5523 3 20 3.44771 20 4V20C20 20.5523 19.5523 21 19 21H5C4.44772 21 4 20.5523 4 20V4C4 3.44772 4.44771 3 5 3Z"
                  fill=currentColor clip-rule=evenodd fill-rule=evenodd></path>
              </svg>
            </span>
            Resume
          </RouterLink>
          <RouterLink to="/" :class="{ 'lg:text-white lg:dark:text-white lg:bg-gradient-to-r from-[#FA5252] to-[#DD2476]': $route.path === '/' }"
            class="w-full h-20 rounded-[10px]  cursor-pointer  font-poppins  bg-[#F3F6F6]  font-medium mx-2.5  text-xtiny text-gray-lite dark:text-[#A6A6A6]    justify-center flex flex-col items-center   transition-all duration-300 ease-in-out dark:hover:text-white dark:bg-[#212425] hover:text-white   hover:bg-gradient-to-r from-[#FA5252] to-[#DD2476] ">
            <span class="text-xl mb-1">
              <svg fill=none height=1em stroke=currentColor stroke-linecap=round stroke-linejoin=round stroke-width=2
                viewBox="0 0 24 24" width=1em xmlns=http://www.w3.org/2000/svg>
                <path
                  d="M21 16V8a2 2 0 0 0-1-1.73l-7-4a2 2 0 0 0-2 0l-7 4A2 2 0 0 0 3 8v8a2 2 0 0 0 1 1.73l7 4a2 2 0 0 0 2 0l7-4A2 2 0 0 0 21 16z">
                </path>
                <polyline points="7.5 4.21 12 6.81 16.5 4.21"></polyline>
                <polyline points="7.5 19.79 7.5 14.6 3 12"></polyline>
                <polyline points="21 12 16.5 14.6 16.5 19.79"></polyline>
                <polyline points="3.27 6.96 12 12.01 20.73 6.96"></polyline>
                <line x1=12 x2=12 y1=22.08 y2=12></line>
              </svg>
            </span>
            Work
          </RouterLink>

          <RouterLink to="/about" :class="{ 'lg:text-white lg:dark:text-white lg:bg-gradient-to-r from-[#FA5252] to-[#DD2476]': $route.path === '/about' }"
            class="w-full h-20 rounded-[10px]  cursor-pointer  font-poppins  bg-[#F3F6F6]  font-medium mx-2.5  text-xtiny text-gray-lite dark:text-[#A6A6A6]    justify-center flex flex-col items-center   transition-all duration-300 ease-in-out dark:hover:text-white dark:bg-[#212425] hover:text-white   hover:bg-gradient-to-r from-[#FA5252] to-[#DD2476] ">
            <span class="text-xl mb-1">
              <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" id="statistics" width="31.52" height="27.81" viewBox="0 0 31.52 27.81">
              <defs>
                <linearGradient id="linear-gradient" x1="0.5" y1="2.595" x2="0.5" y2="-2.922" gradientUnits="objectBoundingBox">
                  <stop offset="0.322" stop-color="#a163f5"/>
                  <stop offset="0.466" stop-color="#b074ee"/>
                  <stop offset="0.752" stop-color="#d8a1dd"/>
                  <stop offset="0.898" stop-color="#efbad3"/>
                </linearGradient>
                <linearGradient id="linear-gradient-2" x1="0.5" y1="2.097" x2="0.5" y2="-1.697" xlink:href="#linear-gradient"/>
                <linearGradient id="linear-gradient-3" x1="0.5" y1="3.317" x2="0.5" y2="-4.696" xlink:href="#linear-gradient"/>
                <linearGradient id="linear-gradient-4" x1="0.5" y1="1.18" x2="0.5" y2="-0.181" gradientUnits="objectBoundingBox">
                  <stop offset="0" stop-color="#fd4ffe"/>
                  <stop offset="1" stop-color="#6bb0f8"/>
                </linearGradient>
                <linearGradient id="linear-gradient-5" x1="0.496" y1="9.187" x2="0.496" y2="-2.303" xlink:href="#linear-gradient"/>
                <linearGradient id="linear-gradient-6" x1="0.5" y1="9.192" x2="0.5" y2="-2.299" xlink:href="#linear-gradient"/>
                <linearGradient id="linear-gradient-7" x1="0.499" y1="9.182" x2="0.499" y2="-2.308" xlink:href="#linear-gradient"/>
              </defs>
              <path id="Path_160" data-name="Path 160" d="M189.924,201.863H187.2a.52.52,0,0,0-.52.52V208.2a.52.52,0,0,0,.52.52h2.724a.52.52,0,0,0,.52-.52v-5.819A.52.52,0,0,0,189.924,201.863Zm-.52,5.819H187.72V202.9H189.4Zm0,0" transform="translate(-172.802 -186.857)" fill="url(#linear-gradient)"/>
              <path id="Path_161" data-name="Path 161" d="M251.6,159.949h-2.724a.52.52,0,0,0-.52.52V169.4a.52.52,0,0,0,.52.52H251.6a.52.52,0,0,0,.52-.52v-8.935A.52.52,0,0,0,251.6,159.949Zm-.52,8.935H249.4V160.99h1.683Zm0,0" transform="translate(-229.893 -148.058)" fill="url(#linear-gradient-2)"/>
              <path id="Path_162" data-name="Path 162" d="M128.245,230.605h-2.724a.52.52,0,0,0-.52.52v3.682a.52.52,0,0,0,.52.52h2.724a.52.52,0,0,0,.52-.52v-3.682A.52.52,0,0,0,128.245,230.605Zm-.52,3.682h-1.683v-2.641h1.683Zm0,0" transform="translate(-115.708 -213.462)" fill="url(#linear-gradient-3)"/>
              <path id="Path_163" data-name="Path 163" d="M28.026,0H3.494A3.5,3.5,0,0,0,0,3.494V24.316A3.5,3.5,0,0,0,3.494,27.81H28.026a3.5,3.5,0,0,0,3.494-3.494V3.494A3.5,3.5,0,0,0,28.026,0ZM3.494,1.041H28.026a2.456,2.456,0,0,1,2.453,2.453v3.8H1.041v-3.8A2.456,2.456,0,0,1,3.494,1.041ZM28.026,26.769H3.494a2.456,2.456,0,0,1-2.453-2.453V8.333H30.479V24.316A2.456,2.456,0,0,1,28.026,26.769Zm0,0" fill="url(#linear-gradient-4)"/>
              <path id="Path_164" data-name="Path 164" d="M99.395,37.583h0a1.647,1.647,0,0,0,.005-3.294H99.4a1.647,1.647,0,0,0-.005,3.293Zm-.422-2.077a.6.6,0,0,1,.427-.176h0a.606.606,0,1,1-.429.176Zm0,0" transform="translate(-90.508 -31.74)" fill="url(#linear-gradient-5)"/>
              <path id="Path_165" data-name="Path 165" d="M31.271,37.375h.005a1.647,1.647,0,0,0,.005-3.293h-.005a1.647,1.647,0,0,0-.005,3.293Zm.005-2.253h0a.606.606,0,0,1,0,1.212h0a.606.606,0,0,1,0-1.212Zm0,0" transform="translate(-27.444 -31.548)" fill="url(#linear-gradient-6)"/>
              <path id="Path_166" data-name="Path 166" d="M167.259,37.8h.005a1.647,1.647,0,0,0,0-3.294h0a1.647,1.647,0,0,0-.005,3.294Zm.005-2.253h0a.606.606,0,0,1,0,1.212h0a.606.606,0,0,1,0-1.212Zm0,0" transform="translate(-153.313 -31.939)" fill="url(#linear-gradient-7)"/>
            </svg>
            </span>
            About
          </RouterLink>

          <RouterLink to="/contact" :class="{ 'lg:text-white lg:dark:text-white lg:bg-gradient-to-r from-[#FA5252] to-[#DD2476]': $route.path === '/contact' }"
            class="w-full h-20 rounded-[10px]  cursor-pointer  font-poppins  bg-[#F3F6F6]  font-medium mx-2.5  text-xtiny text-gray-lite dark:text-[#A6A6A6]    justify-center flex flex-col items-center   transition-all duration-300 ease-in-out dark:hover:text-white dark:bg-[#212425] hover:text-white   hover:bg-gradient-to-r from-[#FA5252] to-[#DD2476] ">
            <span class="text-xl mb-1">
              <svg fill=currentColor height=1em stroke=currentColor stroke-width=0 viewBox="0 0 24 24" width=1em
                xmlns=http://www.w3.org/2000/svg>
                <g>
                  <path d="M0 0h24v24H0z" fill=none></path>
                  <path
                    d="M3 2h16.005C20.107 2 21 2.898 21 3.99v16.02c0 1.099-.893 1.99-1.995 1.99H3V2zm4 2H5v16h2V4zm2 16h10V4H9v16zm2-4a3 3 0 0 1 6 0h-6zm3-4a2 2 0 1 1 0-4 2 2 0 0 1 0 4zm8-6h2v4h-2V6zm0 6h2v4h-2v-4z">
                  </path>
                </g>
              </svg>
            </span>
            Contact
          </RouterLink>
          <RouterLink to="/"
            class="w-full h-20 rounded-[10px]  cursor-pointer  font-poppins  bg-[#F3F6F6]  font-medium mx-2.5  text-xtiny text-gray-lite dark:text-[#A6A6A6]    justify-center flex flex-col items-center   transition-all duration-300 ease-in-out dark:hover:text-white dark:bg-[#212425] hover:text-white   hover:bg-gradient-to-r from-[#FA5252] to-[#DD2476] ">
            <span class="text-xl mb-1">
              <svg fill=currentColor height=1em stroke=currentColor stroke-width=0 viewBox="0 0 448 512" width=1em
                xmlns=http://www.w3.org/2000/svg>
                <path
                  d="M162.4 196c4.8-4.9 6.2-5.1 36.4-5.1 27.2 0 28.1.1 32.1 2.1 5.8 2.9 8.3 7 8.3 13.6 0 5.9-2.4 10-7.6 13.4-2.8 1.8-4.5 1.9-31.1 2.1-16.4.1-29.5-.2-31.5-.8-10.3-2.9-14.1-17.7-6.6-25.3zm61.4 94.5c-53.9 0-55.8.2-60.2 4.1-3.5 3.1-5.7 9.4-5.1 13.9.7 4.7 4.8 10.1 9.2 12 2.2 1 14.1 1.7 56.3 1.2l47.9-.6 9.2-1.5c9-5.1 10.5-17.4 3.1-24.4-5.3-4.7-5-4.7-60.4-4.7zm223.4 130.1c-3.5 28.4-23 50.4-51.1 57.5-7.2 1.8-9.7 1.9-172.9 1.8-157.8 0-165.9-.1-172-1.8-8.4-2.2-15.6-5.5-22.3-10-5.6-3.8-13.9-11.8-17-16.4-3.8-5.6-8.2-15.3-10-22C.1 423 0 420.3 0 256.3 0 93.2 0 89.7 1.8 82.6 8.1 57.9 27.7 39 53 33.4c7.3-1.6 332.1-1.9 340-.3 21.2 4.3 37.9 17.1 47.6 36.4 7.7 15.3 7-1.5 7.3 180.6.2 115.8 0 164.5-.7 170.5zm-85.4-185.2c-1.1-5-4.2-9.6-7.7-11.5-1.1-.6-8-1.3-15.5-1.7-12.4-.6-13.8-.8-17.8-3.1-6.2-3.6-7.9-7.6-8-18.3 0-20.4-8.5-39.4-25.3-56.5-12-12.2-25.3-20.5-40.6-25.1-3.6-1.1-11.8-1.5-39.2-1.8-42.9-.5-52.5.4-67.1 6.2-27 10.7-46.3 33.4-53.4 62.4-1.3 5.4-1.6 14.2-1.9 64.3-.4 62.8 0 72.1 4 84.5 9.7 30.7 37.1 53.4 64.6 58.4 9.2 1.7 122.2 2.1 133.7.5 20.1-2.7 35.9-10.8 50.7-25.9 10.7-10.9 17.4-22.8 21.8-38.5 3.2-10.9 2.9-88.4 1.7-93.9z">
                </path>
              </svg>
            </span>
            Blogs
          </RouterLink>

          <RouterLink to="/service" :class="{ 'lg:text-white lg:dark:text-white lg:bg-gradient-to-r from-[#FA5252] to-[#DD2476]': $route.path === '/service' }"
            class="w-full h-20 rounded-[10px]  cursor-pointer  font-poppins  bg-[#F3F6F6]  font-medium mx-2.5  text-xtiny text-gray-lite dark:text-[#A6A6A6]    justify-center flex flex-col items-center   transition-all duration-300 ease-in-out dark:hover:text-white dark:bg-[#212425] hover:text-white   hover:bg-gradient-to-r from-[#FA5252] to-[#DD2476] ">
            <span class="text-xl mb-1">
              <svg fill=currentColor height=1em stroke=currentColor stroke-width=0 viewBox="0 0 448 512" width=1em
                xmlns=http://www.w3.org/2000/svg>
                <path
                  d="M162.4 196c4.8-4.9 6.2-5.1 36.4-5.1 27.2 0 28.1.1 32.1 2.1 5.8 2.9 8.3 7 8.3 13.6 0 5.9-2.4 10-7.6 13.4-2.8 1.8-4.5 1.9-31.1 2.1-16.4.1-29.5-.2-31.5-.8-10.3-2.9-14.1-17.7-6.6-25.3zm61.4 94.5c-53.9 0-55.8.2-60.2 4.1-3.5 3.1-5.7 9.4-5.1 13.9.7 4.7 4.8 10.1 9.2 12 2.2 1 14.1 1.7 56.3 1.2l47.9-.6 9.2-1.5c9-5.1 10.5-17.4 3.1-24.4-5.3-4.7-5-4.7-60.4-4.7zm223.4 130.1c-3.5 28.4-23 50.4-51.1 57.5-7.2 1.8-9.7 1.9-172.9 1.8-157.8 0-165.9-.1-172-1.8-8.4-2.2-15.6-5.5-22.3-10-5.6-3.8-13.9-11.8-17-16.4-3.8-5.6-8.2-15.3-10-22C.1 423 0 420.3 0 256.3 0 93.2 0 89.7 1.8 82.6 8.1 57.9 27.7 39 53 33.4c7.3-1.6 332.1-1.9 340-.3 21.2 4.3 37.9 17.1 47.6 36.4 7.7 15.3 7-1.5 7.3 180.6.2 115.8 0 164.5-.7 170.5zm-85.4-185.2c-1.1-5-4.2-9.6-7.7-11.5-1.1-.6-8-1.3-15.5-1.7-12.4-.6-13.8-.8-17.8-3.1-6.2-3.6-7.9-7.6-8-18.3 0-20.4-8.5-39.4-25.3-56.5-12-12.2-25.3-20.5-40.6-25.1-3.6-1.1-11.8-1.5-39.2-1.8-42.9-.5-52.5.4-67.1 6.2-27 10.7-46.3 33.4-53.4 62.4-1.3 5.4-1.6 14.2-1.9 64.3-.4 62.8 0 72.1 4 84.5 9.7 30.7 37.1 53.4 64.6 58.4 9.2 1.7 122.2 2.1 133.7.5 20.1-2.7 35.9-10.8 50.7-25.9 10.7-10.9 17.4-22.8 21.8-38.5 3.2-10.9 2.9-88.4 1.7-93.9z">
                </path>
              </svg>
            </span>
            Service
          </RouterLink>
          <RouterLink to="/portfolio" :class="{ 'lg:text-white lg:dark:text-white lg:bg-gradient-to-r from-[#FA5252] to-[#DD2476]': $route.path === '/portfolio' }"
            class="w-full h-20 rounded-[10px]  cursor-pointer  font-poppins  bg-[#F3F6F6]  font-medium mx-2.5  text-xtiny text-gray-lite dark:text-[#A6A6A6]    justify-center flex flex-col items-center   transition-all duration-300 ease-in-out dark:hover:text-white dark:bg-[#212425] hover:text-white   hover:bg-gradient-to-r from-[#FA5252] to-[#DD2476] ">
            <span class="text-xl mb-1">
              <svg fill=currentColor height=1em stroke=currentColor stroke-width=0 viewBox="0 0 448 512" width=1em
                xmlns=http://www.w3.org/2000/svg>
                <path
                  d="M162.4 196c4.8-4.9 6.2-5.1 36.4-5.1 27.2 0 28.1.1 32.1 2.1 5.8 2.9 8.3 7 8.3 13.6 0 5.9-2.4 10-7.6 13.4-2.8 1.8-4.5 1.9-31.1 2.1-16.4.1-29.5-.2-31.5-.8-10.3-2.9-14.1-17.7-6.6-25.3zm61.4 94.5c-53.9 0-55.8.2-60.2 4.1-3.5 3.1-5.7 9.4-5.1 13.9.7 4.7 4.8 10.1 9.2 12 2.2 1 14.1 1.7 56.3 1.2l47.9-.6 9.2-1.5c9-5.1 10.5-17.4 3.1-24.4-5.3-4.7-5-4.7-60.4-4.7zm223.4 130.1c-3.5 28.4-23 50.4-51.1 57.5-7.2 1.8-9.7 1.9-172.9 1.8-157.8 0-165.9-.1-172-1.8-8.4-2.2-15.6-5.5-22.3-10-5.6-3.8-13.9-11.8-17-16.4-3.8-5.6-8.2-15.3-10-22C.1 423 0 420.3 0 256.3 0 93.2 0 89.7 1.8 82.6 8.1 57.9 27.7 39 53 33.4c7.3-1.6 332.1-1.9 340-.3 21.2 4.3 37.9 17.1 47.6 36.4 7.7 15.3 7-1.5 7.3 180.6.2 115.8 0 164.5-.7 170.5zm-85.4-185.2c-1.1-5-4.2-9.6-7.7-11.5-1.1-.6-8-1.3-15.5-1.7-12.4-.6-13.8-.8-17.8-3.1-6.2-3.6-7.9-7.6-8-18.3 0-20.4-8.5-39.4-25.3-56.5-12-12.2-25.3-20.5-40.6-25.1-3.6-1.1-11.8-1.5-39.2-1.8-42.9-.5-52.5.4-67.1 6.2-27 10.7-46.3 33.4-53.4 62.4-1.3 5.4-1.6 14.2-1.9 64.3-.4 62.8 0 72.1 4 84.5 9.7 30.7 37.1 53.4 64.6 58.4 9.2 1.7 122.2 2.1 133.7.5 20.1-2.7 35.9-10.8 50.7-25.9 10.7-10.9 17.4-22.8 21.8-38.5 3.2-10.9 2.9-88.4 1.7-93.9z">
                </path>
              </svg>
            </span>
            Portfolio
          </RouterLink>
        </ul>
      </nav>
    </header>
    </div>
</template>

<style scoped>
 
</style>