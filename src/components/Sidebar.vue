<script></script>
<template>
  <aside
    id="separator-sidebar"
    class="top-0 left-0 z-40 h-screen transition-transform -translate-x-full sm:translate-x-0"
    aria-label="Sidebar"
  >
    <div
      class="h-screen px-3 py-10 overflow-y-auto dark:bg-gray-800 border-r-2 flex justify-between flex-col"
    >
      <div>
        <ul class="space-y-6">
          <button class="w-full">
            <li>
              <a
                href="#"
                class="flex items-center p-2 text-base font-normal text-gray-900 rounded-lg dark:text-white hover:bg-blue-400 active:bg-violet-700 dark:hover:bg-gray-700"
              >
                <svg
                  aria-hidden="true"
                  class="w-6 h-6 text-gray-500 transition duration-75 dark:text-gray-400 group-hover:text-gray-900 dark:group-hover:text-white"
                  fill="currentColor"
                  viewBox="0 0 20 20"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path d="M2 10a8 8 0 018-8v8h8a8 8 0 11-16 0z"></path>
                  <path d="M12 2.252A8.014 8.014 0 0117.748 8H12V2.252z"></path>
                </svg>
                <span class="ml-3">Dashboard</span>
              </a>
            </li>
          </button>
          <button class="w-full">
            <li>
              <a
                href="#"
                class="flex items-center p-2 text-base font-normal text-gray-900 rounded-lg dark:text-white hover:bg-blue-400 active:bg-violet-700 dark:hover:bg-gray-700"
              >
                <!-- svg for statistics -->
                <svg
                  aria-hidden="true"
                  class="w-6 h-6 text-gray-500 transition duration-75 dark:text-gray-400 group-hover:text-gray-900 dark:group-hover:text-white"
                  fill="currentColor"
                  viewBox="0 0 20 20"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    fill-rule="evenodd"
                    d="M3 3a1 1 0 011-1h12a1 1 0 011 1v12a1 1 0 01-1 1H4a1 1 0 01-1-1V3zm3 2a1 1 0 00-1 1v6a1 1 0 102 0V6a1 1 0 00-1-1zm4 0a1 1 0 00-1 1v8a1 1 0 102 0V6a1 1 0 00-1-1zm4 0a1 1 0 00-1 1v4a1 1 0 102 0V6a1 1 0 00-1-1z"
                    clip-rule="evenodd"
                  ></path>
                </svg>
                <span class="ml-3">Statistics</span>
              </a>
            </li>
          </button>
          <button class="w-full">
            <li>
              <a
                href="#"
                class="flex items-center p-2 text-base font-normal text-gray-900 rounded-lg dark:text-white hover:bg-blue-400 active:bg-violet-700 dark:hover:bg-gray-700"
              >
                <svg
                  aria-hidden="true"
                  class="w-6 h-6 text-gray-500 transition duration-75 dark:text-gray-400 group-hover:text-gray-900 dark:group-hover:text-white"
                  fill="currentColor"
                  viewBox="0 0 20 20"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <!-- path for dollar sign  -->

                  <path
                    fill-rule="evenodd"
                    clip-rule="evenodd"
                    d="M7.25 5.52C6.33 6.67 6 8.19 6 10c0 2.76 2.24 5 5 5 .92 0 1.76-.26 2.5-.69V17h-2v-2.31c-.17-.03-.33-.06-.5-.06-1.67 0-3-1.34-3-3 0-.83.34-1.59.88-2.13L7.25 5.52zM10 14c-1.1 0-2-.9-2-2s.9-2 2-2 2 .9 2 2-.9 2-2 2z"
                  ></path>
                </svg>

                <span class="ml-3">Payment</span>
              </a>
            </li>
          </button>
          <button class="w-full">
            <li>
              <a
                href="#"
                class="flex items-center p-2 text-base font-normal text-gray-900 rounded-lg dark:text-white hover:bg-blue-400 active:bg-violet-700 dark:hover:bg-gray-700"
              >
                <!-- svg for transaction -->
                <svg
                  aria-hidden="true"
                  class="w-6 h-6 text-gray-500 transition duration-75 dark:text-gray-400 group-hover:text-gray-900 dark:group-hover:text-white"
                  fill="currentColor"
                  viewBox="0 0 20 20"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    fill-rule="evenodd"
                    d="M3 3a1 1 0 011-1h12a1 1 0 011 1v12a1 1 0 01-1 1H4a1 1 0 01-1-1V3zm3 2a1 1 0 00-1 1v6a1 1 0 102 0V6a1 1 0 00-1-1zm4 0a1 1 0 00-1 1v8a1 1 0 102 0V6a1 1 0 00-1-1zm4 0a1 1 0 00-1 1v4a1 1 0 102 0V6a1 1 0 00-1-1z"
                    clip-rule="evenodd"
                  ></path>
                </svg>
                <span class="ml-3">Transactions</span>
              </a>
            </li>
          </button>
          <button class="w-full">
            <li>
              <a
                href="#"
                class="flex items-center p-2 text-base font-normal text-gray-900 rounded-lg dark:text-white hover:bg-blue-400 active:bg-violet-700 dark:hover:bg-gray-700"
              >
                <!-- svg for products -->
                <svg
                  aria-hidden="true"
                  class="w-6 h-6 text-gray-500 transition duration-75 dark:text-gray-400 group-hover:text-gray-900 dark:group-hover:text-white"
                  fill="currentColor"
                  viewBox="0 0 20 20"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    fill-rule="evenodd"
                    d="M3 3a1 1 0 011-1h12a1 1 0 011 1v12a1 1 0 01-1 1H4a1 1 0 01-1-1V3zm3 2a1 1 0 00-1 1v6a1 1 0 102 0V6a1 1 0 00-1-1zm4 0a1 1 0 00-1 1v8a1 1 0 102 0V6a1 1 0 00-1-1zm4 0a1 1 0 00-1 1v4a1 1 0 102 0V6a1 1 0 00-1-1z"
                    clip-rule="evenodd"
                  ></path>
                </svg>
                <span class="ml-3">Products</span>
              </a>
            </li>
          </button>
          <button class="w-full">
            <li>
              <a
                href="#"
                class="flex items-center p-2 text-base font-normal text-gray-900 rounded-lg dark:text-white hover:bg-blue-400 active:bg-violet-700 dark:hover:bg-gray-700"
              >
                <!-- svg for a customer -->
                <svg
                  aria-hidden="true"
                  class="w-6 h-6 text-gray-500 transition duration-75 dark:text-gray-400 group-hover:text-gray-900 dark:group-hover:text-white"
                  fill="currentColor"
                  viewBox="0 0 20 20"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <!-- give me a path for a customer  -->
                  <path
                    fill-rule="evenodd"
                    d="M3 3a1 1 0 011-1h12a1 1 0 011 1v12a1 1 0 01-1 1H4a1 1 0 01-1-1V3zm3 2a1 1 0 00-1 1v6a1 1 0 102 0V6a1 1 0 00-1-1zm4 0a1 1 0 00-1 1v8a1 1 0 102 0V6a1 1 0 00-1-1zm4 0a1 1 0 00-1 1v4a1 1 0 102 0V6a1 1 0 00-1-1z"
                    clip-rule="evenodd"
                  ></path>
                </svg>
                <span class="ml-3">Customers</span>
              </a>
            </li>
          </button>
          <button class="w-full">
            <li>
              <a
                href="#"
                class="flex items-center p-2 text-base font-normal text-gray-900 rounded-lg dark:text-white hover:bg-blue-400 active:bg-violet-700 dark:hover:bg-gray-700"
              >
                <!-- svg for messages -->
                <svg
                  aria-hidden="true"
                  class="w-6 h-6 text-gray-500 transition duration-75 dark:text-gray-400 group-hover:text-gray-900 dark:group-hover:text-white"
                  fill="currentColor"
                  viewBox="0 0 20 20"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    fill-rule="evenodd"
                    d="M3 3a1 1 0 011-1h12a1 1 0 011 1v12a1 1 0 01-1 1H4a1 1 0 01-1-1V3zm3 2a1 1 0 00-1 1v6a1 1 0 102 0V6a1 1 0 00-1-1zm4 0a1 1 0 00-1 1v8a1 1 0 102 0V6a1 1 0 00-1-1zm4 0a1 1 0 00-1 1v4a1 1 0 102 0V6a1 1 0 00-1-1z"
                    clip-rule="evenodd"
                  ></path>
                </svg>
                <span class="ml-3">Messages</span>
              </a>
            </li>
          </button>
        </ul>
      </div>
      <div>
        <ul
          class="pt-4 mt-4 space-y-2 border-t border-gray-200 dark:border-gray-700"
        >
          <li>
            <a
              href="#"
              class="flex items-center p-2 text-base font-normal text-gray-900 transition duration-75 rounded-lg hover:bg-gray-100 dark:hover:bg-gray-700 dark:text-white group"
            >
              <svg
                aria-hidden="true"
                class="flex-shrink-0 w-5 h-5 text-gray-500 transition duration-75 group-hover:text-gray-900 dark:group-hover:text-white dark:text-gray-400"
                focusable="false"
                data-prefix="fas"
                data-icon="gem"
                role="img"
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 512 512"
              >
                <!-- ///path for settings -->

                <path
                  fill="currentColor"
                  d="M256 8C119.033 8 8 119.033 8
                256s111.033 248 248 248 248-111.033 248-248S392.967 8 256 8zm0
                448c-110.28 0-200-89.72-200-200S145.72 56 256 56s200 89.72 200
                200-89.72 200-200 200zm0-304c-44.183 0-80 35.817-80 80s35.817 80
                80 80 80-35.817 80-80-35.817-80-80-80zm0 128c-22.056
                0-40-17.944-40-40s17.944-40 40-40 40 17.944 40 40-17.944 40-40
                40z"
                ></path>
              </svg>
              <span class="ml-4">Settings</span>
            </a>
          </li>
          <li>
            <a
              href="#"
              class="flex items-center p-2 text-base font-normal text-gray-900 transition duration-75 rounded-lg hover:bg-gray-100 dark:hover:bg-gray-700 dark:text-white group"
            >
              <!-- svg for logout -->
              <svg
                aria-hidden="true"
                class="flex-shrink-0 w-5 h-5 text-gray-500 transition duration-75 group-hover:text-gray-900 dark:group-hover:text-white dark:text-gray-400"
                focusable="false"
                data-prefix="fas"
                data-icon="sign-out-alt"
                role="img"
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 512 512"
              >
                <path
                  fill="currentColor"
                  d="M416 256c0 17.673-14.327 32-32
                32H192v96c0 17.673-14.327 32-32 32s-32-14.327-32-32v-96H32c-17.673
                0-32-14.327-32-32s14.327-32 32-32h128V96c0-17.673 14.327-32 32-32s32
                14.327 32 32v96h160c17.673 0 32 14.327 32 32zm-32 0H192v96h192v-96zm-96
                0H32v96h160v-96zm-32-96c0-17.673 14.327-32 32-32h160c17.673
                0 32 14.327 32 32s-14.327 32-32 32H224c-17.673 0-32-14.327-32-32zm32
                0h160v96H224v-96z"
                ></path>
              </svg>
              <span class="ml-4">Logout</span>
            </a>
          </li>
        </ul>
      </div>
    </div>
  </aside>
</template>
