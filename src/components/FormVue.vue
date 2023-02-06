<template>
  <section class="bg-gray-100 overflow-hidden">
    <div class="  flex justify-center	items-center">
      <div class="w-full md:w-1/2">
        <div class="container px-4 mx-auto">
          <div class="flex flex-wrap">
            <div class="w-full">
              <div class="flex justify-center items-center h-screen">
                <div class="p-4 max-w-md w-full bg-white shadow-xl1 rounded-lg shadow-sm">
                  <div class="flex justify-center pt-5">
                  </div>
                  <div class="flex justify-center items-center mt-10 mb-3">
                    <img alt="Vue logo" class="w-12" src="../assets/logo.png">
                  </div>
                  <div class="flex justify-center items-center mb-5">
                    <span class="text-gray-400 font-medium text-medium">
                      E novo aqui? <a href="/register-user" class="font-semibold text-gray-800 hover:text-gray-700">Crie sua conta!</a>
                    </span>
                  </div>

                  <form class="mt-4">
                    <label class="block mt-3 mb-0">
                      <input type="email" class="w-full py-3 pl-3 mb-4 bg-white border rounded-lg"
                        placeholder="E-mail">
                    </label>

                    <label class="block mt-0 mb-0">
                      <input type="password" class="w-full py-3 pl-3 mb-4 bg-white border rounded-lg"
                        placeholder="********">
                    </label>

                    <div class="mt-0 mb-6">
                      <button type="submit"
                        class="py-2 px-4 text-center bg-gray-800 h-12 rounded-lg w-full font-medium text-white text-base hover:bg-gray-700">
                        Entrar
                      </button>
                    </div>
                    <div class="text-gray-800 hover:text-gray-700 text-base font-medium mb-2 text-center">
                      <a href="/reset-password">Esqueceu sua senha?</a>
                    </div>
                  </form>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
  
<script>

  export default {
    name: 'FormVue',
    props: {
      msg: String
    }
  }

</script>