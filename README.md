# Chapter 5. Setup Environment React Native

## Mobile Application Development, Semester 2, Tahun Akademik 2022/2023

## #Group Exercise 06

Pada Chapter ini kita akan melakukan instalasi [react native]. Pada latihan ini anda diminta untuk menginstall React Native CLI (Bukan Expo) dilaptop/PC masing-masing, dimana langkah-langkahnya adalah sebagai berikut:

- Install Node, JDK
- Install Android Studio & SDK
- Konfigurasi tambahan (khusus yang menggunakan processor [AMD])
- Configure the ANDROID_HOME environment variable & Add platform-tools to Path
- Install Android Emulator (optional - bisa dilewati jika anda ingin menjalankan aplikasi langsung dari hp. Baca dokumentasi [running on device])
- Create project React Native menggunakan npx
- Run project

## Status Instalasi

| Langkah-langkah                           | Status     | Versi         |
| ----------------------------------------- | ------     | -----         |
| Instalasi Node                            |Done        |   v18.14.2    |
| Instalasi JDK                             |Done        |  java 19.0.2       2023-01-17               |
| Android Studio                            |Done        |Electric Eel 2022.1.1               |
| SDK                                       |Done        |30              |
| ANDROID_HOME & Add platform-tools to Path |Done        | -             |
| Android Emulator (opt)                    |Done        | Pixel API 30        |
| Create Project RN using npx               |Done            | -             |
| Run Project on Emulator / Device          |Done            | -             |

Silahkan update status instalasi anda, apabila sudah terinstall silahkan isi versinya:
untuk mengetahui versi node ketik dari cmd (node -v) untuk mengetahui versi JDK ketik dari cmd (java --version).


## Langkah-langkah Pengumpulan Latihan

- Fork project github ini. Ada terdapat 3 branch yaitu: master, parallel-a, parallel-b
- Dari local laptop/PC anda buat branch baru dengan nama sesuai dengan nama kelompok anda. contoh: berlin
- Buat file baru sama seperti nama branch anda dengan format .md. contoh: berlin.md
- Edit file tersebut dengan mengisi status instalasi pada tabel yang sudah disediakan.
- git add dan commit dengan commit message "adding berlin.md"
- lakukan pull request ke dalam branch sesuai dengan parallel kelas anda. (Bukan Branch Master)

  [react native]: https://reactnative.dev/docs/environment-setup
  [running on device]: https://reactnative.dev/docs/running-on-device
  [amd]: https://android-developers.googleblog.com/2018/07/android-emulator-amd-processor-hyper-v.html
  [openjdk 11.0.5 2019-10-15]: https://docs.aws.amazon.com/corretto/latest/corretto-11-ug/downloads-list.html
