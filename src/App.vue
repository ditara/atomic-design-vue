<template>
<html>
  <body>
    <div class="my-jumbotron container" id="my-jumbotron">
      <nav class="navbar flex items-center">
        <a href=""><img src="./pictures/logo2.png" width="100px" height="100px" class="navbar-brand p-6"/></a>
        <nav class="navbar flex items-center">
        <a href=""><p class="font-bold ml-8" style="color: #C890FF;">Berita</p></a>
        <a href=""><p class="font-bold ml-8" style="color: #C890FF;">Olahraga</p></a>
        <a href=""><p class="font-bold ml-8" style="color: #C890FF;">Hiburan</p></a>
        <a href=""><p class="font-bold ml-8" style="color: #C890FF;">Lifestyle</p></a>
        <a href=""><p class="font-bold ml-8" style="color: #C890FF;">Teknologi</p></a>
      </nav>
         <button class="bg-transparent hover:bg-purple-500 text-xs w-20 text-purple-500 font-bold p-2 ml-56 hover:text-white py-2 px-3 border-2 border-purple-500 hover:border-transparent rounded">
          Sign In
         </button>
         <a href=""><img src="./pictures/notification.png" class = "w-10 h-10 p-1 ml-5 p-2"></a>
         <a href=""><img src="./pictures/mail.png" class="w-10 p-1 ml-5 p-2"></a>
      </nav>
    </div>
    <div class="my-jumbotron container" id="my-jumbotron">
      <nav class="navbar flex items-center">
       <input class="shadow appearance-none  rounded w-1/2 h-12 py-2 px-3 text-black leading-tight focus:outline-none "
         id="username" type="text">
         <button class="bg-purple-600 w-32 h-12 py-2 px-3">
           <img src="./pictures/search.png" class="w-6 p-auto m-auto">
         </button>
      </nav>
      <p></p>
    </div>
    <div class="grid grid-rows-3 grid-flow-col gap-4">
      <div class="row-span-3 p-1 mb-1"><img src="./pictures/corona.jpg"></div>
      <div class="row-span-1 col-span-2">
        <p class="font-bold text-purple-500">Berita</p>
        <a href=""><p class="font-bold text-purple-700 hover:text-blue-500">Kasus Positif COVID-19 di Indonesia Jadi 5.923</p></a>
        <p>Juru Bicara Penanganan COVID-19 Achmad Yurianto menyebutkan adanya tambahan 407 kasus positif infeksi virus corona di Indonesia.
Sehingga hari ini, Naik dari kemarin yang berjumlah 5.516 kejadian dan tersebar di 34 provinsi.
Sementara itu, mereka yang sembuh bertambah 59 sehingga secara total kasus kesembuhan sebanyak 607.</p>
      </div>
      <div class="row-span-2 col-span-1 mb-1">
        <div class="bg-red-100 border-l-4 border-red-500 text-red-700 p-4" role="alert">
          <p class="font-bold">Remember</p>
          <p>Maskerku Melindungi Kamu, Maskermu Melindungi Aku</p>
        </div>
      </div>
    </div>
  </body>
</html>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
