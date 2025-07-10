<html class="scroll-smooth" lang="id">
 <head>
  <meta charset="utf-8"/>
  <meta content="width=device-width, initial-scale=1" name="viewport"/>
  <title>
   Cave Rival - Aplikasi Kafe Unik
  </title>
  <script src="https://cdn.tailwindcss.com">
  </script>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&amp;display=swap" rel="stylesheet"/>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet"/>
  <style>
   body {
    font-family: 'Poppins', sans-serif; 
  }
  </style>
 </head>
 <body class="bg-gray-50 min-h-screen flex flex-col">
  <!-- Header / Navbar -->
  <header class="bg-gray-900 text-yellow-400 sticky top-0 z-50 shadow-lg">
   <div class="container mx-auto px-4 py-4 flex items-center justify-between">
    <div class="flex items-center space-x-3">
     <img alt="Logo Cave Rival, huruf CR berwarna kuning dengan latar belakang hitam" class="w-12 h-12 rounded-full" height="48" src="rival.jpg" width="48"/>
     <h1 class="text-2xl font-extrabold tracking-wide">
      Cave Rival
     </h1>
    </div>
    <nav class="hidden md:flex space-x-8 font-semibold">
     <a class="hover:text-yellow-300 transition" href="#menu">
      Menu
     </a>
     <a class="hover:text-yellow-300 transition" href="#plafon">
      Plafon
     </a>
     <a class="hover:text-yellow-300 transition" href="#reservasi">
      Reservasi
     </a>
     <a class="hover:text-yellow-300 transition" href="#tentang">
      Tentang
     </a>
     <a class="hover:text-yellow-300 transition" href="#kontak">
      Kontak
     </a>
    </nav>
    <button aria-label="Toggle menu" class="md:hidden text-yellow-400 focus:outline-none" id="btn-menu">
     <i class="fas fa-bars fa-lg">
     </i>
    </button>
   </div>
   <nav class="md:hidden bg-gray-900 text-yellow-400 border-t border-yellow-700 hidden flex-col space-y-2 px-4 pb-4" id="mobile-menu">
    <a class="block py-2 hover:text-yellow-300 transition font-semibold" href="#menu">
     Menu
    </a>
    <a class="block py-2 hover:text-yellow-300 transition font-semibold" href="#plafon">
     Plafon
    </a>
    <a class="block py-2 hover:text-yellow-300 transition font-semibold" href="#reservasi">
     Reservasi
    </a>
    <a class="block py-2 hover:text-yellow-300 transition font-semibold" href="#tentang">
     Tentang
    </a>
    <a class="block py-2 hover:text-yellow-300 transition font-semibold" href="#kontak">
     Kontak
    </a>
   </nav>
  </header>
  <!-- Hero Section -->
  <section class="container mx-auto px-6 py-20 flex flex-col md:flex-row items-center gap-12">
   <div class="md:w-1/2 text-center md:text-left">
    <h2 class="text-5xl font-extrabold text-gray-900 mb-6">
     Selamat Datang di Cave Rival
    </h2>
    <p class="text-gray-700 text-lg mb-8">
     Kafe unik dengan konsep gua dan plafon artistik yang memukau. Nikmati kopi dan hidangan spesial kami dalam suasana yang berbeda dari yang lain.
    </p>
    <a class="inline-block bg-yellow-500 text-white font-semibold px-8 py-3 rounded-full shadow-lg hover:bg-yellow-600 transition" href="#menu">
     Jelajahi Menu
    </a>
   </div>
   <div class="md:w-1/2">
    <img alt="Interior kafe Cave Rival dengan plafon artistik menyerupai gua batu berwarna gelap dengan lampu-lampu hangat menggantung" class="rounded-xl shadow-lg mx-auto" height="400" src="rival.jpg" width="600"/>
   </div>
  </section>
  <!-- Menu Section -->
  <section class="container mx-auto px-6 py-16" id="menu">
   <h3 class="text-4xl font-bold text-gray-900 mb-12 text-center">
    Menu Andalan Cave Rival
   </h3>
   <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-10">
    <article class="bg-white rounded-xl shadow-md hover:shadow-xl transition overflow-hidden">
     <img alt="Cangkir espresso hitam pekat dengan busa tipis di atasnya di atas meja batu kasar menyerupai gua" class="w-full h-48 object-cover" height="300" src="https://storage.googleapis.com/a1aa/image/630bb28c-98f9-446e-3297-9f06d9519127.jpg" width="400"/>
     <div class="p-5">
      <h4 class="text-xl font-semibold text-yellow-600">
       Espresso Gua
      </h4>
      <p class="mt-2 text-gray-600">
       Kopi hitam pekat dengan aroma kuat, disajikan dengan gaya gua yang unik.
      </p>
      <p class="mt-3 font-bold text-yellow-700">
       Rp 20.000
      </p>
     </div>
    </article>
    <article class="bg-white rounded-xl shadow-md hover:shadow-xl transition overflow-hidden">
     <img alt="Cangkir cappuccino dengan busa susu berbentuk swirl di atasnya di atas meja batu kasar" class="w-full h-48 object-cover" height="300" src="https://storage.googleapis.com/a1aa/image/95514bc1-43c5-4651-f201-6296086629e7.jpg" width="400"/>
     <div class="p-5">
      <h4 class="text-xl font-semibold text-yellow-600">
       Cappuccino Batu
      </h4>
      <p class="mt-2 text-gray-600">
       Kopi susu berbusa lembut dengan sentuhan rasa coklat yang hangat.
      </p>
      <p class="mt-3 font-bold text-yellow-700">
       Rp 28.000
      </p>
     </div>
    </article>
    <article class="bg-white rounded-xl shadow-md hover:shadow-xl transition overflow-hidden">
     <img alt="Cangkir latte dengan latte art berbentuk stalaktit di atasnya" class="w-full h-48 object-cover" height="300" src="https://storage.googleapis.com/a1aa/image/a8483083-f9c6-4b3d-e6ec-24cc8dda1d49.jpg" width="400"/>
     <div class="p-5">
      <h4 class="text-xl font-semibold text-yellow-600">
       Latte Stalaktit
      </h4>
      <p class="mt-2 text-gray-600">
       Latte dengan seni busa menyerupai stalaktit gua, rasa lembut dan creamy.
      </p>
      <p class="mt-3 font-bold text-yellow-700">
       Rp 30.000
      </p>
     </div>
    </article>
    <article class="bg-white rounded-xl shadow-md hover:shadow-xl transition overflow-hidden">
     <img alt="Gelas americano kopi hitam dengan latar belakang batu gua" class="w-full h-48 object-cover" height="300" src="https://storage.googleapis.com/a1aa/image/44875849-b508-45b8-ce9a-e1133331a772.jpg" width="400"/>
     <div class="p-5">
      <h4 class="text-xl font-semibold text-yellow-600">
       Americano Gua
      </h4>
      <p class="mt-2 text-gray-600">
       Kopi hitam yang diseduh dengan air panas, rasa ringan dan segar dengan nuansa gua.
      </p>
      <p class="mt-3 font-bold text-yellow-700">
       Rp 22.000
      </p>
     </div>
    </article>
    <article class="bg-white rounded-xl shadow-md hover:shadow-xl transition overflow-hidden">
     <img alt="Cangkir mocha dengan lapisan coklat dan busa susu di atasnya dengan latar batu gua" class="w-full h-48 object-cover" height="300" src="https://storage.googleapis.com/a1aa/image/c3a73db9-1e0e-4836-1262-cec257736442.jpg" width="400"/>
     <div class="p-5">
      <h4 class="text-xl font-semibold text-yellow-600">
       Mocha Gua
      </h4>
      <p class="mt-2 text-gray-600">
       Perpaduan kopi, coklat, dan susu yang manis dan pahit, cocok untuk suasana gua.
      </p>
      <p class="mt-3 font-bold text-yellow-700">
       Rp 32.000
      </p>
     </div>
    </article>
    <article class="bg-white rounded-xl shadow-md hover:shadow-xl transition overflow-hidden">
     <img alt="Gelas teh tarik dengan busa susu di atasnya dan latar batu gua" class="w-full h-48 object-cover" height="300" src="https://storage.googleapis.com/a1aa/image/043010b6-062e-4113-ef7b-dea3e86ee17a.jpg" width="400"/>
     <div class="p-5">
      <h4 class="text-xl font-semibold text-yellow-600">
       Teh Tarik Gua
      </h4>
      <p class="mt-2 text-gray-600">
       Teh susu manis dengan busa lembut khas Asia Tenggara, nikmat di suasana gua.
      </p>
      <p class="mt-3 font-bold text-yellow-700">
       Rp 18.000
      </p>
     </div>
    </article>
   </div>
  </section>
  <!-- Plafon Section -->
  <section class="bg-gray-900 text-yellow-400 py-20 px-6" id="plafon">
   <div class="container mx-auto max-w-5xl">
    <h3 class="text-4xl font-extrabold mb-12 text-center">
     Fitur Plafon Artistik Cave Rival
    </h3>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-12">
     <div class="flex flex-col items-center text-center">
      <img alt="Lampu gantung artistik berbentuk stalaktit gua dengan cahaya hangat" class="mb-6 rounded-full shadow-lg" height="150" src="https://storage.googleapis.com/a1aa/image/abf6ddad-b20b-47f6-3a4d-51a8a26d0c3e.jpg" width="150"/>
      <h4 class="text-xl font-semibold mb-2">
       Lampu Gantung Stalaktit
      </h4>
      <p class="text-gray-300">
       Lampu gantung unik menyerupai stalaktit gua yang memberikan pencahayaan hangat dan dramatis.
      </p>
     </div>
     <div class="flex flex-col items-center text-center">
      <img alt="Tekstur plafon batu gua alami dengan warna gelap dan detail kasar" class="mb-6 rounded-full shadow-lg" height="150" src="https://storage.googleapis.com/a1aa/image/1575e652-0189-460d-f4f8-488fbde2522f.jpg" width="150"/>
      <h4 class="text-xl font-semibold mb-2">
       Tekstur Batu Alami
      </h4>
      <p class="text-gray-300">
       Plafon dengan tekstur batu alami yang memberikan kesan gua asli dan suasana hangat.
      </p>
     </div>
     <div class="flex flex-col items-center text-center">
      <img alt="Efek lampu warna kuning keemasan yang memantul di plafon batu gua" class="mb-6 rounded-full shadow-lg" height="150" src="https://storage.googleapis.com/a1aa/image/9dd4da44-9259-4ba3-935f-9653ee2a8945.jpg" width="150"/>
      <h4 class="text-xl font-semibold mb-2">
       Efek Cahaya Dinamis
      </h4>
      <p class="text-gray-300">
       Lampu dengan efek cahaya dinamis yang memantul di plafon, menciptakan suasana magis dan cozy.
      </p>
     </div>
    </div>
    <div class="mt-16 text-center">
     <img alt="Foto close up plafon artistik kafe Cave Rival dengan lampu gantung stalaktit dan tekstur batu alami berwarna gelap" class="mx-auto rounded-xl shadow-lg max-w-full" height="400" src="https://storage.googleapis.com/a1aa/image/918ecdb6-e03b-4755-c09c-0a718286dfbf.jpg" width="900"/>
    </div>
   </div>
  </section>
  <!-- Reservasi Section -->
  <section class="container mx-auto px-6 py-16" id="reservasi">
   <h3 class="text-4xl font-bold text-gray-900 mb-10 text-center">
    Reservasi Meja
   </h3>
   <div class="max-w-3xl mx-auto bg-white rounded-xl shadow-lg p-8">
    <form class="space-y-6" id="formReservasi">
     <div>
      <label class="block font-semibold text-gray-700 mb-2" for="nama">
       Nama Lengkap
      </label>
      <input class="w-full border border-gray-300 rounded-md px-4 py-2 focus:outline-yellow-500 focus:ring-2 focus:ring-yellow-300" id="nama" name="nama" placeholder="Masukkan nama lengkap" required="" type="text"/>
     </div>
     <div>
      <label class="block font-semibold text-gray-700 mb-2" for="email">
       Email
      </label>
      <input class="w-full border border-gray-300 rounded-md px-4 py-2 focus:outline-yellow-500 focus:ring-2 focus:ring-yellow-300" id="email" name="email" placeholder="Masukkan email" required="" type="email"/>
     </div>
     <div>
      <label class="block font-semibold text-gray-700 mb-2" for="tanggal">
       Tanggal Reservasi
      </label>
      <input class="w-full border border-gray-300 rounded-md px-4 py-2 focus:outline-yellow-500 focus:ring-2 focus:ring-yellow-300" id="tanggal" name="tanggal" required="" type="date"/>
     </div>
     <div>
      <label class="block font-semibold text-gray-700 mb-2" for="waktu">
       Waktu
      </label>
      <select class="w-full border border-gray-300 rounded-md px-4 py-2 focus:outline-yellow-500 focus:ring-2 focus:ring-yellow-300" id="waktu" name="waktu" required="">
       <option disabled="" selected="" value="">
        Pilih waktu
       </option>
       <option value="10:00">
        10:00 WIB
       </option>
       <option value="12:00">
        12:00 WIB
       </option>
       <option value="14:00">
        14:00 WIB
       </option>
       <option value="16:00">
        16:00 WIB
       </option>
       <option value="18:00">
        18:00 WIB
       </option>
       <option value="20:00">
        20:00 WIB
       </option>
      </select>
     </div>
     <div>
      <label class="block font-semibold text-gray-700 mb-2" for="jumlah">
       Jumlah Orang
      </label>
      <input class="w-full border border-gray-300 rounded-md px-4 py-2 focus:outline-yellow-500 focus:ring-2 focus:ring-yellow-300" id="jumlah" max="20" min="1" name="jumlah" placeholder="Masukkan jumlah orang" required="" type="number"/>
     </div>
     <button class="w-full bg-yellow-600 text-white font-semibold py-3 rounded-full hover:bg-yellow-700 transition" type="submit">
      Pesan Sekarang
     </button>
    </form>
    <p class="mt-6 text-green-600 font-semibold text-center hidden" id="pesanSukses">
     Terima kasih! Reservasi Anda telah diterima.
    </p>
   </div>
  </section>
  <!-- Tentang Section -->
  <section class="container mx-auto px-6 py-16" id="tentang">
   <h3 class="text-4xl font-bold text-gray-900 mb-10 text-center">
    Tentang Cave Rival
   </h3>
   <div class="flex flex-col md:flex-row items-center gap-12">
    <div class="md:w-1/2">
     <img alt="Interior kafe Cave Rival dengan plafon artistik menyerupai gua batu dan lampu gantung hangat" class="rounded-xl shadow-lg w-full" height="400" src="https://storage.googleapis.com/a1aa/image/d0088aa2-ba98-41ca-645a-5b47afdbc69f.jpg" width="600"/>
    </div>
    <div class="md:w-1/2 text-gray-700 text-lg">
     <p>
      Cave Rival adalah kafe dengan konsep unik yang menggabungkan suasana gua alami dan desain plafon artistik yang memukau. Kami berdedikasi memberikan pengalaman ngopi yang berbeda dan tak terlupakan.
     </p>
     <p class="mt-4">
      Dengan pilihan kopi premium dan menu makanan ringan yang lezat, kami mengundang Anda untuk menikmati waktu santai dalam suasana yang cozy dan eksklusif.
     </p>
    </div>
   </div>
  </section>
  <!-- Kontak Section -->
  <section class="bg-gray-900 text-yellow-400 py-16 px-6" id="kontak">
   <div class="container mx-auto max-w-4xl">
    <h3 class="text-4xl font-extrabold mb-10 text-center">
     Hubungi Kami
    </h3>
    <div class="grid grid-cols-1 md:grid-cols-2 gap-12">
     <div class="space-y-6 text-lg">
      <div class="flex items-center space-x-4">
       <i class="fas fa-map-marker-alt text-yellow-500 text-2xl">
       </i>
       <p>
        Jl. Gua Batu No. 77, Jakarta Selatan, Indonesia
       </p>
      </div>
      <div class="flex items-center space-x-4">
       <i class="fas fa-phone-alt text-yellow-500 text-2xl">
       </i>
       <p>
        +62 811 2233 4455
       </p>
      </div>
      <div class="flex items-center space-x-4">
       <i class="fas fa-envelope text-yellow-500 text-2xl">
       </i>
       <p>
        contact@caverival.id
       </p>
      </div>
      <div class="flex items-center space-x-4">
       <i class="fas fa-clock text-yellow-500 text-2xl">
       </i>
       <p>
        Senin - Minggu: 09.00 - 23.00 WIB
       </p>
      </div>
     </div>
     <form class="space-y-6 bg-gray-800 rounded-xl shadow-lg p-8 text-yellow-400" id="formKontak">
      <div>
       <label class="block font-semibold mb-2" for="namaKontak">
        Nama
       </label>
       <input class="w-full rounded-md px-4 py-2 bg-gray-900 border border-yellow-600 focus:outline-yellow-400 focus:ring-2 focus:ring-yellow-400 text-yellow-400" id="namaKontak" name="namaKontak" placeholder="Masukkan nama Anda" required="" type="text"/>
      </div>
      <div>
       <label class="block font-semibold mb-2" for="emailKontak">
        Email
       </label>
       <input class="w-full rounded-md px-4 py-2 bg-gray-900 border border-yellow-600 focus:outline-yellow-400 focus:ring-2 focus:ring-yellow-400 text-yellow-400" id="emailKontak" name="emailKontak" placeholder="Masukkan email Anda" required="" type="email"/>
      </div>
      <div>
       <label class="block font-semibold mb-2" for="pesan">
        Pesan
       </label>
       <textarea class="w-full rounded-md px-4 py-2 bg-gray-900 border border-yellow-600 focus:outline-yellow-400 focus:ring-2 focus:ring-yellow-400 text-yellow-400 resize-none" id="pesan" name="pesan" placeholder="Tulis pesan Anda" required="" rows="4"></textarea>
      </div>
      <button class="w-full bg-yellow-600 text-gray-900 font-semibold py-3 rounded-full hover:bg-yellow-700 transition" type="submit">
       Kirim Pesan
      </button>
      <p class="mt-4 text-green-400 font-semibold text-center hidden" id="pesanKontakSukses">
       Terima kasih! Pesan Anda telah terkirim.
      </p>
     </form>
    </div>
   </div>
  </section>
  <!-- Footer -->
  <footer class="bg-gray-900 text-yellow-400 py-6 mt-auto">
   <div class="container mx-auto px-6 flex flex-col md:flex-row justify-between items-center">
    <p class="text-sm">
     © 2024 Cave Rival. Semua hak cipta dilindungi.
    </p>
    <div class="flex space-x-6 mt-4 md:mt-0">
     <a aria-label="Facebook" class="hover:text-yellow-300 transition" href="#">
      <i class="fab fa-facebook fa-lg">
      </i>
     </a>
     <a aria-label="Instagram" class="hover:text-yellow-300 transition" href="#">
      <i class="fab fa-instagram fa-lg">
      </i>
     </a>
     <a aria-label="Twitter" class="hover:text-yellow-300 transition" href="#">
      <i class="fab fa-twitter fa-lg">
      </i>
     </a>
    </div>
   </div>
  </footer>
  <script>
   // Toggle mobile menu
  const btnMenu = document.getElementById('btn-menu');
  const mobileMenu = document.getElementById('mobile-menu');
  btnMenu.addEventListener('click', () => {
    mobileMenu.classList.toggle('hidden');
  });

  // Reservasi form submit handler
  const formReservasi = document.getElementById('formReservasi');
  const pesanSukses = document.getElementById('pesanSukses');
  formReservasi.addEventListener('submit', (e) => {
    e.preventDefault();
    pesanSukses.classList.remove('hidden');
    formReservasi.reset();
    setTimeout(() => {
      pesanSukses.classList.add('hidden');
    }, 5000);
  });

  // Kontak form submit handler
  const formKontak = document.getElementById('formKontak');
  const pesanKontakSukses = document.getElementById('pesanKontakSukses');
  formKontak.addEventListener('submit', (e) => {
    e.preventDefault();
    pesanKontakSukses.classList.remove('hidden');
    formKontak.reset();
    setTimeout(() => {
      pesanKontakSukses.classList.add('hidden');
    }, 5000);
  });
  </script>
 </body>
</html> 
