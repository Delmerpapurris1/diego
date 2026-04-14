<script setup>
// No script needed for now
</script>

<template>
  <div id="app" class="min-h-screen bg-gray-50">
    <header class="bg-gradient-to-r from-orange-500 to-red-500 text-white py-6 shadow-lg animate-pulse">
      <nav class="container mx-auto flex justify-between items-center px-4">
        <div class="logo">
          <h1 class="text-3xl font-bold animate-bounce">🍗 Polladas Deliciosas</h1>
        </div>
        <ul class="flex space-x-8">
          <li><a href="#inicio" class="hover:text-yellow-300 transition transform hover:scale-110">Inicio</a></li>
          <li><a href="#menu" class="hover:text-yellow-300 transition transform hover:scale-110">Menú</a></li>
          <li><a href="#nosotros" class="hover:text-yellow-300 transition transform hover:scale-110">Nosotros</a></li>
          <li><a href="#contacto" class="hover:text-yellow-300 transition transform hover:scale-110">Contacto</a></li>
        </ul>
      </nav>
    </header>

    <section id="inicio" class="hero bg-gradient-to-br from-gray-100 to-orange-100 py-20">
      <div class="container mx-auto flex items-center px-4">
        <div class="hero-content flex-1 pr-8 animate-fade-in">
          <h2 class="text-5xl font-bold mb-6 text-orange-600 animate-slide-in-left">¡Las mejores polladas de la ciudad!</h2>
          <p class="text-xl mb-10 text-gray-700 animate-slide-in-right">Disfruta de nuestros deliciosos platos de pollo preparados con los mejores ingredientes frescos y recetas tradicionales.</p>
          <a href="#menu" class="bg-gradient-to-r from-orange-500 to-red-500 text-white px-8 py-4 rounded-full hover:from-orange-600 hover:to-red-600 transition transform hover:scale-110 shadow-lg animate-pulse">Ver Menú</a>
        </div>
        <div class="hero-image flex-1 flex justify-center items-center animate-bounce">
          <span class="text-9xl drop-shadow-lg">🍗</span>
        </div>
      </div>
    </section>

    <section id="menu" class="menu py-20 bg-gradient-to-b from-white to-gray-50">
      <div class="container mx-auto px-4 text-center">
        <h2 class="text-4xl font-bold mb-16 text-gray-800 animate-fade-in">Nuestro Menú</h2>
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-10">
          <div class="menu-item bg-gradient-to-br from-white to-orange-50 p-8 rounded-2xl shadow-xl hover:shadow-2xl transition transform hover:scale-110 hover:rotate-3 border border-orange-200">
            <div class="text-7xl mb-6 animate-pulse">🍗</div>
            <h3 class="text-2xl font-semibold mb-4 text-orange-600">Pollada Completa</h3>
            <p class="text-gray-700 text-lg">Pollo asado con papas, ensalada y bebida. $15.00</p>
          </div>
          <div class="menu-item bg-gradient-to-br from-white to-orange-50 p-8 rounded-2xl shadow-xl hover:shadow-2xl transition transform hover:scale-110 hover:rotate-3 border border-orange-200">
            <div class="text-7xl mb-6 animate-pulse">🍖</div>
            <h3 class="text-2xl font-semibold mb-4 text-orange-600">Alitas de Pollo</h3>
            <p class="text-gray-700 text-lg">Alitas crujientes con salsa BBQ. $10.00</p>
          </div>
          <div class="menu-item bg-gradient-to-br from-white to-orange-50 p-8 rounded-2xl shadow-xl hover:shadow-2xl transition transform hover:scale-110 hover:rotate-3 border border-orange-200">
            <div class="text-7xl mb-6 animate-pulse">🍗</div>
            <h3 class="text-2xl font-semibold mb-4 text-orange-600">Pechuga de Pollo</h3>
            <p class="text-gray-700 text-lg">Pechuga a la plancha con verduras. $12.00</p>
          </div>
          <div class="menu-item bg-gradient-to-br from-white to-orange-50 p-8 rounded-2xl shadow-xl hover:shadow-2xl transition transform hover:scale-110 hover:rotate-3 border border-orange-200">
            <div class="text-7xl mb-6 animate-pulse">🍗</div>
            <h3 class="text-2xl font-semibold mb-4 text-orange-600">Pollada Familiar</h3>
            <p class="text-gray-700 text-lg">Para compartir: pollo, papas y ensalada. $25.00</p>
          </div>
        </div>
      </div>
    </section>

    <section id="nosotros" class="about bg-gradient-to-r from-orange-50 to-red-50 py-20">
      <div class="container mx-auto px-4 text-center">
        <h2 class="text-4xl font-bold mb-10 text-gray-800 animate-fade-in">Sobre Nosotros</h2>
        <p class="text-xl max-w-3xl mx-auto text-gray-700 animate-slide-in-up">Somos un local familiar dedicado a ofrecer las mejores polladas desde hace 10 años. Utilizamos pollo fresco y recetas tradicionales para garantizar el mejor sabor en cada bocado. ¡Ven y disfruta de una experiencia culinaria inolvidable! 🍗✨</p>
      </div>
    </section>

    <section id="contacto" class="contact py-20 bg-gradient-to-b from-gray-50 to-white">
      <div class="container mx-auto px-4 text-center">
        <h2 class="text-4xl font-bold mb-16 text-gray-800 animate-fade-in">Contacto</h2>
        <div class="grid grid-cols-1 md:grid-cols-2 gap-12 max-w-5xl mx-auto">
          <div class="bg-gradient-to-br from-white to-orange-50 p-8 rounded-2xl shadow-xl border border-orange-200 animate-slide-in-left">
            <h3 class="text-2xl font-semibold mb-6 text-orange-600">📞 Información de Contacto</h3>
            <p class="mb-4 text-lg"><strong>Dirección:</strong> Calle Principal 123, Ciudad</p>
            <p class="mb-4 text-lg"><strong>Teléfono:</strong> (123) 456-7890</p>
            <p class="mb-4 text-lg"><strong>Email:</strong> info@polladasdeliciosas.com</p>
            <p class="text-lg"><strong>Horarios:</strong> Lunes a Domingo, 11:00 AM - 10:00 PM</p>
          </div>
          <div class="bg-gradient-to-br from-white to-orange-50 p-8 rounded-2xl shadow-xl border border-orange-200 animate-slide-in-right">
            <h3 class="text-2xl font-semibold mb-6 text-orange-600">📍 Ubicación</h3>
            <div class="flex justify-center items-center h-48">
              <span class="text-8xl animate-spin">🗺️</span>
            </div>
          </div>
        </div>
      </div>
    </section>

    <footer class="bg-gradient-to-r from-gray-800 to-black text-white py-12">
      <div class="container mx-auto px-4 text-center">
        <p class="text-lg mb-6">&copy; 2023 Polladas Deliciosas. Todos los derechos reservados. 🍗❤️</p>
        <div class="flex justify-center space-x-8">
          <a href="#" class="text-2xl hover:text-orange-400 transition transform hover:scale-125 animate-pulse">📘</a>
          <a href="#" class="text-2xl hover:text-orange-400 transition transform hover:scale-125 animate-pulse">📷</a>
          <a href="#" class="text-2xl hover:text-orange-400 transition transform hover:scale-125 animate-pulse">🐦</a>
        </div>
      </div>
    </footer>
  </div>
</template>
