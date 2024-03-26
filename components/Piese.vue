<template>
  <div class="bg-white py-6 sm:py-8 lg:py-12">
    <div class="mx-auto min-h-screen max-w-screen-xl px-4 md:px-8 mt-24">
      <!-- text - start -->
      <div class="mb-10 md:mb-16">
        <!-- <h2 class="mb-4 text-center text-2xl font-bold text-gray-800 md:mb-6 lg:text-3xl">Piese</h2> -->

        <p class="mx-auto max-w-screen-md text-center text-gray-500 md:text-lg">
          De la noi poți achiziționa toate piesele pentru îmbunătățirea mașinii tale.
        </p>
      </div>
      <!-- text - end -->

      <div class="grid gap-4 sm:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 p-5 rounded-xl bg-gray-200">
        <!-- Motor - start -->
        <div class="product" data-page="1">
          <a href="#" class="group relative block h-60 overflow-hidden bg-gray-400 rounded-t-2xl shadow-2xl">
            <img src="https://i.pinimg.com/564x/db/b2/07/dbb2072e9b9acc8e4c0c635d3708a3e8.jpg" loading="lazy"
              alt="Engine" class="h-full p-2 rounded-2xl w-full object-cover object-center transition duration-200" />

            <span
              class="absolute left-0 top-3 rounded-r-lg bg-red-500 px-3 py-1.5 text-sm font-semibold uppercase tracking-wider text-white">-50%</span>
          </a>

          <div class="flex items-start justify-between gap-2 rounded-b-2xl bg-gray-500 p-4">
            <div class="flex flex-col">
              <a href="#" class="font-bold text-white transition duration-100 hover:text-gray-300 lg:text-lg">Motor V8</a>
              <span class="text-sm text-gray-300 lg:text-base">4.4 L Diesel</span>
            </div>

            <div class="flex flex-col items-end">
              <span class="font-bold text-white lg:text-lg">$19.99</span>
              <span class="text-sm text-red-500 line-through">$39.99</span>
            </div>
          </div>
        </div>
        <!-- Motor - end -->

        <!-- Baterie - start -->
        <div class="product" data-page="1">
          <a href="#" class="group relative block h-60 overflow-hidden rounded-t-2xl shadow-2xl bg-gray-500">
            <img src="https://live.staticflickr.com/65535/53185822734_c2b872719b_b.jpg" loading="lazy" alt=""
              class="h-full p-2 rounded-2xl w-full object-cover object-center transition duration-200" />
          </a>

          <div class="flex items-start justify-between gap-2 rounded-b-2xl bg-gray-500 p-4">
            <div class="flex flex-col">
              <a href="#" class="font-bold text-white transition duration-200 hover:text-gray-200 lg:text-lg">Baterie
                12V</a>
              <span class="text-sm text-gray-300 lg:text-base">Lithium-Ion</span>
            </div>

            <div class="flex flex-col items-end">
              <span class="font-bold text-white lg:text-lg">$29.99</span>
            </div>
          </div>
        </div>
        <!-- Baterie - end -->

        <!-- Jante - start -->
        <div class="product" data-page="1">
          <a href="#" class="group relative block h-60 overflow-hidden rounded-t-2xl shadow-2xl bg-gray-500">
            <img
              src="https://sc02.alicdn.com/kf/HTB1c.UuSAvoK1RjSZFNq6AxMVXau/236681580/HTB1c.UuSAvoK1RjSZFNq6AxMVXau.jpg"
              loading="lazy" alt=""
              class="h-full p-2 rounded-2xl w-full object-cover object-center transition duration-200" />
          </a>

          <div class="flex items-start justify-between gap-2 rounded-b-2xl shadow-2xl bg-gray-500 p-4">
            <div class="flex flex-col">
              <a href="#" class="font-bold text-white transition duration-200 hover:text-gray-200 lg:text-lg">Jante</a>
              <span class="text-sm text-gray-300 lg:text-base">Din aliaj</span>
            </div>

            <div class="flex flex-col items-end">
              <span class="font-bold text-white lg:text-lg">$29.99</span>
            </div>
          </div>
        </div>
        <!-- Jante - end -->

        <!-- Faruri - start -->
        <div class="product" data-page="1">
          <a href="#" class="group relative block h-60 overflow-hidden rounded-t-2xl shadow-2xl bg-gray-500">
            <img src="https://guar.ro/pics/Masina-faruri-bi-xenon-lumina-bm-we71-x6-30dx-m57n2_thumbs-1/38335.jpeg"
              loading="lazy" alt=""
              class="h-full p-2 rounded-2xl w-full object-cover object-center transition duration-200" />
          </a>

          <div class="flex items-start justify-between gap-2 rounded-b-2xl bg-gray-500 p-4">
            <div class="flex flex-col">
              <a href="#" class="font-bold text-white transition duration-200 hover:text-gray-200 lg:text-lg">Faruri</a>
              <span class="text-sm text-gray-300 lg:text-base">Xenon</span>
            </div>

            <div class="flex flex-col items-end">
              <span class="font-bold text-white lg:text-lg">$29.99</span>
            </div>
          </div>
        </div>
        <!-- Faruri - end -->

        <!-- Grila - start -->
        <div class="product" data-page="1">
          <a href="#" class="group relative block h-60 overflow-hidden rounded-t-2xl shadow-2xl bg-gray-500">
            <img
              src="https://5.imimg.com/data5/SELLER/Default/2022/8/WS/FJ/NL/8347271/audi-a4-b8-5-rs4-front-grill-black-2012-2013-2014-2015.jpg"
              loading="lazy" alt=""
              class="h-full p-2 rounded-2xl w-full object-cover object-center transition duration-200" />
          </a>

          <div class="flex items-start justify-between gap-2 rounded-b-2xl bg-gray-500 p-4">
            <div class="flex flex-col">
              <a href="#" class="font-bold text-white transition duration-200 hover:text-gray-200 lg:text-lg">Grilă
                Față</a>
              <span class="text-sm text-gray-300 lg:text-base">Pentru Audi RS4 B8</span>
            </div>

            <div class="flex flex-col items-end">
              <span class="font-bold text-white lg:text-lg">$29.99</span>
            </div>
          </div>
        </div>
        <!-- Grila - end -->

        <!-- Volan - start -->
        <div class="product" data-page="1">
          <a href="#" class="group relative block h-60 overflow-hidden rounded-t-2xl shadow-2xl bg-gray-500">
            <img
              src="https://carbonsteer.com/cdn/shop/products/image_b6e08b71-b84e-4040-8137-0ae6b3fd299c_995x.jpg?v=1618674730"
              loading="lazy" alt=""
              class="h-full p-2 rounded-2xl w-full object-cover object-center transition duration-200" />
          </a>

          <div class="flex items-start justify-between gap-2 rounded-b-2xl bg-gray-500 p-4">
            <div class="flex flex-col">
              <a href="#" class="font-bold text-white transition duration-200 hover:text-gray-200 lg:text-lg">Volan</a>
              <span class="text-sm text-gray-300 lg:text-base">BMW Fibra Carbon</span>
            </div>

            <div class="flex flex-col items-end">
              <span class="font-bold text-white lg:text-lg">$29.99</span>
            </div>
          </div>
        </div>
        <!-- Volan - end -->

        <!-- Filtru aer - start -->
        <div class="product" data-page="1">
          <a href="#" class="group relative block h-60 overflow-hidden rounded-t-2xl shadow-2xl bg-gray-500">
            <img src="https://i.ebayimg.com/images/g/nBgAAOSw9eBjodf1/s-l1600.jpg" loading="lazy" alt=""
              class="h-full p-2 rounded-2xl w-full object-cover object-center transition duration-200" />
          </a>

          <div class="flex items-start justify-between gap-2 rounded-b-2xl bg-gray-500 p-4">
            <div class="flex flex-col">
              <a href="#" class="font-bold text-white transition duration-200 hover:text-gray-200 lg:text-lg">Filtru de
                Aer</a>
              <span class="text-sm text-gray-300 lg:text-base">Galben</span>
            </div>

            <div class="flex flex-col items-end">
              <span class="font-bold text-white lg:text-lg">$29.99</span>
            </div>
          </div>
        </div>
        <!-- Filtru aer - end -->

        <!-- Catalizator - start -->
        <div class="product" data-page="1">
          <a href="#" class="group relative block h-60 overflow-hidden rounded-t-2xl shadow-2xl bg-gray-500">
            <img
              src="https://s13emagst.akamaized.net/products/46267/46266264/images/res_18499997ec71cbee2ad78e1bf47a69b8.jpg"
              loading="lazy" alt=""
              class="h-full p-2 rounded-2xl w-full object-cover object-center transition duration-200" />
          </a>

          <div class="flex items-start justify-between gap-2 rounded-b-2xl bg-gray-500 p-4">
            <div class="flex flex-col">
              <a href="#"
                class="font-bold text-white transition duration-200 hover:text-gray-200 lg:text-lg">Catalizator</a>
              <span class="text-sm text-gray-300 lg:text-base">Universal - Euro 4</span>
            </div>

            <div class="flex flex-col items-end">
              <span class="font-bold text-white lg:text-lg">$29.99</span>
            </div>
          </div>
        </div>
        <!-- Catalizator - end -->

        <!-- Etrier - start -->
        <div class="product" data-page="2">
          <a href="#" class="group relative block h-60 overflow-hidden rounded-t-2xl shadow-2xl bg-gray-500">
            <img
              src="https://dcaevolution.ro/image/cache/catalog/vopsea_etriere/foliatec-matt-red-vopsea-etriere-109036-500x500-550x550.jpg"
              loading="lazy" alt=""
              class="h-full p-2 rounded-2xl w-full object-cover object-center transition duration-200" />
          </a>

          <div class="flex items-start justify-between gap-2 rounded-b-2xl bg-gray-500 p-4">
            <div class="flex flex-col">
              <a href="#"
                class="font-bold text-white transition duration-200 hover:text-gray-200 lg:text-lg">Etrier</a>
              <span class="text-sm text-gray-300 lg:text-base">Culoare - Roșu</span>
            </div>

            <div class="flex flex-col items-end">
              <span class="font-bold text-white lg:text-lg">$29.99</span>
            </div>
          </div>
        </div>
        <!-- Etrier - end -->

        <!-- Disc frana - start -->
        <div class="product" data-page="2">
          <a href="#" class="group relative block h-60 overflow-hidden rounded-t-2xl shadow-2xl bg-gray-500">
            <img
              src="https://s13emagst.akamaized.net/products/28891/28890968/images/res_125af1b6790845b4d571c2761a1eab69.jpg"
              loading="lazy" alt=""
              class="h-full p-2 rounded-2xl w-full object-cover object-center transition duration-200" />
          </a>

          <div class="flex items-start justify-between gap-2 rounded-b-2xl bg-gray-500 p-4">
            <div class="flex flex-col">
              <a href="#"
                class="font-bold text-white transition duration-200 hover:text-gray-200 lg:text-lg">Disc de frână</a>
              <span class="text-sm text-gray-300 lg:text-base">Sport - Perforat</span>
            </div>

            <div class="flex flex-col items-end">
              <span class="font-bold text-white lg:text-lg">390 RON</span>
            </div>
          </div>
        </div>
        <!-- Disc frana - end -->

        <!-- Kit Ambreiaj - start -->
        <div class="product" data-page="2">
          <a href="#" class="group relative block h-60 overflow-hidden rounded-t-2xl shadow-2xl bg-gray-500">
            <img
              src="https://media.autodoc.de/360_photos/7885964/h-preview.jpg"
              loading="lazy" alt=""
              class="h-full p-2 rounded-2xl w-full object-cover object-center transition duration-200" />
          </a>

          <div class="flex items-start justify-between gap-2 rounded-b-2xl bg-gray-500 p-4">
            <div class="flex flex-col">
              <a href="#"
                class="font-bold text-white transition duration-200 hover:text-gray-200 lg:text-lg">Kit Ambreiaj</a>
              <span class="text-sm text-gray-300 lg:text-base">Placa, disc și rulment</span>
            </div>

            <div class="flex flex-col items-end">
              <span class="font-bold text-white lg:text-lg">390 RON</span>
            </div>
          </div>
        </div>
        <!-- Kit ambreiaj - end -->

        <!-- Bujie - start -->
        <div class="product" data-page="2">
          <a href="#" class="group relative block h-60 overflow-hidden rounded-t-2xl shadow-2xl bg-gray-500">
            <img
              src="https://s13emagst.akamaized.net/products/5637/5636949/images/res_d3ccd95a07a87a7ad7f1a0f4fe195b1a.jpg"
              loading="lazy" alt=""
              class="h-full p-2 rounded-2xl w-full object-cover object-center transition duration-200" />
          </a>

          <div class="flex items-start justify-between gap-2 rounded-b-2xl bg-gray-500 p-4">
            <div class="flex flex-col">
              <a href="#"
                class="font-bold text-white transition duration-200 hover:text-gray-200 lg:text-lg">Bujie</a>
              <span class="text-sm text-gray-300 lg:text-base">Aprindere scânteie</span>
            </div>

            <div class="flex flex-col items-end">
              <span class="font-bold text-white lg:text-lg">100 RON</span>
            </div>
          </div>
        </div>
        <!-- Bujie - end -->

        <!-- Amortizoare - start -->
        <div class="product" data-page="2">
          <a href="#" class="group relative block h-60 overflow-hidden rounded-t-2xl shadow-2xl bg-gray-500">
            <img
              src="https://www.pieseauto.ro/poze/poza/poza-07eb5f1721d68a9100-0-0-0-0-0.jpg"
              loading="lazy" alt=""
              class="h-full p-2 rounded-2xl w-full object-cover object-center transition duration-200" />
          </a>

          <div class="flex items-start justify-between gap-2 rounded-b-2xl bg-gray-500 p-4">
            <div class="flex flex-col">
              <a href="#"
                class="font-bold text-white transition duration-200 hover:text-gray-200 lg:text-lg">Amortizoare</a>
              <span class="text-sm text-gray-300 lg:text-base">Aluminiu Roșu</span>
            </div>

            <div class="flex flex-col items-end">
              <span class="font-bold text-white lg:text-lg">900 RON</span>
            </div>
          </div>
        </div>
        <!-- Amortizoare - end -->

        <!-- Nuca schimbator - start -->
        <div class="product" data-page="2">
          <a href="#" class="group relative block h-60 overflow-hidden rounded-t-2xl shadow-2xl bg-gray-500">
            <img
              src="https://raftulcupiese.ro/wp-content/uploads/Nuca-schimbator-BMW-M-Piele-perforata-E36-E46-E90-E91-E92-centru.jpg"
              loading="lazy" alt=""
              class="h-full p-2 rounded-2xl w-full object-cover object-center transition duration-200" />
          </a>

          <div class="flex items-start justify-between gap-2 rounded-b-2xl bg-gray-500 p-4">
            <div class="flex flex-col">
              <a href="#"
                class="font-bold text-white transition duration-200 hover:text-gray-200 lg:text-lg">Nucă Schimbător</a>
              <span class="text-sm text-gray-300 lg:text-base">BMW M - Piele</span>
            </div>

            <div class="flex flex-col items-end">
              <span class="font-bold text-white lg:text-lg">100 RON</span>
            </div>
          </div>
        </div>
        <!-- Nuca schimbator - end -->

        <!-- Prezoane - start -->
        <div class="product" data-page="2">
          <a href="#" class="group relative block h-60 overflow-hidden rounded-t-2xl shadow-2xl bg-gray-500">
            <img
              src="https://img.rapidauto.ro/I210817/4/520504-set-prezoane-auto-antifurt-carpoint-tip-d-m14x1-5x26mm-rotund-pentru-audi-rover-.jpg"
              loading="lazy" alt=""
              class="h-full p-2 rounded-2xl w-full object-cover object-center transition duration-200" />
          </a>

          <div class="flex items-start justify-between gap-2 rounded-b-2xl bg-gray-500 p-4">
            <div class="flex flex-col">
              <a href="#"
                class="font-bold text-white transition duration-200 hover:text-gray-200 lg:text-lg">Prezoane</a>
              <span class="text-sm text-gray-300 lg:text-base">4 buc / set</span>
            </div>

            <div class="flex flex-col items-end">
              <span class="font-bold text-white lg:text-lg">100 RON</span>
            </div>
          </div>
        </div>
        <!-- Prezoane - end -->

        <!-- Chiulasa - start -->
        <div class="product" data-page="2">
          <a href="#" class="group relative block h-60 overflow-hidden rounded-t-2xl shadow-2xl bg-gray-500">
            <img
              src="https://newpartsauto.files.wordpress.com/2012/08/chiulasa.jpg"
              loading="lazy" alt=""
              class="h-full p-2 rounded-2xl w-full object-cover object-center transition duration-200" />
          </a>

          <div class="flex items-start justify-between gap-2 rounded-b-2xl bg-gray-500 p-4">
            <div class="flex flex-col">
              <a href="#"
                class="font-bold text-white transition duration-200 hover:text-gray-200 lg:text-lg">Chiulasă</a>
              <span class="text-sm text-gray-300 lg:text-base">3 cilindrii</span>
            </div>

            <div class="flex flex-col items-end">
              <span class="font-bold text-white lg:text-lg">100 RON</span>
            </div>
          </div>
        </div>
        <!-- Chiulasa - end -->

        <!-- Apple Carplay - start -->
        <div class="product" data-page="3">
          <a href="#" class="group relative block h-60 overflow-hidden rounded-t-2xl shadow-2xl bg-gray-500">
            <img
              src="https://images-fe.ssl-images-amazon.com/images/I/71vdkKGRgXL._AC_UL600_SR600,600_.jpg"
              loading="lazy" alt=""
              class="h-full p-2 rounded-2xl w-full object-cover object-center transition duration-200" />
          </a>

          <div class="flex items-start justify-between gap-2 rounded-b-2xl bg-gray-500 p-4">
            <div class="flex flex-col">
              <a href="#"
                class="font-bold text-white transition duration-200 hover:text-gray-200 lg:text-lg">Apple Carplay</a>
              <span class="text-sm text-gray-300 lg:text-base">Touchscreen 10.1"</span>
            </div>

            <div class="flex flex-col items-end">
              <span class="font-bold text-white lg:text-lg">100 RON</span>
            </div>
          </div>
        </div>
        <!-- Apple Carplay - end -->

        <!-- Chiulasa - start -->
        <div class="product" data-page="3">
          <a href="#" class="group relative block h-60 overflow-hidden rounded-t-2xl shadow-2xl bg-gray-500">
            <img
              src="https://ireland.apollo.olxcdn.com/v1/files/ns1ashbx1ptz-PT/image"
              loading="lazy" alt=""
              class="h-full p-2 rounded-2xl w-full object-cover object-center transition duration-200" />
          </a>

          <div class="flex items-start justify-between gap-2 rounded-b-2xl bg-gray-500 p-4">
            <div class="flex flex-col">
              <a href="#"
                class="font-bold text-white transition duration-200 hover:text-gray-200 lg:text-lg">Climatronic Audi</a>
              <span class="text-sm text-gray-300 lg:text-base">3 cilindrii</span>
            </div>

            <div class="flex flex-col items-end">
              <span class="font-bold text-white lg:text-lg">100 RON</span>
            </div>
          </div>
        </div>
        <!-- Chiulasa - end -->

        <!-- Chiulasa - start -->
        <div class="product" data-page="3">
          <a href="#" class="group relative block h-60 overflow-hidden rounded-t-2xl shadow-2xl bg-gray-500">
            <img
              src="https://newpartsauto.files.wordpress.com/2012/08/chiulasa.jpg"
              loading="lazy" alt=""
              class="h-full p-2 rounded-2xl w-full object-cover object-center transition duration-200" />
          </a>

          <div class="flex items-start justify-between gap-2 rounded-b-2xl bg-gray-500 p-4">
            <div class="flex flex-col">
              <a href="#"
                class="font-bold text-white transition duration-200 hover:text-gray-200 lg:text-lg">Chiulasă</a>
              <span class="text-sm text-gray-300 lg:text-base">3 cilindrii</span>
            </div>

            <div class="flex flex-col items-end">
              <span class="font-bold text-white lg:text-lg">100 RON</span>
            </div>
          </div>
        </div>
        <!-- Chiulasa - end -->

        <!-- Chiulasa - start -->
        <div class="product" data-page="3">
          <a href="#" class="group relative block h-60 overflow-hidden rounded-t-2xl shadow-2xl bg-gray-500">
            <img
              src="https://newpartsauto.files.wordpress.com/2012/08/chiulasa.jpg"
              loading="lazy" alt=""
              class="h-full p-2 rounded-2xl w-full object-cover object-center transition duration-200" />
          </a>

          <div class="flex items-start justify-between gap-2 rounded-b-2xl bg-gray-500 p-4">
            <div class="flex flex-col">
              <a href="#"
                class="font-bold text-white transition duration-200 hover:text-gray-200 lg:text-lg">Chiulasă</a>
              <span class="text-sm text-gray-300 lg:text-base">3 cilindrii</span>
            </div>

            <div class="flex flex-col items-end">
              <span class="font-bold text-white lg:text-lg">100 RON</span>
            </div>
          </div>
        </div>
        <!-- Chiulasa - end -->

        <!-- Chiulasa - start -->
        <div class="product" data-page="3">
          <a href="#" class="group relative block h-60 overflow-hidden rounded-t-2xl shadow-2xl bg-gray-500">
            <img
              src="https://newpartsauto.files.wordpress.com/2012/08/chiulasa.jpg"
              loading="lazy" alt=""
              class="h-full p-2 rounded-2xl w-full object-cover object-center transition duration-200" />
          </a>

          <div class="flex items-start justify-between gap-2 rounded-b-2xl bg-gray-500 p-4">
            <div class="flex flex-col">
              <a href="#"
                class="font-bold text-white transition duration-200 hover:text-gray-200 lg:text-lg">Chiulasă</a>
              <span class="text-sm text-gray-300 lg:text-base">3 cilindrii</span>
            </div>

            <div class="flex flex-col items-end">
              <span class="font-bold text-white lg:text-lg">100 RON</span>
            </div>
          </div>
        </div>
        <!-- Chiulasa - end -->

        <!-- Chiulasa - start -->
        <div class="product" data-page="3">
          <a href="#" class="group relative block h-60 overflow-hidden rounded-t-2xl shadow-2xl bg-gray-500">
            <img
              src="https://newpartsauto.files.wordpress.com/2012/08/chiulasa.jpg"
              loading="lazy" alt=""
              class="h-full p-2 rounded-2xl w-full object-cover object-center transition duration-200" />
          </a>

          <div class="flex items-start justify-between gap-2 rounded-b-2xl bg-gray-500 p-4">
            <div class="flex flex-col">
              <a href="#"
                class="font-bold text-white transition duration-200 hover:text-gray-200 lg:text-lg">Chiulasă</a>
              <span class="text-sm text-gray-300 lg:text-base">3 cilindrii</span>
            </div>

            <div class="flex flex-col items-end">
              <span class="font-bold text-white lg:text-lg">100 RON</span>
            </div>
          </div>
        </div>
        <!-- Chiulasa - end -->

        <!-- Chiulasa - start -->
        <div class="product" data-page="3">
          <a href="#" class="group relative block h-60 overflow-hidden rounded-t-2xl shadow-2xl bg-gray-500">
            <img
              src="https://newpartsauto.files.wordpress.com/2012/08/chiulasa.jpg"
              loading="lazy" alt=""
              class="h-full p-2 rounded-2xl w-full object-cover object-center transition duration-200" />
          </a>

          <div class="flex items-start justify-between gap-2 rounded-b-2xl bg-gray-500 p-4">
            <div class="flex flex-col">
              <a href="#"
                class="font-bold text-white transition duration-200 hover:text-gray-200 lg:text-lg">Chiulasă</a>
              <span class="text-sm text-gray-300 lg:text-base">3 cilindrii</span>
            </div>

            <div class="flex flex-col items-end">
              <span class="font-bold text-white lg:text-lg">100 RON</span>
            </div>
          </div>
        </div>
        <!-- Chiulasa - end -->

        <!-- Chiulasa - start -->
        <div class="product" data-page="3">
          <a href="#" class="group relative block h-60 overflow-hidden rounded-t-2xl shadow-2xl bg-gray-500">
            <img
              src="https://newpartsauto.files.wordpress.com/2012/08/chiulasa.jpg"
              loading="lazy" alt=""
              class="h-full p-2 rounded-2xl w-full object-cover object-center transition duration-200" />
          </a>

          <div class="flex items-start justify-between gap-2 rounded-b-2xl bg-gray-500 p-4">
            <div class="flex flex-col">
              <a href="#"
                class="font-bold text-white transition duration-200 hover:text-gray-200 lg:text-lg">Chiulasă</a>
              <span class="text-sm text-gray-300 lg:text-base">3 cilindrii</span>
            </div>

            <div class="flex flex-col items-end">
              <span class="font-bold text-white lg:text-lg">100 RON</span>
            </div>
          </div>
        </div>
        <!-- Chiulasa - end -->

      </div>

      <!-- Navigation -->
      <div class="flex justify-center mt-20">
        <button id="prev-page-btn" class="mr-2 bg-gray-200 hover:bg-gray-300 px-3 py-1 rounded-md transition duration-200 focus:outline-none">
          <img class="w-4" src="https://www.svgrepo.com/show/533620/arrow-sm-left.svg" alt="">
        </button>

        <div class="flex">
          <button class="page-number bg-gray-200 hover:bg-gray-300 rounded-tl-md rounded-bl-md transition duration-200 px-3 py-1 focus:outline-none"
            data-page="1">1</button>
          <button class="page-number bg-gray-200 hover:bg-gray-300 px-3 py-1 transition duration-200 focus:outline-none"
            data-page="2">2</button>
          <button class="page-number bg-gray-200 hover:bg-gray-300 rounded-tr-md rounded-br-md transition duration-200 px-3 py-1 focus:outline-none"
            data-page="3">3</button>
        </div>

        <button id="next-page-btn" class="ml-2 bg-gray-200 hover:bg-gray-300 px-3 py-1 rounded-md transition duration-200 focus:outline-none">
          <img class="w-4" src="https://www.svgrepo.com/show/533621/arrow-sm-right.svg" alt="">
        </button>
      </div>
      <!-- Navigation - end -->

    </div>
  </div>
</template>

<script>
export default {
  mounted() {
    const totalPages = 3;
    let currentPage = 1;

    function showPage(pageNumber) {
      const products = document.querySelectorAll(".product");
      products.forEach((product) => {
        if (product.dataset.page === pageNumber.toString()) {
          product.classList.remove("hidden");
        } else {
          product.classList.add("hidden");
        }
      });
    }

    function nextPage() {
      if (currentPage < totalPages) {
        currentPage++;
        showPage(currentPage);
      }
    }

    function previousPage() {
      if (currentPage > 1) {
        currentPage--;
        showPage(currentPage);
      }
    }

    document.getElementById("next-page-btn").addEventListener("click", nextPage);
    document.getElementById("prev-page-btn").addEventListener("click", previousPage);

    document.querySelectorAll(".page-number").forEach((pageNumberBtn) => {
      pageNumberBtn.addEventListener("click", function () {
        const page = parseInt(this.dataset.page);
        currentPage = page;
        showPage(page);
      });
    });

    showPage(currentPage);
  }
}
</script>
