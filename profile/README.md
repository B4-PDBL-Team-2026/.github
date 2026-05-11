# 💸 MOCO: Your Financial Autopilot

![Moco Banner](https://via.placeholder.com/1200x300.png?text=MOCO+-+Engineering+Financial+Freedom) > **Berhenti mencatat masa lalu, mulai prediksikan masa depan.**
> Moco bukan sekadar aplikasi pencatat keuangan (*expense tracker*) biasa. Kami membangun ekosistem finansial proaktif yang bekerja secara otomatis untuk melacak, memprediksi, dan mengamankan pengeluaran Anda.
MOCO: Money Control
---

## 🚀 The Vision: Proactive > Reactive
Mayoritas money management app di luar sana itu pasif—mereka cuma "buku catatan digital". Pengguna dipaksa memasukkan data secara manual setiap hari. 

Moco dibangun dengan pendekatan **Proactive Money Management**. Melalui *Smart Fixed Cost Engine* kami, Moco memprediksi tagihan (mingguan/bulanan), melacak siklus pembayaran (*occurrences*), dan mengingatkan pengguna sebelum uang mereka habis. *It's not just a tracker; it's a financial autopilot.*

---

## 🛠️ Under The Hood (Our Engineering Flex)
Moco V2 dirancang ulang dari nol menggunakan prinsip perangkat lunak skala *Enterprise* untuk memastikan skalabilitas, integritas data, dan performa tinggi.

* **🏗️ Domain-Driven Design (DDD):** API kami dibangun dengan arsitektur DDD di atas ekosistem **Laravel 12**. Memisahkan *business logic* dari infrastruktur untuk *codebase* yang modular dan kebal terhadap perubahan.
* **🗄️ Strict & Optimized Database:** Menggunakan **PostgreSQL** dengan skema relasional tingkat lanjut. Semua transaksi dilindungi oleh *Foreign Key constraints* yang ketat, *Polymorphic relationships* yang dioptimalkan, dan indeksasi cerdas untuk *query* secepat kilat.
* **🧬 JIT (Just-In-Time) Legacy Migration:** Transisi mulus dari V1 ke V2 tanpa *downtime*. Kami menerapkan *Strangler Fig Pattern* untuk memigrasikan data *user* secara aman di latar belakang (*on-the-fly*) tepat saat mereka login.
* **⚡ Flutter + Shorebird OTA:** *Frontend mobile* Moco ditenagai oleh **Flutter** untuk performa *native* di Android & iOS. Pembaruan fitur dan *bug fixes* dikirim langsung ke perangkat pengguna menggunakan teknologi *Over-The-Air* (OTA) dari **Shorebird**—tanpa perlu menunggu *review* toko aplikasi.
* **🚀 FrankenPHP / Octane:** *API Server* kami berlari di atas *Application Server* berbasis *worker* untuk menekan latensi hingga ke hitungan milidetik.

---

## 📂 Our Repositories

| Repository | Tech Stack | Description |
| :--- | :--- | :--- |
| 🔒 `moco-api` | Laravel 12, PostgreSQL, FrankenPHP | Core backend service. Mengelola DDD engine, JIT Migration, dan background schedulers. |
| 📱 `moco-app` | Flutter, Bloc/Riverpod, Shorebird | Cross-platform mobile app dengan UI/UX modern dan OTA update support. |
| 🌐 `moco-landing` | Nuxt/Next.js, TailwindCSS | (Opsional) Landing page resmi dan portal edukasi finansial Moco. |

---

## 🤝 Join the Journey
Tertarik melihat bagaimana kami mendefinisikan ulang *personal finance* lewat *code* yang bersih? Intip repositori publik kami, baca dokumentasinya, dan mari berkolaborasi!

📧 **Contact the Team:** [email.organisasi@moco-app.web.id](mailto:email.organisasi@moco-app.web.id)
