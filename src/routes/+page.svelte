<main class="grid h-screen w-full place-content-center bg-[#121212]">
  <div class="w-[70rem] flex-grow grid grid-cols-3 place-content-center gap-8">
    <div class="flex flex-col col-span-2 gap-8 h-full">
      <!-- Project Breadth -->
      <div
        class="flex flex-col gap-4 border-2 border-indigo-500 rounded-xl p-8 h-min"
      >
        <div class="pb-4">
          <h2 class=" font-bold text-4xl uppercase text-indigo-500">
            Project Breadth
          </h2>
          <h3 class="text-white text-lg pt-2">
            Select the components that make up your project
          </h3>
        </div>
        <div class="flex flew-row flex-wrap gap-2">
          <div
            class="tooltip tooltip-accent tooltip-bottom font-bold"
            data-tip="The home of your site, the first thing people see."
          >
            <button class="btn rounded-full">Landing Page</button>
          </div>
          <div
            class="tooltip tooltip-accent tooltip-bottom font-bold"
            data-tip="The home of your site, the first thing people see."
          >
            <button class="btn rounded-full">Internal Software</button>
          </div>
          <div
            class="tooltip tooltip-accent tooltip-bottom font-bold"
            data-tip="The home of your site, the first thing people see."
          >
            <button class="btn rounded-full">Online Store</button>
          </div>
          <div
            class="tooltip tooltip-accent tooltip-bottom font-bold"
            data-tip="The home of your site, the first thing people see."
          >
            <button class="btn rounded-full">Management Page</button>
          </div>
          <div
            class="tooltip tooltip-accent tooltip-bottom font-bold"
            data-tip="The home of your site, the first thing people see."
          >
            <button class="btn rounded-full">User Accounts</button>
          </div>
          <div
            class="tooltip tooltip-accent tooltip-bottom font-bold"
            data-tip="The home of your site, the first thing people see."
          >
            <button class="btn rounded-full">Intake Page</button>
          </div>
          <div
            class="tooltip tooltip-accent tooltip-bottom font-bold"
            data-tip="The home of your site, the first thing people see."
          >
            <button class="btn rounded-full">Portfolio</button>
          </div>
        </div>
      </div>

      <div
        class="flex flex-col gap-4 border-2 border-violet-500 rounded-xl p-8 h-min flex-grow"
      >
        <div class="pb-4">
          <h2 class=" font-bold text-4xl uppercase text-violet-500">
            Project Description
          </h2>
          <h3 class="text-white text-lg pt-2">
            Describe the project you want to build. What do you want your
            project to do?
          </h3>
        </div>
        <textarea
          class="textarea h-full"
          placeholder="Blog to keep my fans updated while I'm exploring Pluto..."
        />
      </div>
    </div>
    <div class="flex flex-col gap-8">
      <div
        class="flex flex-col gap-4 border-2 border-purple-500 rounded-xl p-8 flex-grow"
      >
        <h2 class=" font-bold text-4xl uppercase text-purple-500 pb-4">
          About You
        </h2>
        <div class="form-control w-full max-w-xs">
          <select class="select select-bordered rounded-lg">
            <option disabled selected>Who are you?</option>
            <option>Individual</option>
            <option>Small Business</option>
            <option>Bigger Business</option>
          </select>
        </div>
        <input
          type="text"
          placeholder="Business Name"
          class="input w-full max-w-xs"
        />
        <input
          type="text"
          placeholder="Full Name"
          class="input w-full max-w-xs"
        />
        <input
          type="text"
          placeholder="Email Address"
          class="input w-full max-w-xs"
        />
        <input
          type="text"
          placeholder="Phone Number"
          class="input w-full max-w-xs"
        />
      </div>
      <button
        class="flex flex-col gap-4 bg-gradient-to-r from-purple-500 bg-pink-500 rounded-xl p-8"
      >
        <h2 class=" font-bold text-4xl uppercase text-black text-center w-full">
          Submit
        </h2>
      </button>
    </div>
  </div>
</main>
