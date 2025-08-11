<template>
  <div
    class="relative flex size-full min-h-screen flex-col bg-white group/design-root overflow-x-hidden"
    style="font-family: 'Space Grotesk', 'Noto Sans', sans-serif"
  >
    <div class="layout-container flex h-full grow flex-col">
      <header-bar />
      <div class="flex flex-1 justify-center pb-5">
        <div
          class="layout-content-container flex flex-col max-w-[960px] flex-1"
        >
          <div class="@container">
            <div class="@[480px]:p-4">
              <div
                class="flex min-h-[480px] flex-col gap-6 bg-cover bg-center bg-no-repeat @[480px]:gap-8 @[480px]:rounded-xl items-center justify-center p-4"
                style="
                  background-image: linear-gradient(
                      rgba(0, 0, 0, 0.1) 0%,
                      rgba(0, 0, 0, 0.4) 100%
                    ),
                    url('https://lh3.googleusercontent.com/aida-public/AB6AXuB1KnpS3sBLzCbrPkFyJ60Hptn8nuIPArFntlHqbzDzwfN1yfvNqu389d-1hb7MyheBmuEh7nv82tRhgukrYTXtub0bmP1lzgnvitWDQGE0JVi69g8CsOGQ9WgoiPPVMrrZwA6bcgi303K1Z4d9EhHM7Mw6EXR2QmY5KVwzqj9UvDIm6S_FlpZiROxPiw7nnGBA9F2Sfcl_tjAf0XHw3Z9hDVAGHcBsb7VIOJMOSgCLNY-MDDuTNZpY1lDVTaPH-SrcJ-MRcccGIBLE');
                "
              >
                <div class="flex flex-col gap-2 text-center">
                  <h1
                    class="text-white text-4xl font-black leading-tight tracking-[-0.033em] @[480px]:text-5xl @[480px]:font-black @[480px]:leading-tight @[480px]:tracking-[-0.033em]"
                  >
                    Clean Your Ride, Right at Your Doorstep.
                  </h1>
                  <h2
                    class="text-white text-sm font-normal leading-normal @[480px]:text-base @[480px]:font-normal @[480px]:leading-normal"
                  >
                    Experience the best wash services in town for your cars,
                    bikes, and scooters. Book your service through our Android
                    and iOS apps.
                  </h2>
                </div>
                <button
                  class="flex min-w-[84px] max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-full h-10 px-4 @[480px]:h-12 @[480px]:px-5 bg-[#196be5] text-white text-sm font-bold leading-normal tracking-[0.015em] @[480px]:text-base @[480px]:font-bold @[480px]:leading-normal @[480px]:tracking-[0.015em]"
                >
                  <span class="truncate">Download Our App</span>
                </button>
              </div>
            </div>
          </div>
          <h2
            class="text-[#111418] text-[22px] font-bold leading-tight tracking-[-0.015em] px-4 pb-3 pt-5"
          >
            How It Works
          </h2>
          <div
            class="grid grid-cols-[repeat(auto-fit,minmax(158px,1fr))] gap-3 p-4"
          >
            <div
              class="flex flex-1 gap-3 rounded-lg border border-[#dcdfe5] bg-white p-4 flex-col"
            >
              <div
                class="text-[#111418]"
                data-icon="Car"
                data-size="24px"
                data-weight="regular"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="24px"
                  height="24px"
                  fill="currentColor"
                  viewBox="0 0 256 256"
                >
                  <path
                    d="M240,112H229.2L201.42,49.5A16,16,0,0,0,186.8,40H69.2a16,16,0,0,0-14.62,9.5L26.8,112H16a8,8,0,0,0,0,16h8v80a16,16,0,0,0,16,16H64a16,16,0,0,0,16-16V192h96v16a16,16,0,0,0,16,16h24a16,16,0,0,0,16-16V128h8a8,8,0,0,0,0-16ZM69.2,56H186.8l24.89,56H44.31ZM64,208H40V192H64Zm128,0V192h24v16Zm24-32H40V128H216ZM56,152a8,8,0,0,1,8-8H80a8,8,0,0,1,0,16H64A8,8,0,0,1,56,152Zm112,0a8,8,0,0,1,8-8h16a8,8,0,0,1,0,16H176A8,8,0,0,1,168,152Z"
                  ></path>
                </svg>
              </div>
              <div class="flex flex-col gap-1">
                <h2 class="text-[#111418] text-base font-bold leading-tight">
                  Select a Service
                </h2>
                <p class="text-[#637288] text-sm font-normal leading-normal">
                  Choose from a variety of services tailored for your car and
                  bike care needs.
                </p>
              </div>
            </div>
            <div
              class="flex flex-1 gap-3 rounded-lg border border-[#dcdfe5] bg-white p-4 flex-col"
            >
              <div
                class="text-[#111418]"
                data-icon="Calendar"
                data-size="24px"
                data-weight="regular"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="24px"
                  height="24px"
                  fill="currentColor"
                  viewBox="0 0 256 256"
                >
                  <path
                    d="M208,32H184V24a8,8,0,0,0-16,0v8H88V24a8,8,0,0,0-16,0v8H48A16,16,0,0,0,32,48V208a16,16,0,0,0,16,16H208a16,16,0,0,0,16-16V48A16,16,0,0,0,208,32ZM72,48v8a8,8,0,0,0,16,0V48h80v8a8,8,0,0,0,16,0V48h24V80H48V48ZM208,208H48V96H208V208Zm-96-88v64a8,8,0,0,1-16,0V132.94l-4.42,2.22a8,8,0,0,1-7.16-14.32l16-8A8,8,0,0,1,112,120Zm59.16,30.45L152,176h16a8,8,0,0,1,0,16H136a8,8,0,0,1-6.4-12.8l28.78-38.37A8,8,0,1,0,145.07,132a8,8,0,1,1-13.85-8A24,24,0,0,1,176,136,23.76,23.76,0,0,1,171.16,150.45Z"
                  ></path>
                </svg>
              </div>
              <div class="flex flex-col gap-1">
                <h2 class="text-[#111418] text-base font-bold leading-tight">
                  Book a Slot
                </h2>
                <p class="text-[#637288] text-sm font-normal leading-normal">
                  Schedule your service effortlessly using our intuitive
                  Android/IOS app.
                </p>
              </div>
            </div>
            <div
              class="flex flex-1 gap-3 rounded-lg border border-[#dcdfe5] bg-white p-4 flex-col"
            >
              <div
                class="text-[#111418]"
                data-icon="House"
                data-size="24px"
                data-weight="regular"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="24px"
                  height="24px"
                  fill="currentColor"
                  viewBox="0 0 256 256"
                >
                  <path
                    d="M218.83,103.77l-80-75.48a1.14,1.14,0,0,1-.11-.11,16,16,0,0,0-21.53,0l-.11.11L37.17,103.77A16,16,0,0,0,32,115.55V208a16,16,0,0,0,16,16H96a16,16,0,0,0,16-16V160h32v48a16,16,0,0,0,16,16h48a16,16,0,0,0,16-16V115.55A16,16,0,0,0,218.83,103.77ZM208,208H160V160a16,16,0,0,0-16-16H112a16,16,0,0,0-16,16v48H48V115.55l.11-.1L128,40l79.9,75.43.11.1Z"
                  ></path>
                </svg>
              </div>
              <div class="flex flex-col gap-1">
                <h2 class="text-[#111418] text-base font-bold leading-tight">
                  Door-step Care
                </h2>
                <p class="text-[#637288] text-sm font-normal leading-normal">
                  Our skilled professionals arrive at your location with all
                  necessary power and cleaning supplies.
                </p>
              </div>
            </div>
          </div>
          <h2
            class="text-[#111418] text-[22px] font-bold leading-tight tracking-[-0.015em] px-4 pb-3 pt-5"
          >
            Our Services
          </h2>
          <div
            class="grid grid-cols-[repeat(auto-fit,minmax(158px,1fr))] gap-3 p-4"
          >
            <div
              class="flex flex-1 gap-3 rounded-lg border border-[#dcdfe5] bg-white p-4 flex-col"
            >
              <div
                class="text-[#111418]"
                data-icon="Drop"
                data-size="24px"
                data-weight="regular"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="24px"
                  height="24px"
                  fill="currentColor"
                  viewBox="0 0 256 256"
                >
                  <path
                    d="M174,47.75a254.19,254.19,0,0,0-41.45-38.3,8,8,0,0,0-9.18,0A254.19,254.19,0,0,0,82,47.75C54.51,79.32,40,112.6,40,144a88,88,0,0,0,176,0C216,112.6,201.49,79.32,174,47.75ZM128,216a72.08,72.08,0,0,1-72-72c0-57.23,55.47-105,72-118,16.53,13,72,60.75,72,118A72.08,72.08,0,0,1,128,216Zm55.89-62.66a57.6,57.6,0,0,1-46.56,46.55A8.75,8.75,0,0,1,136,200a8,8,0,0,1-1.32-15.89c16.57-2.79,30.63-16.85,33.44-33.45a8,8,0,0,1,15.78,2.68Z"
                  ></path>
                </svg>
              </div>
              <div class="flex flex-col gap-1">
                <h2 class="text-[#111418] text-base font-bold leading-tight">
                  Normal Wash
                </h2>
                <p class="text-[#637288] text-sm font-normal leading-normal">
                  Thorough vacuum cleaning of the interior, gentle foam wash for
                  the exterior, steam cleaning to remove stubborn dirt and
                  grime.
                </p>
              </div>
            </div>
            <div
              class="flex flex-1 gap-3 rounded-lg border border-[#dcdfe5] bg-white p-4 flex-col"
            >
              <div
                class="text-[#111418]"
                data-icon="SketchLogo"
                data-size="24px"
                data-weight="regular"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="24px"
                  height="24px"
                  fill="currentColor"
                  viewBox="0 0 256 256"
                >
                  <path
                    d="M246,98.73l-56-64A8,8,0,0,0,184,32H72a8,8,0,0,0-6,2.73l-56,64a8,8,0,0,0,.17,10.73l112,120a8,8,0,0,0,11.7,0l112-120A8,8,0,0,0,246,98.73ZM222.37,96H180L144,48h36.37ZM74.58,112l30.13,75.33L34.41,112Zm89.6,0L128,202.46,91.82,112ZM96,96l32-42.67L160,96Zm85.42,16h40.17l-70.3,75.33ZM75.63,48H112L76,96H33.63Z"
                  ></path>
                </svg>
              </div>
              <div class="flex flex-col gap-1">
                <h2 class="text-[#111418] text-base font-bold leading-tight">
                  Premium Wash
                </h2>
                <p class="text-[#637288] text-sm font-normal leading-normal">
                  Deep interior cleaning, foam cleaning, vacuuming, steam wash,
                  tire shine, deep cleaning underbody, and steam wash for seats.
                </p>
              </div>
            </div>
            <div
              class="flex flex-1 gap-3 rounded-lg border border-[#dcdfe5] bg-white p-4 flex-col"
            >
              <div
                class="text-[#111418]"
                data-icon="Sparkle"
                data-size="24px"
                data-weight="regular"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="24px"
                  height="24px"
                  fill="currentColor"
                  viewBox="0 0 256 256"
                >
                  <path
                    d="M197.58,129.06l-51.61-19-19-51.65a15.92,15.92,0,0,0-29.88,0L78.07,110l-51.65,19a15.92,15.92,0,0,0,0,29.88L78,178l19,51.62a15.92,15.92,0,0,0,29.88,0l19-51.61,51.65-19a15.92,15.92,0,0,0,0-29.88ZM140.39,163a15.87,15.87,0,0,0-9.43,9.43l-19,51.46L93,172.39A15.87,15.87,0,0,0,83.61,163h0L32.15,144l51.46-19A15.87,15.87,0,0,0,93,115.61l19-51.46,19,51.46a15.87,15.87,0,0,0,9.43,9.43l51.46,19ZM144,40a8,8,0,0,1,8-8h16V16a8,8,0,0,1,16,0V32h16a8,8,0,0,1,0,16H184V64a8,8,0,0,1-16,0V48H152A8,8,0,0,1,144,40ZM248,88a8,8,0,0,1-8,8h-8v8a8,8,0,0,1-16,0V96h-8a8,8,0,0,1,0-16h8V72a8,8,0,0,1,16,0v8h8A8,8,0,0,1,248,88Z"
                  ></path>
                </svg>
              </div>
              <div class="flex flex-col gap-1">
                <h2 class="text-[#111418] text-base font-bold leading-tight">
                  Detailing
                </h2>
                <p class="text-[#637288] text-sm font-normal leading-normal">
                  Ceramic coating, paint protection, exterior beautification,
                  premium interior foam, interior enrichment, AC vent cleaning,
                  engine cleaning/polish, windscreen treatment, and all premium
                  wash services.
                </p>
              </div>
            </div>
          </div>
          <div class="flex flex-col gap-10 px-4 py-10 @container">
            <div class="flex flex-col gap-4">
              <h1
                class="text-[#111418] tracking-light text-[32px] font-bold leading-tight @[480px]:text-4xl @[480px]:font-black @[480px]:leading-tight @[480px]:tracking-[-0.033em] max-w-[720px]"
              >
                Why Choose Us?
              </h1>
              <p
                class="text-[#111418] text-base font-normal leading-normal max-w-[720px]"
              >
                We offer a convenient, professional, and eco-friendly car wash
                service that comes to you. Here's why we stand out:
              </p>
            </div>
            <div
              class="grid grid-cols-[repeat(auto-fit,minmax(158px,1fr))] gap-3 p-0"
            >
              <div
                class="flex flex-1 gap-3 rounded-lg border border-[#dcdfe5] bg-white p-4 flex-col"
              >
                <div
                  class="text-[#111418]"
                  data-icon="Car"
                  data-size="24px"
                  data-weight="regular"
                >
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="24px"
                    height="24px"
                    fill="currentColor"
                    viewBox="0 0 256 256"
                  >
                    <path
                      d="M240,112H229.2L201.42,49.5A16,16,0,0,0,186.8,40H69.2a16,16,0,0,0-14.62,9.5L26.8,112H16a8,8,0,0,0,0,16h8v80a16,16,0,0,0,16,16H64a16,16,0,0,0,16-16V192h96v16a16,16,0,0,0,16,16h24a16,16,0,0,0,16-16V128h8a8,8,0,0,0,0-16ZM69.2,56H186.8l24.89,56H44.31ZM64,208H40V192H64Zm128,0V192h24v16Zm24-32H40V128H216ZM56,152a8,8,0,0,1,8-8H80a8,8,0,0,1,0,16H64A8,8,0,0,1,56,152Zm112,0a8,8,0,0,1,8-8h16a8,8,0,0,1,0,16H176A8,8,0,0,1,168,152Z"
                    ></path>
                  </svg>
                </div>
                <div class="flex flex-col gap-1">
                  <h2 class="text-[#111418] text-base font-bold leading-tight">
                    Doorstep Service
                  </h2>
                  <p class="text-[#637288] text-sm font-normal leading-normal">
                    We come to you, saving time and hassle.
                  </p>
                </div>
              </div>
              <div
                class="flex flex-1 gap-3 rounded-lg border border-[#dcdfe5] bg-white p-4 flex-col"
              >
                <div
                  class="text-[#111418]"
                  data-icon="UsersThree"
                  data-size="24px"
                  data-weight="regular"
                >
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="24px"
                    height="24px"
                    fill="currentColor"
                    viewBox="0 0 256 256"
                  >
                    <path
                      d="M244.8,150.4a8,8,0,0,1-11.2-1.6A51.6,51.6,0,0,0,192,128a8,8,0,0,1-7.37-4.89,8,8,0,0,1,0-6.22A8,8,0,0,1,192,112a24,24,0,1,0-23.24-30,8,8,0,1,1-15.5-4A40,40,0,1,1,219,117.51a67.94,67.94,0,0,1,27.43,21.68A8,8,0,0,1,244.8,150.4ZM190.92,212a8,8,0,1,1-13.84,8,57,57,0,0,0-98.16,0,8,8,0,1,1-13.84-8,72.06,72.06,0,0,1,33.74-29.92,48,48,0,1,1,58.36,0A72.06,72.06,0,0,1,190.92,212ZM128,176a32,32,0,1,0-32-32A32,32,0,0,0,128,176ZM72,120a8,8,0,0,0-8-8A24,24,0,1,1,87.24,82a8,8,0,1,0,15.5-4A40,40,0,1,0,37,117.51,67.94,67.94,0,0,0,9.6,139.19a8,8,0,1,0,12.8,9.61A51.6,51.6,0,0,1,64,128,8,8,0,0,0,72,120Z"
                    ></path>
                  </svg>
                </div>
                <div class="flex flex-col gap-1">
                  <h2 class="text-[#111418] text-base font-bold leading-tight">
                    Trained Professionals
                  </h2>
                  <p class="text-[#637288] text-sm font-normal leading-normal">
                    Background-verified and skilled staff.
                  </p>
                </div>
              </div>
              <div
                class="flex flex-1 gap-3 rounded-lg border border-[#dcdfe5] bg-white p-4 flex-col"
              >
                <div
                  class="text-[#111418]"
                  data-icon="Calendar"
                  data-size="24px"
                  data-weight="regular"
                >
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="24px"
                    height="24px"
                    fill="currentColor"
                    viewBox="0 0 256 256"
                  >
                    <path
                      d="M208,32H184V24a8,8,0,0,0-16,0v8H88V24a8,8,0,0,0-16,0v8H48A16,16,0,0,0,32,48V208a16,16,0,0,0,16,16H208a16,16,0,0,0,16-16V48A16,16,0,0,0,208,32ZM72,48v8a8,8,0,0,0,16,0V48h80v8a8,8,0,0,0,16,0V48h24V80H48V48ZM208,208H48V96H208V208Zm-96-88v64a8,8,0,0,1-16,0V132.94l-4.42,2.22a8,8,0,0,1-7.16-14.32l16-8A8,8,0,0,1,112,120Zm59.16,30.45L152,176h16a8,8,0,0,1,0,16H136a8,8,0,0,1-6.4-12.8l28.78-38.37A8,8,0,1,0,145.07,132a8,8,0,1,1-13.85-8A24,24,0,0,1,176,136,23.76,23.76,0,0,1,171.16,150.45Z"
                    ></path>
                  </svg>
                </div>
                <div class="flex flex-col gap-1">
                  <h2 class="text-[#111418] text-base font-bold leading-tight">
                    Flexible Time Slots
                  </h2>
                  <p class="text-[#637288] text-sm font-normal leading-normal">
                    Book anytime, 7 days a week.
                  </p>
                </div>
              </div>
              <div
                class="flex flex-1 gap-3 rounded-lg border border-[#dcdfe5] bg-white p-4 flex-col"
              >
                <div
                  class="text-[#111418]"
                  data-icon="CurrencyCircleDollar"
                  data-size="24px"
                  data-weight="regular"
                >
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="24px"
                    height="24px"
                    fill="currentColor"
                    viewBox="0 0 256 256"
                  >
                    <path
                      d="M128,24A104,104,0,1,0,232,128,104.11,104.11,0,0,0,128,24Zm0,192a88,88,0,1,1,88-88A88.1,88.1,0,0,1,128,216Zm40-68a28,28,0,0,1-28,28h-4v8a8,8,0,0,1-16,0v-8H104a8,8,0,0,1,0-16h36a12,12,0,0,0,0-24H116a28,28,0,0,1,0-56h4V72a8,8,0,0,1,16,0v8h16a8,8,0,0,1,0,16H116a12,12,0,0,0,0,24h24A28,28,0,0,1,168,148Z"
                    ></path>
                  </svg>
                </div>
                <div class="flex flex-col gap-1">
                  <h2 class="text-[#111418] text-base font-bold leading-tight">
                    Transparent Pricing
                  </h2>
                  <p class="text-[#637288] text-sm font-normal leading-normal">
                    No hidden fees, pay for what you choose.
                  </p>
                </div>
              </div>
              <div
                class="flex flex-1 gap-3 rounded-lg border border-[#dcdfe5] bg-white p-4 flex-col"
              >
                <div
                  class="text-[#111418]"
                  data-icon="Recycle"
                  data-size="24px"
                  data-weight="regular"
                >
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="24px"
                    height="24px"
                    fill="currentColor"
                    viewBox="0 0 256 256"
                  >
                    <path
                      d="M96,208a8,8,0,0,1-8,8H40a24,24,0,0,1-20.77-36l34.29-59.25L39.47,124.5A8,8,0,1,1,35.33,109l32.77-8.77a8,8,0,0,1,9.8,5.66l8.79,32.77A8,8,0,0,1,81,148.5a8.37,8.37,0,0,1-2.08.27,8,8,0,0,1-7.72-5.93l-3.8-14.15L33.11,188A8,8,0,0,0,40,200H88A8,8,0,0,1,96,208Zm140.73-28-23.14-40a8,8,0,0,0-13.84,8l23.14,40A8,8,0,0,1,216,200H147.31l10.34-10.34a8,8,0,0,0-11.31-11.32l-24,24a8,8,0,0,0,0,11.32l24,24a8,8,0,0,0,11.31-11.32L147.31,216H216a24,24,0,0,0,20.77-36ZM128,32a7.85,7.85,0,0,1,6.92,4l34.29,59.25-14.08-3.78A8,8,0,0,0,151,106.92l32.78,8.79a8.23,8.23,0,0,0,2.07.27,8,8,0,0,0,7.72-5.93l8.79-32.79a8,8,0,1,0-15.45-4.14l-3.8,14.17L148.77,28a24,24,0,0,0-41.54,0L84.07,68a8,8,0,0,0,13.85,8l23.16-40A7.85,7.85,0,0,1,128,32Z"
                    ></path>
                  </svg>
                </div>
                <div class="flex flex-col gap-1">
                  <h2 class="text-[#111418] text-base font-bold leading-tight">
                    Eco-Friendly
                  </h2>
                  <p class="text-[#637288] text-sm font-normal leading-normal">
                    Water-efficient &amp; biodegradable products.
                  </p>
                </div>
              </div>
              <div
                class="flex flex-1 gap-3 rounded-lg border border-[#dcdfe5] bg-white p-4 flex-col"
              >
                <div
                  class="text-[#111418]"
                  data-icon="DeviceMobile"
                  data-size="24px"
                  data-weight="regular"
                >
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="24px"
                    height="24px"
                    fill="currentColor"
                    viewBox="0 0 256 256"
                  >
                    <path
                      d="M176,16H80A24,24,0,0,0,56,40V216a24,24,0,0,0,24,24h96a24,24,0,0,0,24-24V40A24,24,0,0,0,176,16ZM72,64H184V192H72Zm8-32h96a8,8,0,0,1,8,8v8H72V40A8,8,0,0,1,80,32Zm96,192H80a8,8,0,0,1-8-8v-8H184v8A8,8,0,0,1,176,224Z"
                    ></path>
                  </svg>
                </div>
                <div class="flex flex-col gap-1">
                  <h2 class="text-[#111418] text-base font-bold leading-tight">
                    Real-Time Booking
                  </h2>
                  <p class="text-[#637288] text-sm font-normal leading-normal">
                    Fast, easy, and trackable.
                  </p>
                </div>
              </div>
              <div
                class="flex flex-1 gap-3 rounded-lg border border-[#dcdfe5] bg-white p-4 flex-col"
              >
                <div
                  class="text-[#111418]"
                  data-icon="Smiley"
                  data-size="24px"
                  data-weight="regular"
                >
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="24px"
                    height="24px"
                    fill="currentColor"
                    viewBox="0 0 256 256"
                  >
                    <path
                      d="M128,24A104,104,0,1,0,232,128,104.11,104.11,0,0,0,128,24Zm0,192a88,88,0,1,1,88-88A88.1,88.1,0,0,1,128,216ZM80,108a12,12,0,1,1,12,12A12,12,0,0,1,80,108Zm96,0a12,12,0,1,1-12-12A12,12,0,0,1,176,108Zm-1.07,48c-10.29,17.79-27.4,28-46.93,28s-36.63-10.2-46.92-28a8,8,0,1,1,13.84-8c7.47,12.91,19.21,20,33.08,20s25.61-7.1,33.07-20a8,8,0,0,1,13.86,8Z"
                    ></path>
                  </svg>
                </div>
                <div class="flex flex-col gap-1">
                  <h2 class="text-[#111418] text-base font-bold leading-tight">
                    Satisfaction Guaranteed
                  </h2>
                  <p class="text-[#637288] text-sm font-normal leading-normal">
                    We don’t leave until you're happy.
                  </p>
                </div>
              </div>
            </div>
          </div>
          <h2
            class="text-[#111418] text-[22px] font-bold leading-tight tracking-[-0.015em] px-4 pb-3 pt-5"
          >
            Pricing Starting At
          </h2>
          <div
            class="grid grid-cols-[repeat(auto-fit,minmax(228px,1fr))] gap-2.5 px-4 py-3 @3xl:grid-cols-4"
          >
            <div
              class="flex flex-1 flex-col gap-4 rounded-xl border border-solid border-[#dcdfe5] bg-white p-6"
            >
              <div class="flex flex-col gap-1">
                <h1 class="text-[#111418] text-base font-bold leading-tight">
                  Normal Wash
                </h1>
                <p class="flex items-baseline gap-1 text-[#111418]">
                  <span
                    class="text-[#111418] text-4xl font-black leading-tight tracking-[-0.033em]"
                    >₹299</span
                  >
                  <span class="text-[#111418] text-base font-bold leading-tight"
                    >per wash</span
                  >
                </p>
              </div>
              <div class="flex flex-col gap-2">
                <div
                  class="text-[13px] font-normal leading-normal flex gap-3 text-[#111418]"
                >
                  <div
                    class="text-[#111418]"
                    data-icon="Check"
                    data-size="20px"
                    data-weight="regular"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="20px"
                      height="20px"
                      fill="currentColor"
                      viewBox="0 0 256 256"
                    >
                      <path
                        d="M229.66,77.66l-128,128a8,8,0,0,1-11.32,0l-56-56a8,8,0,0,1,11.32-11.32L96,188.69,218.34,66.34a8,8,0,0,1,11.32,11.32Z"
                      ></path>
                    </svg>
                  </div>
                  Vacuum Cleaning
                </div>
                <div
                  class="text-[13px] font-normal leading-normal flex gap-3 text-[#111418]"
                >
                  <div
                    class="text-[#111418]"
                    data-icon="Check"
                    data-size="20px"
                    data-weight="regular"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="20px"
                      height="20px"
                      fill="currentColor"
                      viewBox="0 0 256 256"
                    >
                      <path
                        d="M229.66,77.66l-128,128a8,8,0,0,1-11.32,0l-56-56a8,8,0,0,1,11.32-11.32L96,188.69,218.34,66.34a8,8,0,0,1,11.32,11.32Z"
                      ></path>
                    </svg>
                  </div>
                  Foam Cleaning
                </div>
                <div
                  class="text-[13px] font-normal leading-normal flex gap-3 text-[#111418]"
                >
                  <div
                    class="text-[#111418]"
                    data-icon="Check"
                    data-size="20px"
                    data-weight="regular"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="20px"
                      height="20px"
                      fill="currentColor"
                      viewBox="0 0 256 256"
                    >
                      <path
                        d="M229.66,77.66l-128,128a8,8,0,0,1-11.32,0l-56-56a8,8,0,0,1,11.32-11.32L96,188.69,218.34,66.34a8,8,0,0,1,11.32,11.32Z"
                      ></path>
                    </svg>
                  </div>
                  Steam Cleaning
                </div>
              </div>
            </div>
            <div
              class="flex flex-1 flex-col gap-4 rounded-xl border border-solid border-[#dcdfe5] bg-white p-6"
            >
              <div class="flex flex-col gap-1">
                <h1 class="text-[#111418] text-base font-bold leading-tight">
                  Premium Wash
                </h1>
                <p class="flex items-baseline gap-1 text-[#111418]">
                  <span
                    class="text-[#111418] text-4xl font-black leading-tight tracking-[-0.033em]"
                    >₹499</span
                  >
                  <span class="text-[#111418] text-base font-bold leading-tight"
                    >per wash</span
                  >
                </p>
              </div>
              <div class="flex flex-col gap-2">
                <div
                  class="text-[13px] font-normal leading-normal flex gap-3 text-[#111418]"
                >
                  <div
                    class="text-[#111418]"
                    data-icon="Check"
                    data-size="20px"
                    data-weight="regular"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="20px"
                      height="20px"
                      fill="currentColor"
                      viewBox="0 0 256 256"
                    >
                      <path
                        d="M229.66,77.66l-128,128a8,8,0,0,1-11.32,0l-56-56a8,8,0,0,1,11.32-11.32L96,188.69,218.34,66.34a8,8,0,0,1,11.32,11.32Z"
                      ></path>
                    </svg>
                  </div>
                  Deep interior cleaning
                </div>
                <div
                  class="text-[13px] font-normal leading-normal flex gap-3 text-[#111418]"
                >
                  <div
                    class="text-[#111418]"
                    data-icon="Check"
                    data-size="20px"
                    data-weight="regular"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="20px"
                      height="20px"
                      fill="currentColor"
                      viewBox="0 0 256 256"
                    >
                      <path
                        d="M229.66,77.66l-128,128a8,8,0,0,1-11.32,0l-56-56a8,8,0,0,1,11.32-11.32L96,188.69,218.34,66.34a8,8,0,0,1,11.32,11.32Z"
                      ></path>
                    </svg>
                  </div>
                  Foam cleaning
                </div>
                <div
                  class="text-[13px] font-normal leading-normal flex gap-3 text-[#111418]"
                >
                  <div
                    class="text-[#111418]"
                    data-icon="Check"
                    data-size="20px"
                    data-weight="regular"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="20px"
                      height="20px"
                      fill="currentColor"
                      viewBox="0 0 256 256"
                    >
                      <path
                        d="M229.66,77.66l-128,128a8,8,0,0,1-11.32,0l-56-56a8,8,0,0,1,11.32-11.32L96,188.69,218.34,66.34a8,8,0,0,1,11.32,11.32Z"
                      ></path>
                    </svg>
                  </div>
                  Vacuuming
                </div>
                <div
                  class="text-[13px] font-normal leading-normal flex gap-3 text-[#111418]"
                >
                  <div
                    class="text-[#111418]"
                    data-icon="Check"
                    data-size="20px"
                    data-weight="regular"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="20px"
                      height="20px"
                      fill="currentColor"
                      viewBox="0 0 256 256"
                    >
                      <path
                        d="M229.66,77.66l-128,128a8,8,0,0,1-11.32,0l-56-56a8,8,0,0,1,11.32-11.32L96,188.69,218.34,66.34a8,8,0,0,1,11.32,11.32Z"
                      ></path>
                    </svg>
                  </div>
                  Steam wash
                </div>
                <div
                  class="text-[13px] font-normal leading-normal flex gap-3 text-[#111418]"
                >
                  <div
                    class="text-[#111418]"
                    data-icon="Check"
                    data-size="20px"
                    data-weight="regular"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="20px"
                      height="20px"
                      fill="currentColor"
                      viewBox="0 0 256 256"
                    >
                      <path
                        d="M229.66,77.66l-128,128a8,8,0,0,1-11.32,0l-56-56a8,8,0,0,1,11.32-11.32L96,188.69,218.34,66.34a8,8,0,0,1,11.32,11.32Z"
                      ></path>
                    </svg>
                  </div>
                  Tire shine
                </div>
                <div
                  class="text-[13px] font-normal leading-normal flex gap-3 text-[#111418]"
                >
                  <div
                    class="text-[#111418]"
                    data-icon="Check"
                    data-size="20px"
                    data-weight="regular"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="20px"
                      height="20px"
                      fill="currentColor"
                      viewBox="0 0 256 256"
                    >
                      <path
                        d="M229.66,77.66l-128,128a8,8,0,0,1-11.32,0l-56-56a8,8,0,0,1,11.32-11.32L96,188.69,218.34,66.34a8,8,0,0,1,11.32,11.32Z"
                      ></path>
                    </svg>
                  </div>
                  Deep cleaning underbody
                </div>
                <div
                  class="text-[13px] font-normal leading-normal flex gap-3 text-[#111418]"
                >
                  <div
                    class="text-[#111418]"
                    data-icon="Check"
                    data-size="20px"
                    data-weight="regular"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="20px"
                      height="20px"
                      fill="currentColor"
                      viewBox="0 0 256 256"
                    >
                      <path
                        d="M229.66,77.66l-128,128a8,8,0,0,1-11.32,0l-56-56a8,8,0,0,1,11.32-11.32L96,188.69,218.34,66.34a8,8,0,0,1,11.32,11.32Z"
                      ></path>
                    </svg>
                  </div>
                  Steam wash for seats
                </div>
              </div>
            </div>
            <div
              class="flex flex-1 flex-col gap-4 rounded-xl border border-solid border-[#dcdfe5] bg-white p-6"
            >
              <div class="flex flex-col gap-1">
                <h1 class="text-[#111418] text-base font-bold leading-tight">
                  Detailing
                </h1>
                <p class="flex items-baseline gap-1 text-[#111418]">
                  <span
                    class="text-[#111418] text-4xl font-black leading-tight tracking-[-0.033em]"
                    >₹100</span
                  >
                  <span class="text-[#111418] text-base font-bold leading-tight"
                    >per service</span
                  >
                </p>
              </div>
              <div class="flex flex-col gap-2">
                <div
                  class="text-[13px] font-normal leading-normal flex gap-3 text-[#111418]"
                >
                  <div
                    class="text-[#111418]"
                    data-icon="Check"
                    data-size="20px"
                    data-weight="regular"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="20px"
                      height="20px"
                      fill="currentColor"
                      viewBox="0 0 256 256"
                    >
                      <path
                        d="M229.66,77.66l-128,128a8,8,0,0,1-11.32,0l-56-56a8,8,0,0,1,11.32-11.32L96,188.69,218.34,66.34a8,8,0,0,1,11.32,11.32Z"
                      ></path>
                    </svg>
                  </div>
                  Ceramic coating
                </div>
                <div
                  class="text-[13px] font-normal leading-normal flex gap-3 text-[#111418]"
                >
                  <div
                    class="text-[#111418]"
                    data-icon="Check"
                    data-size="20px"
                    data-weight="regular"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="20px"
                      height="20px"
                      fill="currentColor"
                      viewBox="0 0 256 256"
                    >
                      <path
                        d="M229.66,77.66l-128,128a8,8,0,0,1-11.32,0l-56-56a8,8,0,0,1,11.32-11.32L96,188.69,218.34,66.34a8,8,0,0,1,11.32,11.32Z"
                      ></path>
                    </svg>
                  </div>
                  Paint protection
                </div>
                <div
                  class="text-[13px] font-normal leading-normal flex gap-3 text-[#111418]"
                >
                  <div
                    class="text-[#111418]"
                    data-icon="Check"
                    data-size="20px"
                    data-weight="regular"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="20px"
                      height="20px"
                      fill="currentColor"
                      viewBox="0 0 256 256"
                    >
                      <path
                        d="M229.66,77.66l-128,128a8,8,0,0,1-11.32,0l-56-56a8,8,0,0,1,11.32-11.32L96,188.69,218.34,66.34a8,8,0,0,1,11.32,11.32Z"
                      ></path>
                    </svg>
                  </div>
                  Exterior beautification
                </div>
                <div
                  class="text-[13px] font-normal leading-normal flex gap-3 text-[#111418]"
                >
                  <div
                    class="text-[#111418]"
                    data-icon="Check"
                    data-size="20px"
                    data-weight="regular"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="20px"
                      height="20px"
                      fill="currentColor"
                      viewBox="0 0 256 256"
                    >
                      <path
                        d="M229.66,77.66l-128,128a8,8,0,0,1-11.32,0l-56-56a8,8,0,0,1,11.32-11.32L96,188.69,218.34,66.34a8,8,0,0,1,11.32,11.32Z"
                      ></path>
                    </svg>
                  </div>
                  Premium interior foam
                </div>
                <div
                  class="text-[13px] font-normal leading-normal flex gap-3 text-[#111418]"
                >
                  <div
                    class="text-[#111418]"
                    data-icon="Check"
                    data-size="20px"
                    data-weight="regular"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="20px"
                      height="20px"
                      fill="currentColor"
                      viewBox="0 0 256 256"
                    >
                      <path
                        d="M229.66,77.66l-128,128a8,8,0,0,1-11.32,0l-56-56a8,8,0,0,1,11.32-11.32L96,188.69,218.34,66.34a8,8,0,0,1,11.32,11.32Z"
                      ></path>
                    </svg>
                  </div>
                  Interior enrichment
                </div>
                <div
                  class="text-[13px] font-normal leading-normal flex gap-3 text-[#111418]"
                >
                  <div
                    class="text-[#111418]"
                    data-icon="Check"
                    data-size="20px"
                    data-weight="regular"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="20px"
                      height="20px"
                      fill="currentColor"
                      viewBox="0 0 256 256"
                    >
                      <path
                        d="M229.66,77.66l-128,128a8,8,0,0,1-11.32,0l-56-56a8,8,0,0,1,11.32-11.32L96,188.69,218.34,66.34a8,8,0,0,1,11.32,11.32Z"
                      ></path>
                    </svg>
                  </div>
                  AC vent cleaning
                </div>
                <div
                  class="text-[13px] font-normal leading-normal flex gap-3 text-[#111418]"
                >
                  <div
                    class="text-[#111418]"
                    data-icon="Check"
                    data-size="20px"
                    data-weight="regular"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="20px"
                      height="20px"
                      fill="currentColor"
                      viewBox="0 0 256 256"
                    >
                      <path
                        d="M229.66,77.66l-128,128a8,8,0,0,1-11.32,0l-56-56a8,8,0,0,1,11.32-11.32L96,188.69,218.34,66.34a8,8,0,0,1,11.32,11.32Z"
                      ></path>
                    </svg>
                  </div>
                  Engine cleaning/polish
                </div>
                <div
                  class="text-[13px] font-normal leading-normal flex gap-3 text-[#111418]"
                >
                  <div
                    class="text-[#111418]"
                    data-icon="Check"
                    data-size="20px"
                    data-weight="regular"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="20px"
                      height="20px"
                      fill="currentColor"
                      viewBox="0 0 256 256"
                    >
                      <path
                        d="M229.66,77.66l-128,128a8,8,0,0,1-11.32,0l-56-56a8,8,0,0,1,11.32-11.32L96,188.69,218.34,66.34a8,8,0,0,1,11.32,11.32Z"
                      ></path>
                    </svg>
                  </div>
                  Windscreen treatment
                </div>
                <div
                  class="text-[13px] font-normal leading-normal flex gap-3 text-[#111418]"
                >
                  <div
                    class="text-[#111418]"
                    data-icon="Check"
                    data-size="20px"
                    data-weight="regular"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="20px"
                      height="20px"
                      fill="currentColor"
                      viewBox="0 0 256 256"
                    >
                      <path
                        d="M229.66,77.66l-128,128a8,8,0,0,1-11.32,0l-56-56a8,8,0,0,1,11.32-11.32L96,188.69,218.34,66.34a8,8,0,0,1,11.32,11.32Z"
                      ></path>
                    </svg>
                  </div>
                  All premium wash services
                </div>
              </div>
            </div>
          </div>
          <h2
            class="text-[#111418] text-[22px] font-bold leading-tight tracking-[-0.015em] px-4 pb-3 pt-5"
          >
            How Our Services Work
          </h2>
          <div class="p-4">
            <div
              class="relative flex items-center justify-center bg-[#111418] bg-cover bg-center aspect-video rounded-xl p-4"
              style="
                background-image: url('https://lh3.googleusercontent.com/aida-public/AB6AXuDcntRQWW2xtta9yljP3JnYpImt3FyKSgCwyS9bWJBKzpR4r16hC2dTJdu7Iz-CIJn1uQ122E5zXr0SU4fJwMYGPDjUmgwyNt3_yJqTXWAPtvYOLIzBPSZcEDqqV12pt4mgVgSKqDW6iwvs0O4tG2BiMWCP2Gqj4uCnX-z9djXdKo2zTqgU9HXwRidq0CkMWDQ3ni86xPFuO12sn4w1_V7HRA4BhxOQqrRK4MQSdwn7ylGQjSDErUK-RaEZbEFlBmX1pVAvDvTku_F0');
              "
            >
              <button
                class="flex shrink-0 items-center justify-center rounded-full size-16 bg-black/40 text-white"
              >
                <div
                  class="text-inherit"
                  data-icon="Play"
                  data-size="24px"
                  data-weight="fill"
                >
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="24px"
                    height="24px"
                    fill="currentColor"
                    viewBox="0 0 256 256"
                  >
                    <path
                      d="M240,128a15.74,15.74,0,0,1-7.6,13.51L88.32,229.65a16,16,0,0,1-16.2.3A15.86,15.86,0,0,1,64,216.13V39.87a15.86,15.86,0,0,1,8.12-13.82,16,16,0,0,1,16.2.3L232.4,114.49A15.74,15.74,0,0,1,240,128Z"
                    ></path>
                  </svg>
                </div>
              </button>
            </div>
          </div>
          <h2
            class="text-[#111418] text-[22px] font-bold leading-tight tracking-[-0.015em] px-4 pb-3 pt-5"
          >
            Contact Us
          </h2>
          <div class="flex max-w-[480px] flex-wrap items-end gap-4 px-4 py-3">
            <label class="flex flex-col min-w-40 flex-1">
              <p
                class="text-[#111418] text-base font-medium leading-normal pb-2"
              >
                Name
              </p>
              <input
                placeholder="Your Name"
                class="form-input flex w-full min-w-0 flex-1 resize-none overflow-hidden rounded-xl text-[#111418] focus:outline-0 focus:ring-0 border border-[#dcdfe5] bg-white focus:border-[#dcdfe5] h-14 placeholder:text-[#637288] p-[15px] text-base font-normal leading-normal"
                value=""
              />
            </label>
          </div>
          <div class="flex max-w-[480px] flex-wrap items-end gap-4 px-4 py-3">
            <label class="flex flex-col min-w-40 flex-1">
              <p
                class="text-[#111418] text-base font-medium leading-normal pb-2"
              >
                Email
              </p>
              <input
                placeholder="Your Email"
                class="form-input flex w-full min-w-0 flex-1 resize-none overflow-hidden rounded-xl text-[#111418] focus:outline-0 focus:ring-0 border border-[#dcdfe5] bg-white focus:border-[#dcdfe5] h-14 placeholder:text-[#637288] p-[15px] text-base font-normal leading-normal"
                value=""
              />
            </label>
          </div>
          <div class="flex max-w-[480px] flex-wrap items-end gap-4 px-4 py-3">
            <label class="flex flex-col min-w-40 flex-1">
              <p
                class="text-[#111418] text-base font-medium leading-normal pb-2"
              >
                Phone
              </p>
              <input
                placeholder="Your Phone"
                class="form-input flex w-full min-w-0 flex-1 resize-none overflow-hidden rounded-xl text-[#111418] focus:outline-0 focus:ring-0 border border-[#dcdfe5] bg-white focus:border-[#dcdfe5] h-14 placeholder:text-[#637288] p-[15px] text-base font-normal leading-normal"
                value=""
              />
            </label>
          </div>
          <div class="flex max-w-[480px] flex-wrap items-end gap-4 px-4 py-3">
            <label class="flex flex-col min-w-40 flex-1">
              <p
                class="text-[#111418] text-base font-medium leading-normal pb-2"
              >
                Subject
              </p>
              <input
                placeholder="Subject"
                class="form-input flex w-full min-w-0 flex-1 resize-none overflow-hidden rounded-xl text-[#111418] focus:outline-0 focus:ring-0 border border-[#dcdfe5] bg-white focus:border-[#dcdfe5] h-14 placeholder:text-[#637288] p-[15px] text-base font-normal leading-normal"
                value=""
              />
            </label>
          </div>
          <div class="flex max-w-[480px] flex-wrap items-end gap-4 px-4 py-3">
            <label class="flex flex-col min-w-40 flex-1">
              <p
                class="text-[#111418] text-base font-medium leading-normal pb-2"
              >
                Message
              </p>
              <textarea
                placeholder="Your Message"
                class="form-input flex w-full min-w-0 flex-1 resize-none overflow-hidden rounded-xl text-[#111418] focus:outline-0 focus:ring-0 border border-[#dcdfe5] bg-white focus:border-[#dcdfe5] min-h-36 placeholder:text-[#637288] p-[15px] text-base font-normal leading-normal"
              ></textarea>
            </label>
          </div>
          <div class="flex px-4 py-3 justify-start">
            <button
              class="flex min-w-[84px] max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-full h-10 px-4 bg-[#196be5] text-white text-sm font-bold leading-normal tracking-[0.015em]"
            >
              <span class="truncate">Submit</span>
            </button>
          </div>
          <h2
            class="text-[#111418] text-[22px] font-bold leading-tight tracking-[-0.015em] px-4 pb-3 pt-5"
          >
            Download Our App
          </h2>
          <div class="flex w-full grow bg-white @container p-4">
            <div
              class="w-full gap-1 overflow-hidden bg-white @[480px]:gap-2 aspect-[3/2] rounded-xl flex"
            >
              <div
                class="w-full bg-center bg-no-repeat bg-cover aspect-auto rounded-none flex-1"
                style="
                  background-image: url('https://lh3.googleusercontent.com/aida-public/AB6AXuDhn0SYWKHbcYasE681OfKwisPpiOEc25aqWbPX9FDH3ctaDygZ-xC4nzRTvruDzRAYE3h6OM3hR56n_1MEusqjzUEl0ZD4pjsNxzsUd7SEdyDaWSfcWDp-n139j6mAJLB2U7jY9xDhql7vPtsiSdMgk2SIrPGgIjpw_ThB4l49I6iYANmhn0gipa-xUuhfQTo365DPCicfF4ymZ6hYQSc5xTb2duzU5U4uNNvAZtI7-zjRltw7WiiVfEyOxznqdObQ3SCp0gUrUT-y');
                "
              ></div>
            </div>
          </div>
          <div class="flex justify-center">
            <div
              class="flex flex-1 gap-3 flex-wrap px-4 py-3 max-w-[480px] justify-center"
            >
              <button
                class="flex min-w-[84px] max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-full h-10 px-4 bg-[#196be5] text-white text-sm font-bold leading-normal tracking-[0.015em] grow"
              >
                <span class="truncate">Download on App Store</span>
              </button>
              <button
                class="flex min-w-[84px] max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-full h-10 px-4 bg-[#196be5] text-white text-sm font-bold leading-normal tracking-[0.015em] grow"
              >
                <span class="truncate">Get it on Play Store</span>
              </button>
            </div>
          </div>
          <h2
            class="text-[#111418] text-[22px] font-bold leading-tight tracking-[-0.015em] px-4 pb-3 pt-5"
          >
            FAQ
          </h2>
          <div class="flex flex-col p-4 gap-3">
            <details
              class="flex flex-col rounded-xl border border-[#dcdfe5] bg-white px-[15px] py-[7px] group"
              open=""
            >
              <summary
                class="flex cursor-pointer items-center justify-between gap-6 py-2"
              >
                <p class="text-[#111418] text-sm font-medium leading-normal">
                  What types of vehicles do you service?
                </p>
                <div
                  class="text-[#111418] group-open:rotate-180"
                  data-icon="CaretDown"
                  data-size="20px"
                  data-weight="regular"
                >
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="20px"
                    height="20px"
                    fill="currentColor"
                    viewBox="0 0 256 256"
                  >
                    <path
                      d="M213.66,101.66l-80,80a8,8,0,0,1-11.32,0l-80-80A8,8,0,0,1,53.66,90.34L128,164.69l74.34-74.35a8,8,0,0,1,11.32,11.32Z"
                    ></path>
                  </svg>
                </div>
              </summary>
              <p class="text-[#637288] text-sm font-normal leading-normal pb-2">
                We service cars, bikes, and scooters.
              </p>
            </details>
            <details
              class="flex flex-col rounded-xl border border-[#dcdfe5] bg-white px-[15px] py-[7px] group"
            >
              <summary
                class="flex cursor-pointer items-center justify-between gap-6 py-2"
              >
                <p class="text-[#111418] text-sm font-medium leading-normal">
                  How do I book a wash?
                </p>
                <div
                  class="text-[#111418] group-open:rotate-180"
                  data-icon="CaretDown"
                  data-size="20px"
                  data-weight="regular"
                >
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="20px"
                    height="20px"
                    fill="currentColor"
                    viewBox="0 0 256 256"
                  >
                    <path
                      d="M213.66,101.66l-80,80a8,8,0,0,1-11.32,0l-80-80A8,8,0,0,1,53.66,90.34L128,164.69l74.34-74.35a8,8,0,0,1,11.32,11.32Z"
                    ></path>
                  </svg>
                </div>
              </summary>
              <p class="text-[#637288] text-sm font-normal leading-normal pb-2">
                We service cars, bikes, and scooters.
              </p>
            </details>
            <details
              class="flex flex-col rounded-xl border border-[#dcdfe5] bg-white px-[15px] py-[7px] group"
            >
              <summary
                class="flex cursor-pointer items-center justify-between gap-6 py-2"
              >
                <p class="text-[#111418] text-sm font-medium leading-normal">
                  What equipment do you use?
                </p>
                <div
                  class="text-[#111418] group-open:rotate-180"
                  data-icon="CaretDown"
                  data-size="20px"
                  data-weight="regular"
                >
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="20px"
                    height="20px"
                    fill="currentColor"
                    viewBox="0 0 256 256"
                  >
                    <path
                      d="M213.66,101.66l-80,80a8,8,0,0,1-11.32,0l-80-80A8,8,0,0,1,53.66,90.34L128,164.69l74.34-74.35a8,8,0,0,1,11.32,11.32Z"
                    ></path>
                  </svg>
                </div>
              </summary>
              <p class="text-[#637288] text-sm font-normal leading-normal pb-2">
                We service cars, bikes, and scooters.
              </p>
            </details>
          </div>
        </div>
      </div>
      <footer class="flex justify-center">
        <div class="flex max-w-[960px] flex-1 flex-col">
          <footer class="flex flex-col gap-6 px-5 py-10 text-center @container">
            <div
              class="flex flex-wrap items-center justify-center gap-6 @[480px]:flex-row @[480px]:justify-around"
            >
              <a
                class="text-[#637288] text-base font-normal leading-normal min-w-40"
                href="#"
                >Services</a
              >
              <a
                class="text-[#637288] text-base font-normal leading-normal min-w-40"
                href="#"
                >Pricing</a
              >
              <a
                class="text-[#637288] text-base font-normal leading-normal min-w-40"
                href="#"
                >Contact</a
              >
            </div>
            <p class="text-[#637288] text-base font-normal leading-normal">
              @2023 SUTING. All rights reserved.
            </p>
          </footer>
        </div>
      </footer>
    </div>
  </div>
</template>

<script setup>
import HeaderBar from "@/components/Header.vue";
</script>
