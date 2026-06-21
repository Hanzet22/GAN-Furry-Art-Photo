# GAN-Furry-Art-Photo

# 4x Anime/Furry Image Upscaler (Real-ESRGAN)

*Mending sebelum kalian pake, UTAMAKAN LITERASI ANJ*

### Daftar Isi / List of Contents

1. [Fitur / Features](#-features)
2. [Cara Pake / How To Use](#%EF%B8%8F-how-to-use)
3. [Kredit / Credits](#-credits--acknowledgements)
4. [Lisensi / License](#-license)
5. [Baca ini biar gak Mines Literasi / Read this so you don't have a lack of literacy](#catatan)
6. [Indonesia Series](#qa-mode-goo)
7. [English Series](#qa-mode-goo-euro-j-edition-malas-lempar--gw-capek)

A ready-to-use Google Colab notebook for upscaling Anime and Furry artwork using Real-ESRGAN. This script is pre-configured with the `RealESRGAN_x4plus_anime_6B` and `RealESRGAN_x4plus` model to ensure high-quality 4x upscaling without common architecture mismatch errors.

## 🚀 Features
- **One-Click Setup:** Automatic installation of dependencies and model downloading.
- **Optimized for Anime:** Uses the `anime_6B` model which is best suited for 2D illustrations, furry art, and anime styles.
- **Bug-Free:** Includes fixed parameters (`--model_name`) to prevent `Missing key(s)` state_dict errors. (Jangan harap Kaga ada Bug AWOKAWOKAWOK, Free Bug itu MITHOSSSSSSSS)
- **Automated Workflow:** Handles image upload, upscaling, and zipping results for easy download.

## 🛠️ How to Use
1. Open the `.ipynb` file in [Google Colab](https://colab.research.google.com/).
2. Run all cells sequentially.
3. Upload your images when prompted.
4. Wait for the process to finish and download the `results.zip`.

## 📜 Credits & Acknowledgements
This project is built upon the amazing work of the Real-ESRGAN team and brilliant community model creators. All credit for the core technology and models goes to:

- **Real-ESRGAN Repository:** [xinntao/Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN)
- **Lead Author:** [Xintao Wang](https://github.com/xinntao)
- **Contributors:** ARC Lab, Tencent PCG; Shanghai AI Laboratory; and other contributors listed in the original repository.
- **HuggingFace Community Models:** Special thanks to Kim2091 (UltraSharp), NMKD (Superscale), and the open-source AI community for developing custom ESRGAN weights hosted on HuggingFace.

> **Note:** This notebook is a convenience wrapper designed to simplify the usage of Real-ESRGAN and custom HuggingFace community models for specific upscaling tasks on Google Colab.

## 📄 License
The underlying Real-ESRGAN code is licensed under the BSD 3-Clause License. Please refer to the [original repository](https://github.com/xinntao/Real-ESRGAN) for full license details. Custom community models follow their respective non-commercial or open-source licenses as provided by their authors on HuggingFace.


## CATATAN
If someone suddenly says `THIS IS ILLEGALLY TRAIN AI, DON'T USE IT.` You're bullshit, this is Upscaler not *"AI Buatkan aku foto Furry bergaya dihotel Anthrocon"* NOPE. AND ONE MORE MOST CRUCIAL **AS LONG AS YOU USE FURRY PEOPLE'S PHOTOS OR PEOPLE'S ART, THE RESPONSIBILITY IS IN YOUR OWN HANDS, NOT ME**

## Q&A Mode Goo
* **Q: INI BUAT TRAIN AI INI, KAMI TOLAK! 😡**
  * **A:** Literasi tolong ditingkatkan. Ini **UPSCALER**, BUKAN GENERATIVE AI sekelas Gemini atau Midjourney yang melatih data dari nol. Alat ini cuma memperbaiki resolusi gambar pecah agar menjadi tajam.

* **Q: Ada Ransomware-nya enggak bang? 😨**
  * **A:** W-R-A-P-P-E-R, oke? Semua baris kode di skrip ini terbuka lebar (*open-source*). Kalau lu paranoid dan malas membaca isinya, silakan bikin dan koding sendiri dari awal sana!

* **Q: Bang, kok pas gua jalanin selnya ada eror merah tulisan "Runtime Disconnected"?**
  * **A:** Itu Google Colab lu disepak servernya karena lu kesamaan dapet kuota GPU gratisan, atau kuota lu abis. Server Google bukan punya bapak gua, jadi jangan komplain ke repo ini! AWOKAWOKAWOK.

* **Q: Bisa buat upscale foto asli pacar saya gak biar jadi HD?**
  * **A:** Baca judulnya: **Anime/Furry Image Upscaler**. Ini di-optimize pake model `anime_6B`. Kalau lu paksain pake foto manusia asli, ntar muka pacar lu malah berubah jadi mulus mirip karakter VTuber 2D. Jangan salahin gua.

* **Q: Hasil download-annya kok format .zip? Ribet amat harus di-extract dulu!**
  * **A:** Ya kalau lu upload gambarnya 50 biji sekaligus, masa Google Colab-nya harus kirim filenya satu-satu lewat JNE? Dibundel jadi `.zip` biar lu sekali klik langsung ke-download semua, dasar pemalas.

* **Q: Akun GitHub lu aman kan bang? Takutnya lu maling cookie atau data privat gua.**
  * **A:** Lu pikir gua se-gabut itu sampai mau nge-hack data orang lewat notebook Colab open-source? Lagian ini script jalan di virtual machine milik Google, bukan di PC lu. Tolong kursus komputer dasar dulu gih.

* **Q: Kenapa gak dibikin jadi aplikasi .exe atau web aja biar gak usah buka Colab?**
  * **A:** Lu mau patungan bayar sewa server GPU bulanan atau beliin gua PC spek dewa buat nge-render gambar 4K lu? Kagak kan? Makanya kita numpang pake cloud GPU gratisan punya Google. Bersyukur dikit lah!

* **Q: Bang, kok hasil gambarnya setelah di-upscale malah kelihatan aneh/pecah di bagian tertentu?**
  * **A:** AI ini fungsinya *memperbaiki* resolusi, bukan melakukan keajaiban sihir. Kalau gambar input asli yang lu masukin udah sekecil semut, burik, dan penuh kompresi buruk, ya hasilnya gak bakal bisa langsung kayak buatan artist pro. *Garbage in, garbage out!*

 - **Q: Bang, kok proses upscaling-nya lama bener? Katanya One-Click? 🥱**  
- **A:** One-Click itu instalasinya, bukan proses rendernya langsung kelar sedetik. Kecepatan render itu tergantung ukuran gambar lu dan sisa amal ibadah GPU gratisan lu hari ini.  
  
  
- **Q: Ini beneran gratis kan bang? Gak bakal ditagih duit kan? 💸**  
- **A:** GRATIS 100%. Lu cuma modal kuota sama akun Google doang. Kalau ada tagihan masuk ke email lu, itu paling tagihan PayLater lu yang lupa dibayar. Jangan nuduh repo ini.  
  
  
- **Q: Bang, kalau gambar gua udah 4K, bisa di-upscale jadi 16K gak? 🤔**  
- **A:** Bisa, tapi RAM gratisan Google Colab bakal langsung meledak kena *Out of Memory* (OOM). Lagian lu mau cetak baliho furry segede lapangan bola buat apa? Gunakan logika.  
  
  
- **Q: Kenapa pake model RealESRGAN_x4plus_anime_6B? Gak pake model lain? 🛠️**  
- **A:** Karena model `anime_6B` ini paling stabil buat gambar 2D, anime, dan Furry art. Kalau gua pasang model sembarangan, ntar hasil gambar lu penuh sensor garis mirip TV nasional.  
  
  
- **Q: Bang, ada versi mobile-nya gak? Gua males buka laptop. 📱**  
- **A:** Colab itu basisnya web, jadi BISA dibuka di HP lewat browser. Tapi tanggung sendiri pusingnya nge-scroll kodingan di layar HP yang seuprit. Jangan malas, buka laptop lu.  
  
  
- **Q: Kenapa file output-nya harus dinamain results.zip? Gak bisa nama lain? 📦**  
- **A:** Bisa aja gua ganti jadi `amal_ibadah.zip`, tapi demi standarisasi kodingan, nama `results.zip` itu paling waras. Kalau lu pengen nama lain, ntar kalau udah kelar download lu *rename* sendiri.  
  
  
- **Q: Script ini aman dari pelacakan pemerintah atau hacker internasional gak bang? 🕵️**  
- **A:** Lu cuma mau nge-upscale gambar karakter hewan antropomorfik berbulu, bukan lagi meretas pangkalan data Pentagon. Pemerintah juga males ngelacak hobi lu, gak usah merasa kayak agen rahasia.  
  
  
- **Q: Bang, kok pas gua klik 'Run All', ada lingkaran muter terus gak berhenti? 🔄**  
- **A:** Itu namanya proses download model Real-ESRGAN ke virtual machine Google, pinter. Internet lu mungkin lagi sekarat, jadi tungguin aja sampai selesai muter, jangan panik.  
  
  
- **Q: Kalau gua ketahuan pake tools ini sama artist original-nya, gua bakal dituntut gak? ⚖️**  
- **A:** Baca lagi bagian **CATATAN** di atas pake kacamata pembesar. Segala urusan hak cipta dan izin itu tanggung jawab LU SENDIRI. Gua cuma sediain tools, bukan penampung dosa lu. Dan satu lagi **DERITA LOE AWOKAWOKAWOK**
  
  
- **Q: Bang, script-nya bisa dipake offline gak kalau gua lagi gak ada kuota? ✈️**  
- **A:** Ini berjalan di atas infrastruktur Cloud milik Google. Kalau internet lu mati ya script-nya mogok. Pertanyaan lu setara kayak nanya "Bisa gak nonton YouTube pas HP mode pesawat tanpa Wi-Fi?" AWOKAWOKAWOK.  
  
  
- **Q: Kok ada eror 'ModuleNotFoundError: No module named...' padahal gua udah ikuti cara lu? ❌**  
- **A:** Itu artinya lu bebal dan gak baca instruksi nomor 2: *"Run all cells sequentially"*. Lu pasti langsung lompat ke cell bawah tanpa jalanin cell instalasi di atasnya. Kebiasaan pengen cepet tapi males baca.  
  
  
- **Q: Bang, foto profil GitHub lu kok aneh banget sih? 🤨**  
- **A:** Urusan foto profil gua gak ada hubungannya sama performa upscaler Real-ESRGAN ini. Fokus ke kodenya, jangan fokus ke kehidupan pribadi gua. Gua di sini koding, bukan nyari jodoh.  
  
  
- **Q: Tools ini bisa bikin gambar yang blur-nya parah banget jadi super tajam gak? 📷**  
- **A:** Lu kira ini teknologi film Hollywood? Kalau foto aslinya udah kayak jepretan HP 3gp tahun 2005, AI ini cuma bisa bantu maksimalin seadanya, gak bisa merekonstruksi data pixel yang emang udah hilang dari awal.  
  
  
- **Q: Gua mau donasi nih bang, ada link Saweria atau Trakteer gak? 🪙**  
- **A:** Kagak usah donasi duit. Cukup lu bintangin (Give a Star ⭐) repositori ini dan JANGAN LAPORKAN (Don't Report) akun gua lagi ke admin komunitas lu, itu udah bikin gua seneng di Season Dua ini.  
  
  
- **Q: Bang, kok pas gua upload gambar banyak sekaligus, prosesnya tiba-tiba berhenti? 🛑**  
- **A:** Google Colab punya batas memori untuk pengguna gratisan. Kalau lu serakah langsung upload ratusan gambar resolusi tinggi sekaligus, sistem Google bakal otomatis nendang sesi lu. Upload dicicil sedikit-sedikit!  
  
  
- **Q: Ini beneran buatan lu sendiri bang dari nol kodenya? 🧠**  
- **A:** BACA bagian **Credits & Acknowledgements**! Teknologi intinya punya tim Real-ESRGAN (Xinntao dkk). Gua di sini cuma bikin *convenience wrapper* berupa file notebook biar kaum awam kayak lu tinggal klak-klik doang langsung jalan.  
  
  
- **Q: Kenapa lu ketawa 'AWOKAWOKAWOK' terus di setiap dokumentasi? Gak bisa formal ya? 🤣**  
- **A:** Akun GitHub ini punya gua, hak asasi gua mau nulis pake gaya bahasa apa. Lagian gaya bahasa formal terbukti gagal menyelamatkan gua dari depakan Season Satu kemarin, jadi sekarang kita pake jalur bar-bar biar hater-nya kesaring.  
  
  
- **Q: Bang, kalau gua nemu bug yang beneran merusak sistem Colab-nya gimana? 🐛**  
- **A:** Silakan buka menu *Issues* di GitHub ini, tulis erornya dengan jelas beserta screenshot-nya. JANGAN cuma chat gua pake kalimat *"Bang eror bang"* tanpa detail apa-apa. Gua programmer, bukan dukun ramal.  
  
  
- **Q: Model anime_6B ini aman dari virus yang bisa ngerusak Windows gua gak bang? 🛡️**  
- **A:** File model ini di-download dan dijalankan di dalam server virtual Linux milik Google Colab, bukan di dalam komputer Windows lu. Jadi file itu gak bakal bisa menyentuh Drive C lu sama sekali. Tolong bedakan cloud sama lokal.  
  
  
- **Q: Pertanyaan terakhir bang, lu kapok gak kalau nanti didepak lagi di Season Dua? 💀**  
- **A:** Kagak ada kata kapok di kamus gua. Akun bisa dibikin lagi, repo bisa di-backup. Selama internet jalan dan Google Colab masih ngasih GPU gratisan, script upscaler ini bakal tetep hidup. Yang hater silakan menangis di pojokan!

## Q&A Mode Goo Euro J Edition (malas lempar * gw, Capek)

* Q: THIS IS AI TRAINING! WE REJECT THIS! 😡
  
  * A: Please improve your reading comprehension. This is an UPSCALER, NOT a generative AI like Gemini or Midjourney that trains models from scratch. This tool simply improves the resolution of blurry or low-quality images.

* Q: Does it contain ransomware or something? 😨
  
  * A: It's called a W-R-A-P-P-E-R, okay? Every line of code in this script is completely open-source. If you're paranoid and too lazy to read it, feel free to build and code your own version from scratch.

* Q: Bro, why does it say "Runtime Disconnected" when I run the cells?
  
  * A: That's Google Colab kicking your session because your free GPU quota ran out, or Colab simply decided your session had enough fun for today. Google's servers don't belong to my dad, so don't complain to this repository. AWOKAWOKAWOK.

* Q: Can I upscale a real-life photo of my girlfriend with this?
  
  * A: Read the title again: Anime/Furry Image Upscaler. This notebook is optimized using the "anime_6B" model. If you force it to process real human photos, your girlfriend might come out looking like a smooth 2D VTuber. Don't blame me.

* Q: Why are the results downloaded as a .zip file?
  
  * A: If you upload 50 images at once, what do you expect? Google Colab delivering them one by one through postal mail? They're bundled into a ".zip" so you can download everything in a single click. Lazy much?

* Q: Is your GitHub account safe? What if you're stealing my cookies or personal data?
  
  * A: Do you really think I'm bored enough to steal people's data through an open-source Colab notebook? This script runs on Google's virtual machine, not on your computer. Please take a basic computer literacy course first.

* Q: Why not make this a .exe application or a website instead of using Colab?
  
  * A: Are you going to help pay for GPU servers every month? Or maybe buy me a monster PC capable of processing your 4K images? No? Then that's why we're borrowing Google's free cloud GPUs. Show some gratitude.

* Q: Why do some parts of the image look weird after upscaling?
  
  * A: AI improves image resolution. It doesn't perform magical wizardry. If your original image is tiny, blurry, compressed to oblivion, and held together by hope and duct tape, don't expect professional-grade results. Garbage in, garbage out.

* Q: Why is the upscaling process so slow? You called it One-Click? 🥱
  
  * A: One-Click refers to the installation process, not instant rendering. Rendering speed depends on your image size and how much free GPU luck Google has blessed you with today.

* Q: Is this really free? You're not going to charge me later, right? 💸
  
  * A: 100% FREE. All you need is internet access and a Google account. If you receive a bill later, it's probably your forgotten Buy Now Pay Later payment. Don't blame this repository.

* Q: Can I upscale a 4K image into 16K? 🤔
  
  * A: Technically yes, but Google's free Colab RAM will probably explode with an Out of Memory (OOM) error. Besides, why do you need a furry billboard the size of a football field? Use common sense.

* Q: Why use RealESRGAN_x4plus_anime_6B instead of another model? 🛠️
  
  * A: Because "anime_6B" is one of the most stable options for anime, 2D illustrations, and furry artwork. If I randomly picked another model, your image might end up looking like a corrupted TV broadcast.

* Q: Is there a mobile version? 📱
  
  * A: Colab is web-based, so YES, you can open it in a mobile browser. But enjoy scrolling through notebook cells on a screen the size of a potato chip. Stop being lazy and use a laptop.

* Q: Why is the output file called results.zip? 📦
  
  * A: Sure, I could rename it to "good_deeds.zip", but "results.zip" is the most sane and standardized choice. If you want another name, rename it yourself after downloading.

* Q: Is this script safe from government tracking and international hackers? 🕵️
  
  * A: You're upscaling anthropomorphic furry artwork, not hacking the Pentagon. Governments are not interested in your hobby. Stop acting like a secret agent.

* Q: Why does the loading circle keep spinning forever after I click "Run All"? 🔄
  
  * A: That's the notebook downloading the Real-ESRGAN model into Google's virtual machine. Your internet connection is probably fighting for its life. Be patient and let it finish.

* Q: If the original artist finds out I used this tool, can I get sued? ⚖️
  
  * A: Read the NOTES section again, preferably with a magnifying glass. Copyright, permissions, and licensing issues are YOUR responsibility. I'm providing a tool, not absorbing your legal consequences.

* Q: Can I use this offline when I don't have internet access? ✈️
  
  * A: This runs on Google's cloud infrastructure. If your internet dies, the notebook dies with it. That's like asking whether you can watch YouTube in airplane mode without Wi-Fi. AWOKAWOKAWOK.

* Q: Why am I getting "ModuleNotFoundError: No module named..." even though I followed the instructions? ❌
  
  * A: That means you ignored Instruction #2: "Run all cells sequentially." You probably skipped the installation cell and jumped straight to the fun part. Classic impatient behavior.

* Q: Bro, why is your GitHub profile picture so weird? 🤨
  
  * A: My profile picture has absolutely nothing to do with Real-ESRGAN's performance. Focus on the code, not my personal life. I'm here to code, not to find a soulmate.

* Q: Can this tool turn an extremely blurry image into a perfectly sharp one? 📷
  
  * A: Do you think this is Hollywood movie technology? If your source image looks like a 2005 3GP phone photo, the AI can only improve it so much. It cannot reconstruct pixel information that never existed.

* Q: I want to donate. Do you have a Ko-fi or Patreon link? 🪙
  
  * A: No need to donate money. Just give the repository a Star ⭐ and PLEASE STOP REPORTING my account to community moderators. That already makes me happy enough in Season Two.

* Q: Why does the process stop when I upload too many images at once? 🛑
  
  * A: Google Colab has memory limits for free users. If you greedily upload hundreds of high-resolution images at once, Google will gladly kick your session out the door. Upload them in smaller batches.

* Q: Did you actually write all of this from scratch? 🧠
  
  * A: READ the Credits & Acknowledgements section. The core technology belongs to the Real-ESRGAN team (Xinntao and contributors). I simply created a convenience wrapper so ordinary people can click buttons and get results.

* Q: Why do you keep writing "AWOKAWOKAWOK" everywhere? 🤣
  
  * A: This GitHub account belongs to me. I can write however I want. Formal writing didn't save me from getting kicked out during Season One, so now we're using the chaotic route to filter out the haters.

* Q: What if I discover a bug that actually breaks the Colab notebook? 🐛
  
  * A: Open a GitHub Issue and provide a proper report with screenshots and error messages. DO NOT send me a message that just says "Bro it's broken" with zero details. I'm a programmer, not a fortune teller.

* Q: Is the anime_6B model safe? Can it infect my Windows PC with a virus? 🛡️
  
  * A: The model is downloaded and executed inside Google's Linux virtual machine, not on your Windows computer. It never touches your C: drive. Please learn the difference between cloud computing and local execution.

* Q: Final question. If you get kicked out again during Season Two, will you finally give up? 💀
  
  * A: There's no such word as "give up" in my dictionary. Accounts can be recreated. Repositories can be backed up. As long as the internet exists and Google keeps handing out free GPUs, this upscaler will continue to live on. The haters may cry in the corner.
