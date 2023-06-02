# TR
## 👨🏻‍💻 Kullanılan Teknolojiler
- Alpine.js
- Astro.js
- Bootstrap

## 🚀 Proje Yapısı
Proje içerisindeki klasör ve dosyalar:
```
/
├── api/
│   └── advices.json
│
├── public/
│   └── favicon.svg
│
├── src/
│   ├── components/
│   │   └── Navbar.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       ├── index.astro
│       ├── tavsiyegiris.astro
│       └── tavsiyelistesi.astro
│
└── package.json
```

## 🧞 Komutlar
Geliştirmeye yardım etmek veya kendi bilgisaayarınızda test etmek için kullanmanız için terminale ``npm i`` yazıp devam ettikten sonra, ``npm run dev`` komutu ile projeyi çalıştırabilirsiniz. Proje sorunsuz bir şekilde çalıaşacaktır.

| Komut                     | Yapacağı İş                                                          |
| :------------------------ | :------------------------------------------------------------------- |
| `npm install`             | Proje gerekliliklerini yükler                                        |
| `npm run dev`             | Local geliştirme sunucusunu `localhost:3000` adresinde başlatır      |
| `npm run  build`          | `./dist/` klasörüne projeyi build ecektir                            |
| `npm run preview`         | Yayınlama aşamasından önce yerel sunucuda build'i önizleyin          |
| `npm run astro ...`       | `astro add`, `astro check` gibi CLI komutlarını çalıştırır           |
| `npm run astro -- --help` | Astro CLI hakkında bilgi alın                                        |

## Eklenecek Özellikler
1. Günlük Tavsiye ve anasayfa birbirinden ayrılacak
2. anasayfada tanıtım olacak, nasıl destek olunacağı yazacak ve günlük tavsiye butonuna yönlendirme olacak
3. Tavsiye girişi yapılacak
4. dark ve light mode eklenecek
5. tr ve en dil destekleri eklenece

# EN
## 👨🏻‍💻 Tech Stack
- Alpine.js
- Astro.js
- Bootstrap

## 🚀 Project Structure
Folders and files in the project:
```
/
├── api/
│   └── advices.json
│
├── public/
│   └── favicon.svg
│
├── src/
│   ├── components/
│   │   └── Navbar.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       ├── index.astro
│       ├── tavsiyegiris.astro
│       └── tavsiyelistesi.astro
│
└── package.json
```

## 🧞 Commands
To help with development or to test it on your own computer, you can run the project by typing ``npm i`` in the terminal and then ``npm run dev``. The project will run without any problems.

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:3000`      |
| `npm run  build`          | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |
