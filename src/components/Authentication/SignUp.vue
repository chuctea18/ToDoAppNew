<template>
  <form
    class="bg-gray-800 shadow-2xl rounded p-5 mx-5 md:mx-20 xl:mx-64 2xl:mx-96"
  >
    <h1 class="font-sans text-4xl font-semibold text-white mb-6 text-center">
      Sign Up.
    </h1>
    <div class="mb-4">
      <input
        class="
          shadow
          appearance-none
          border
          rounded
          w-full
          py-2
          px-3
          text-gray-700
          leading-tight
          focus:outline-none focus:shadow-outline
        "
        id="fullname"
        type="text"
        placeholder="Full Name"
      />
    </div>
    <div class="mb-4">
      <input
        class="
          shadow
          appearance-none
          border
          rounded
          w-full
          py-2
          px-3
          text-gray-700
          leading-tight
          focus:outline-none focus:shadow-outline
        "
        id="email"
        type="email"
        placeholder="Email"
      />
    </div>
    <div class="mb-4">
      <input
        class="
          shadow
          appearance-none
          border border-red-500
          rounded
          w-full
          py-2
          px-3
          text-gray-700
          mb-3
          leading-tight
          focus:outline-none focus:shadow-outline
        "
        id="password"
        type="password"
        placeholder="******************"
      />
      <p class="text-red-500 text-xs italic">Please choose a password.</p>
    </div>
    <div class="text-center">
      <button
        class="
          py-3
          w-64
          text-xl text-white
          bg-red-400
          hover:bg-red-500
          rounded-2xl
        "
      >
        Create Account
      </button>
      <p class="mt-4 text-sm text-neutral-500">
        Already Have An Account?
        <a
          class="
            inline-block
            align-baseline
            underline
            font-bold
            text-neutral-500
            hover:text-white
          "
          href="#"
        >
          Sign In
        </a>
      </p>
    </div>
    <!-- <div class="flex items-center justify-between">
      <button
        class="
          bg-red-400
          hover:bg-red-500
          text-white
          font-bold
          py-2
          px-4
          rounded
          focus:outline-none focus:shadow-outline
        "
        type="button"
      >
        Sign Up
      </button>
      <a
        class="
          inline-block
          align-baseline
          font-bold
          text-neutral-500
          hover:text-white
        "
        href="#"
      >
        Forgot Password?
      </a>
    </div> -->
  </form>
</template>

<script>
export default {};
</script>

<style>
</style>