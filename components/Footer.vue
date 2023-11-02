<template>
    <footer>
        <section class="bg-blue-900 h-full">
            <div class="overflow-hidden mb-10">
                <img class="h-12 ml-16 float-left mr-4 mt-14 mb-5" src="../assets/Logo Resmi Unhas.png" />
                <h1 class="font-bold text-white text-xl mt-14">FAKULTAS TEKNIK</h1>
                <h1 class="font-medium text-white text-xs">UNIVERSITAS HASANUDDIN</h1>
            </div>

            <div class="flex flex-wrap gap-x-24 mb-16">
                <div class="ml-20">
                    <h3 class="font-bold text-sm text-white mb-9" >INFORMASI LEBIH LANJUT</h3>

                    <nav>
                        <ul class="text-xs text-white">
                            <li><img class="h-3 float-left mr-5" src="../assets/lokasi.png" /> <NuxtLink to="/">Jalan Poros Malino Km. 6, Bontomarannu. Gowa, Sulawesi Selatan</NuxtLink></li><br/>
                            <li><img class="h-3 float-left mr-3" src="../assets/email.png" /> <NuxtLink to="/">engineering@unhas.ac.id</NuxtLink></li><br/>
                            <li><img class="h-3 float-left mr-5" src="../assets/call.png" /> <NuxtLink to="/">727-727-727-727</NuxtLink></li>
                        </ul>
                    </nav>
                </div>

                <div class="ml-9">
                    <h3 class="font-bold text-sm text-white mb-9" >DEPARTEMEN</h3>

                    <nav class="flex flex-wrap gap-5">
                        <ul class="text-xs text-white">
                            <li><NuxtLink to="/">Teknik Mesin</NuxtLink></li><br/>
                            <li><NuxtLink to="/">Teknik Sipil</NuxtLink></li><br/>
                            <li><NuxtLink to="/">Teknik Perkapalan</NuxtLink></li><br/>
                            <li><NuxtLink to="/">Teknik Elektro</NuxtLink></li><br/>
                            <li><NuxtLink to="/">Teknik Arsitektur</NuxtLink></li><br/>
                            <li><NuxtLink to="/">Teknik Geologi</NuxtLink></li><br/>
                        </ul>
                        <ul class="text-xs text-white">
                            <li><NuxtLink to="/">Teknik Kelautan</NuxtLink></li><br/>
                            <li><NuxtLink to="/">Teknik Sistem Perkapalan</NuxtLink></li><br/>
                            <li><NuxtLink to="/">Teknik Perencanaan Wilayah Kota</NuxtLink></li><br/>
                            <li><NuxtLink to="/">Teknik Pertambangan</NuxtLink></li><br/>
                            <li><NuxtLink to="/">Teknik Informatika</NuxtLink></li><br/>
                            <li><NuxtLink to="/">Teknik Lingkungan</NuxtLink></li><br/>
                        </ul>
                    </nav>
                </div>

                <div class="ml-9">
                    <h3 class="font-bold text-sm text-white mb-9" >TENTANG</h3>

                    <nav>
                        <ul class="text-xs text-white">
                            <li><NuxtLink to="/">Sejarah</NuxtLink></li><br/>
                            <li><NuxtLink to="/">Visi dan Misi</NuxtLink></li><br/>
                            <li><NuxtLink to="/">Manajemen</NuxtLink></li><br/>
                            <li><NuxtLink to="/">Peta Kampus</NuxtLink></li><br/>
                            <li><NuxtLink to="/">Pimpinan Fakultas</NuxtLink></li><br/>
                        </ul>
                    </nav>
                </div>

                <div class="ml-9">
                    <h3 class="font-bold text-sm text-white mb-9">DIDUKUNG OLEH</h3>
                    <div class="flex flex-wrap gap-3" >
                        <img class="h-10" src="../assets/dukung1.png" />
                        <img class="h-7" src="../assets/dukung2.png" />
                        <img class="h-9" src="../assets/dukung3.png" />
                    </div>
                </div>
            </div>

            <div class="flex flex-row gap-10">
                <div class="flex flex-wrap gap-x-5 ml-20 pb-5">
                    <NuxtLink to="/"><img class="h-5" src="../assets/fb.png" /></NuxtLink>
                    <NuxtLink to="/"><img class="h-5" src="../assets/twitter.png" /></NuxtLink>
                    <NuxtLink to="/"><img class="h-5" src="../assets/ig.png" /></NuxtLink>
                    <NuxtLink to="/"><img class="h-5" src="../assets/yt.png" /></NuxtLink>
                </div>

                <div>
                    <p class="font-semibold text-white text-sm">© 2023 Fakultas Teknik Universitas Hasanuddin</p>
                </div>
            </div>

        </section>
    </footer>
    
</template>