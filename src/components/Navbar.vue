<template>
  <nav
    class="flex items-center flex-wrap #f8fafc border-b-2 border-slate-400 divide-x-2"
  >
    <div
      class="flex items-center flex-shrink-0 divide-slate-400 text-lg #0f172a p-6 lg:w-1/5"
    >
      <h1 class="font-extrabold text-2xl tracking-tight">Gogana</h1>
    </div>
    <div class="block lg:hidden">
      <button
        class="flex items-center px-3 py-2 border rounded text-black border-gray-600 hover:text-white hover:border-white"
      >
        <svg
          class="fill-current h-3 w-3"
          viewBox="0 0 20 20"
          xmlns="http://www.w3.org/2000/svg"
        >
          <title>Menu</title>
          <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z" />
        </svg>
      </button>
    </div>
    <div class="lg:flex lg:items-center lg:w-4/5">
      <div class="text-2xl pl-6 font-extrabold lg:flex-grow">
        <a
          href="#"
          class="block mt-4 lg:inline-block lg:mt-0 text-black hover:text-white mr-4"
        >
          Dashboard
        </a>
      </div>
      <div class="w-3/5">
        <form class="w-3/5">
          <label for="simple-search" class="sr-only">Search</label>
          <div class="relative w-full">
            <div
              class="absolute inset-y-0 left-0 flex items-center pl-3 pointer-events-none"
            >
              <svg
                aria-hidden="true"
                class="w-5 h-5 text-gray-500 dark:text-gray-400"
                fill="currentColor"
                viewBox="0 0 20 20"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  fill-rule="evenodd"
                  d="M8 4a4 4 0 100 8 4 4 0 000-8zM2 8a6 6 0 1110.89 3.476l4.817 4.817a1 1 0 01-1.414 1.414l-4.816-4.816A6 6 0 012 8z"
                  clip-rule="evenodd"
                ></path>
              </svg>
            </div>
            <input
              type="text"
              id="simple-search"
              class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-3xl focus:ring-blue-500 focus:border-blue-500 block w-full pl-10 p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
              placeholder="Search here..."
              required
            />
          </div>
        </form>
      </div>
      <div>
        <button
          id="dropdownNotificationButton"
          data-dropdown-toggle="dropdownNotification"
          class="inline-flex items-center text-sm font-medium text-center text-gray-500 hover:text-gray-900 focus:outline-none dark:hover:text-white dark:text-gray-400"
          type="button"
        >
          <svg
            class="w-12 h-12 p-1 rounded-full ring-2 ring-gray-300 dark:ring-gray-500"
            aria-hidden="true"
            fill="currentColor"
            viewBox="0 0 20 20"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M10 2a6 6 0 00-6 6v3.586l-.707.707A1 1 0 004 14h12a1 1 0 00.707-1.707L16 11.586V8a6 6 0 00-6-6zM10 18a3 3 0 01-3-3h6a3 3 0 01-3 3z"
            ></path>
          </svg>
          <div class="relative flex">
            <div
              class="relative inline-flex w-3 h-3 bg-red-500 border-2 border-white rounded-full -top-2 right-3 dark:border-gray-900"
            ></div>
          </div>
        </button>
      </div>
      <div class="flex items-center justify-between pr-6">
        <div class="px-5">
          <h1 class="font-bold">Alex Mora</h1>
          <h2>Super Admin</h2>
        </div>
        <img
          class="w-12 h-12 p-1 rounded-full ring-2 ring-gray-300 dark:ring-gray-500"
          src="./images/logo.svg"
          alt="Rounded avatar"
        />
      </div>
    </div>
  </nav>
</template>
