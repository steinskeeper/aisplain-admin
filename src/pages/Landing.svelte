<script>
  // @ts-nocheck
  import store from "../store";
  import toast, { Toaster } from "svelte-french-toast";
  import Navbar from "./components/Navbar.svelte";
  import step1 from "../assets/step1.png";
  import step2 from "../assets/step2.png";
  import guide from "../assets/guide.png";
  import frontdesk from "../assets/frontdesk.png";
  import elevate from "../assets/06.png";
  import plug from "../assets/plug.png";
  import complex from "../assets/09.png";
  import bounce from "../assets/05.png";
  import { push } from "svelte-spa-router";
</script>

<Toaster />

<section class="mx-auto h-full min-h-screen max-w-screen-md p-10">
  <Navbar />
  <div class="mt-20 flex gap-5 flex-col">
    <div class="text-5xl">Experience Your Website Come Alive</div>
    <div class="text-xl">
      AI-Splain is a website plugin that Speaks! It Empowers your website with an Autonomous Sales Guide, effortlessly narrating and auto-scrolling your content.
    </div>

    <div class="text-3xl mt-10">Why is AI-Splain required?</div>
    <div class="grid gap-4">
      <div class="flex-col flex gap-3">
        <div class="flex gap-3 items-center">
          <div
            class="w-10 h-10 flex items-center justify-center font-bold text-xl rounded-xl text-indigo-600 bg-indigo-100"
          >
            1
          </div>
          <div class="text-2xl">Elevate Your Landing Page Experience</div>
        </div>
        <img src={elevate} class="rounded-xl" alt="" />
        <div>
          Landing pages are vital for any business. Visuals alone aren't enough to capture user attention. A vocal guide enhances the visitor experience and engagement significantly.
        </div>
      </div>
      <div class="flex-col flex gap-3">
        <div class="flex gap-3 items-center">
          <div
            class="w-10 h-10 flex items-center justify-center font-bold text-xl rounded-xl text-indigo-600 bg-indigo-100"
          >
            2
          </div>
          <div class="text-2xl">Cut through complexity</div>
        </div>
        <img src={complex} class="rounded-xl" alt="" />
        <div>
          Landing pages can be overwhelming to navigate, as they are packed with vital information that businesses don't want customers to miss.
        </div>
      </div>
      <div class="flex-col flex gap-3">
        <div class="flex gap-3 items-center">
          <div
            class="w-10 h-10 flex items-center justify-center font-bold text-xl rounded-xl text-indigo-600 bg-indigo-100"
          >
            3
          </div>
          <div class="text-2xl">Reduce bounce rate</div>
        </div>
        <img src={bounce} class="rounded-xl" alt="" />
        <div>
          Landing pages often experience a high bounce rate, especially when visitors are left to navigate on their own without clear guidance.
        </div>
      </div>
    </div>
    <div class="text-3xl mt-10">What does Ai-Splain deliver?</div>
    <div class="grid gap-4">
      <div class="flex-col flex gap-3">
        <div class="flex gap-3 items-center">
          <div
            class="w-10 h-10 flex items-center justify-center font-bold text-xl rounded-xl text-yellow-600 bg-yellow-100"
          >
            1
          </div>
          <div class="text-2xl">Guided Walkthrough Voice Assistant</div>
        </div>
        <img src={guide} class="rounded-xl" alt="" />
        <div>
          AI-Splain allows you to add a guided voice that walks your visitors through your landing page. The assistant auto generates the script based on the content of your landing page.
        </div>
      </div>
      <div class="flex-col flex gap-3">
        <div class="flex gap-3 items-center">
          <div
            class="w-10 h-10 flex items-center justify-center font-bold text-xl rounded-xl text-yellow-600 bg-yellow-100"
          >
            2
          </div>
          <div class="text-2xl">Frontdesk for Your Landing Page</div>
        </div>
        <img src={frontdesk} class="rounded-xl" alt="" />
        <div>
          Provide our assistant with your essential business knowledge, and it will engage your visitors in interactive conversation sessions.
        </div>
      </div>
      <div class="flex-col flex gap-3">
        <div class="flex gap-3 items-center">
          <div
            class="w-10 h-10 flex items-center justify-center font-bold text-xl rounded-xl text-yellow-600 bg-yellow-100"
          >
            3
          </div>
          <div class="text-2xl">Plug and Play</div>
        </div>
        <img src={plug} class="rounded-xl" alt="" />
        <div>
          Add the AI-Splain widget to any website with a single line of code and it works out of the box.
        </div>
      </div>
    </div>
    <div class="mt-10">
      <div class="text-3xl">How to does it work?</div>
      <div class="mt-7 flex flex-col">
        <div class="flex gap-3 items-center">
          <div
            class="w-10 h-10 flex items-center justify-center font-bold text-xl rounded-xl text-teal-600 bg-teal-100"
          >
            1
          </div>
          <div class="text-xl">
            Manage your apps and get your API key from the dashboard
          </div>
        </div>
        <div class="my-7">
          <img src={step1} class="rounded-xl" alt="" />
        </div>
      </div>
      <div class="mt-7 flex flex-col">
        <div class="flex gap-3 items-center">
          <div
            class="w-10 h-10 flex items-center justify-center font-bold text-xl rounded-xl text-teal-600 bg-teal-100"
          >
            2
          </div>
          <div class="text-xl">
            Add required files to enable Ai-Splain your website source
          </div>
        </div>
        <div class="mockup-code mt-6">
          <pre data-prefix=""><code
              >{`<script apikey="<replace with your key>" src="dist.js" />`}</code
            ></pre>
        </div>
      </div>
      <div class="mt-7 flex flex-col">
        <div class="flex gap-3 items-center">
          <div
            class="w-10 h-10 flex items-center justify-center font-bold text-xl rounded-xl text-teal-600 bg-teal-100"
          >
            3
          </div>
          <div class="text-xl">
            Your are all set! Ai-Splain will now be available on your website
          </div>
        </div>
        <div class="my-4 flex items-center justify-center">
          <img
            src="https://media.tenor.com/S9ohrGPEfYUAAAAd/plieger-celebration.gif"
            alt=""
            class="w-1/2"
          />
        </div>
      </div>
    </div>
    <div class="mt-10">
      <div class="text-xl">
        A small price to pay for 100x customer excitement
      </div>
      <div class="grid grid-cols-3 gap-4 mt-5">
        <div class="border p-3 flex flex-col rounded-xl">
          <div class="font-semibold text-4xl">$5</div>
          <div class="my-3 font-semibold opacity-50">Hustler's Plan</div>
          <div class="flex flex-col gap-3">
            <div class="text-sm">Ingress traffic 0-10k</div>
          </div>
        </div>
        <div class="border p-3 flex flex-col rounded-xl">
          <div class="font-semibold text-4xl">$15</div>
          <div class="my-3 font-semibold opacity-50">Growth Plan</div>
          <div class="flex flex-col gap-3">
            <div class="text-sm">Ingress traffic 10-50k</div>
          </div>
        </div>
        <div class="border p-3 flex flex-col rounded-xl">
          <div class="font-semibold text-3xl">Let's Talk</div>
          <div class="my-3 font-semibold opacity-50">Companies</div>
          <div class="flex flex-col gap-3">
            <div class="text-sm">Ingress traffic >50k</div>
          </div>
        </div>
      </div>
    </div>
    <div class="mt-10">
      <button
        on:click={() => {
          push("/docs");
        }}
        class="flex gap-3 items-center hover:scale-95 transition-all"
      >
        <div class="text-xl">View documentations</div>
        <div>
          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke-width="1.5"
            stroke="currentColor"
            class="w-4 h-4"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M4.5 19.5l15-15m0 0H8.25m11.25 0v11.25"
            />
          </svg>
        </div>
      </button>
    </div>
  </div>
</section>
