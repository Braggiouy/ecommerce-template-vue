<template>
  <div class="flex flex-col bg-coolGray-50 text-coolGray-800">
    <h2 class="text-xl font-semibold">Your cart</h2>
    <ul class="flex flex-col divide-y divide-coolGray-300">
      <!-- ITEM 1 -->
      <li class="flex flex-col py-6">
        <div class="flex p-1">
          <img
            class="
              flex-shrink-0
              object-cover
              w-20
              h-20
              border-transparent
              rounded
              outline-none
              bg-coolGray-500
            "
            src="https://images.unsplash.com/photo-1526170375885-4d8ecf77b99f?ixlib=rb-1.2.1&amp;ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;auto=format&amp;fit=crop&amp;w=1350&amp;q=80"
            alt="Polaroid camera"
          />
          <div class="flex flex-col justify-between w-full p-1">
            <div class="flex justify-between w-full">
              <div class="">
                <h3 class="text-lg font-semibold">Polaroid camera</h3>
                <p class="text-sm text-coolGray-600">Classic</p>
              </div>
              <div class="text-right">
                <p class="text-lg font-semibold">59.99€</p>
                <p class="text-sm line-through text-coolGray-400">75.50€</p>
              </div>
            </div>
            <div class="flex text-sm divide-x">
              <button
                type="button"
                class="flex items-center px-2 py-1 pl-0 space-x-1"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 512 512"
                  class="w-4 h-4 fill-current"
                >
                  <path
                    d="M96,472a23.82,23.82,0,0,0,23.579,24H392.421A23.82,23.82,0,0,0,416,472V152H96Zm32-288H384V464H128Z"
                  ></path>
                  <rect width="32" height="200" x="168" y="216"></rect>
                  <rect width="32" height="200" x="240" y="216"></rect>
                  <rect width="32" height="200" x="312" y="216"></rect>
                  <path
                    d="M328,88V40c0-13.458-9.488-24-21.6-24H205.6C193.488,16,184,26.542,184,40V88H64v32H448V88ZM216,48h80V88H216Z"
                  ></path>
                </svg>
                <span>Remove</span>
              </button>
              <button
                type="button"
                class="flex items-center px-2 py-1 space-x-1"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 512 512"
                  class="w-4 h-4 fill-current"
                >
                  <path
                    d="M453.122,79.012a128,128,0,0,0-181.087.068l-15.511,15.7L241.142,79.114l-.1-.1a128,128,0,0,0-181.02,0l-6.91,6.91a128,128,0,0,0,0,181.019L235.485,449.314l20.595,21.578.491-.492.533.533L276.4,450.574,460.032,266.94a128.147,128.147,0,0,0,0-181.019ZM437.4,244.313,256.571,425.146,75.738,244.313a96,96,0,0,1,0-135.764l6.911-6.91a96,96,0,0,1,135.713-.051l38.093,38.787,38.274-38.736a96,96,0,0,1,135.765,0l6.91,6.909A96.11,96.11,0,0,1,437.4,244.313Z"
                  ></path>
                </svg>
                <span>Add to favorites</span>
              </button>
            </div>
          </div>
        </div>
      </li>
      <!-- ITEM 2 -->
      <li class="flex flex-col py-6">
        <div class="flex p-1">
          <img
            class="
              flex-shrink-0
              object-cover
              w-20
              h-20
              border-transparent
              rounded
              outline-none
              bg-coolGray-500
            "
            src="https://images.unsplash.com/photo-1504274066651-8d31a536b11a?ixlib=rb-1.2.1&amp;ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;auto=format&amp;fit=crop&amp;w=675&amp;q=80"
            alt="Replica headphones"
          />
          <div class="flex flex-col justify-between w-full p-1">
            <div class="flex justify-between w-full">
              <div class="">
                <h3 class="text-lg font-semibold">Replica headphones</h3>
                <p class="text-sm text-coolGray-600">White</p>
              </div>
              <div class="text-right">
                <p class="text-lg font-semibold">99.95€</p>
                <p class="text-sm line-through text-coolGray-400">150€</p>
              </div>
            </div>
            <div class="flex text-sm divide-x">
              <button
                type="button"
                class="flex items-center px-2 py-1 pl-0 space-x-1"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 512 512"
                  class="w-4 h-4 fill-current"
                >
                  <path
                    d="M96,472a23.82,23.82,0,0,0,23.579,24H392.421A23.82,23.82,0,0,0,416,472V152H96Zm32-288H384V464H128Z"
                  ></path>
                  <rect width="32" height="200" x="168" y="216"></rect>
                  <rect width="32" height="200" x="240" y="216"></rect>
                  <rect width="32" height="200" x="312" y="216"></rect>
                  <path
                    d="M328,88V40c0-13.458-9.488-24-21.6-24H205.6C193.488,16,184,26.542,184,40V88H64v32H448V88ZM216,48h80V88H216Z"
                  ></path>
                </svg>
                <span>Remove</span>
              </button>
              <button
                type="button"
                class="flex items-center px-2 py-1 space-x-1"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 512 512"
                  class="w-4 h-4 fill-current"
                >
                  <path
                    d="M453.122,79.012a128,128,0,0,0-181.087.068l-15.511,15.7L241.142,79.114l-.1-.1a128,128,0,0,0-181.02,0l-6.91,6.91a128,128,0,0,0,0,181.019L235.485,449.314l20.595,21.578.491-.492.533.533L276.4,450.574,460.032,266.94a128.147,128.147,0,0,0,0-181.019ZM437.4,244.313,256.571,425.146,75.738,244.313a96,96,0,0,1,0-135.764l6.911-6.91a96,96,0,0,1,135.713-.051l38.093,38.787,38.274-38.736a96,96,0,0,1,135.765,0l6.91,6.909A96.11,96.11,0,0,1,437.4,244.313Z"
                  ></path>
                </svg>
                <span>Add to favorites</span>
              </button>
            </div>
          </div>
        </div>
      </li>
      <!-- ITEM 3 -->
      <li class="flex flex-col py-6">
        <div class="flex p-1">
          <img
            class="
              flex-shrink-0
              object-cover
              w-20
              h-20
              border-transparent
              rounded
              outline-none
              bg-coolGray-500
            "
            src="https://images.unsplash.com/photo-1594549181132-9045fed330ce?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;ixlib=rb-1.2.1&amp;auto=format&amp;fit=crop&amp;w=675&amp;q=80"
            alt="Set of travel chargers"
          />
          <div class="flex flex-col justify-between w-full p-1">
            <div class="flex justify-between w-full">
              <div class="">
                <h3 class="text-lg font-semibold">Set of travel chargers</h3>
                <p class="text-sm text-coolGray-600">Black</p>
              </div>
              <div class="text-right">
                <p class="text-lg font-semibold">8.99€</p>
                <p class="text-sm line-through text-coolGray-400">15.99€</p>
              </div>
            </div>
            <div class="flex text-sm divide-x">
              <button
                type="button"
                class="flex items-center px-2 py-1 pl-0 space-x-1"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 512 512"
                  class="w-4 h-4 fill-current"
                >
                  <path
                    d="M96,472a23.82,23.82,0,0,0,23.579,24H392.421A23.82,23.82,0,0,0,416,472V152H96Zm32-288H384V464H128Z"
                  ></path>
                  <rect width="32" height="200" x="168" y="216"></rect>
                  <rect width="32" height="200" x="240" y="216"></rect>
                  <rect width="32" height="200" x="312" y="216"></rect>
                  <path
                    d="M328,88V40c0-13.458-9.488-24-21.6-24H205.6C193.488,16,184,26.542,184,40V88H64v32H448V88ZM216,48h80V88H216Z"
                  ></path>
                </svg>
                <span>Remove</span>
              </button>
              <button
                type="button"
                class="flex items-center px-2 py-1 space-x-1"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 512 512"
                  class="w-4 h-4 fill-current"
                >
                  <path
                    d="M453.122,79.012a128,128,0,0,0-181.087.068l-15.511,15.7L241.142,79.114l-.1-.1a128,128,0,0,0-181.02,0l-6.91,6.91a128,128,0,0,0,0,181.019L235.485,449.314l20.595,21.578.491-.492.533.533L276.4,450.574,460.032,266.94a128.147,128.147,0,0,0,0-181.019ZM437.4,244.313,256.571,425.146,75.738,244.313a96,96,0,0,1,0-135.764l6.911-6.91a96,96,0,0,1,135.713-.051l38.093,38.787,38.274-38.736a96,96,0,0,1,135.765,0l6.91,6.909A96.11,96.11,0,0,1,437.4,244.313Z"
                  ></path>
                </svg>
                <span>Add to favorites</span>
              </button>
            </div>
          </div>
        </div>
      </li>

      <!---->
    </ul>
    <div class="space-y-1 text-right p-2">
      <p>
        Total amount:
        <span class="font-semibold">168.93 €</span>
      </p>
      <p class="text-sm text-coolGray-600">
        Not including taxes and shipping costs
      </p>
    </div>
    <div class="flex justify-end space-x-4 p-2">
      <button
        type="button"
        class="px-6 py-2 border rounded-md text-red-500 border-red-500"
      >
        <span class="">Back to Shop</span>
      </button>
      <button
        type="button"
        class="px-6 py-2 border rounded-md bg-green-600 text-white"
      >
        <span class="">Continue to Checkout</span>
      </button>
    </div>
  </div>
</template>

<script>
export default {};
</script>
