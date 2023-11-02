<template>
    <section>
        <div class="text-xs text-white font-bold bg-blue-950 h-6 pt-0.5">
            <NuxtLink class="ml-40 mr-20 hover:text-red-600" to="/">UNHAS</NuxtLink>
            <NuxtLink class="mr-96 hover:text-red-600" to="/">COT</NuxtLink>
            <NuxtLink class="ml-96 hover:text-red-600" to="/">PETA SITUS</NuxtLink>
            <NuxtLink class="ml-20 mr-40 hover:text-red-600" to="/">AKSES CEPAT</NuxtLink>   
        </div>

        <div class="bg-blue-900 overflow-hidden relative">
            <img class="w-20 h-24 ml-10 float-left mr-5 mt-5 mb-5" src="../assets/Logo Resmi Unhas.png" />
            <h1 class="font-bold text-white text-4xl mt-9">FAKULTAS TEKNIK</h1>
            <h1 class="font-medium text-white text-base">UNIVERSITAS HASANUDDIN</h1>
            
            <div class="border-2 absolute top-11 right-14 border-solid">
                <label for="searching"></label>
                <input class="bg-transparent text-white border-none outline-none w-72 h-12 ml-2" type="search" id="searching" placeholder="&nbsp;Cari" />
                <button><img class="w-5 h-5 float-right mt-2 mr-5" src="../assets/icon _search_.png" /></button>
            </div>
        </div>

        <div class="bg-red-600 space-x-11 h-12 pt-3">
            <NuxtLink class="font-bold text-white text-xs ml-11 hover:text-blue-950" to="/">BERANDA</NuxtLink>
            <NuxtLink class="font-bold text-white text-xs hover:text-blue-950" to="/">PROFIL</NuxtLink>
            <NuxtLink class="font-bold text-white text-xs hover:text-blue-950" to="/">SUMBER DAYA</NuxtLink>
            <NuxtLink class="font-bold text-white text-xs hover:text-blue-950" to="/">AKADEMIK</NuxtLink>
            <NuxtLink class="font-bold text-white text-xs hover:text-blue-950" to="/">KEMAHASISWAAN</NuxtLink>
            <NuxtLink class="font-bold text-white text-xs hover:text-blue-950" to="/">RISET DAN INOVASI</NuxtLink>
            <NuxtLink class="font-bold text-white text-xs hover:text-blue-950" to="/">KEMITRAAN</NuxtLink>
            <NuxtLink class="font-bold text-white text-xs hover:text-blue-950" to="/">GPM-PR</NuxtLink>
            <NuxtLink class="font-bold text-white text-xs hover:text-blue-950" to="/">DHARMA WANITA</NuxtLink>
            <NuxtLink class="" to="/"><img class="w-5 h-5 inline-block" src="../assets/Vector.png" /></NuxtLink>
        </div>
    </section>
</template>