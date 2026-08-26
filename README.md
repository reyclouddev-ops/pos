# 🚀 POS — ReyCloud

Website dashboard dan management platform berbasis web untuk kebutuhan ReyCloud.

## 🌐 Demo

https://pos.legionteknologi.my.id

## 🔗 Base URL API

https://api.legionteknologi.my.id

Seluruh fitur yang membutuhkan backend atau API menggunakan satu baseUrl:

const baseUrl = "https://api.legionteknologi.my.id";

## 📦 Repository

https://github.com/reyclouddev-ops/pos

## ✨ Features

- 🏠 Dashboard
- 💬 Chat
- 🖥️ CPanel
- ⚙️ CAdmin
- 🚀 Deploy
- 🛒 Marketplace
- 👤 Profile
- 📊 Status
- 📤 Upload
- 🔌 API Integration
- 📱 Responsive Interface

## 📁 Project Structure

pos/
├── README.md
├── index.html
├── dashboard.html
├── chat.html
├── cpanel.html
├── cadmin.html
├── deploy.html
├── marketplace.html
├── profile.html
├── status.html
└── upload.html

## 🖥️ Pages

### 🏠 Dashboard

Halaman utama untuk mengakses berbagai fitur dan informasi platform.

### 💬 Chat

Halaman komunikasi dan chat pengguna.

### 🖥️ CPanel

Halaman management panel dan layanan hosting.

### ⚙️ CAdmin

Halaman administrasi dan management sistem.

### 🚀 Deploy

Halaman untuk kebutuhan deployment project.

### 🛒 Marketplace

Halaman marketplace untuk produk dan layanan.

### 👤 Profile

Halaman profile pengguna.

### 📊 Status

Halaman monitoring status layanan.

### 📤 Upload

Halaman upload file melalui API.

## 🔌 API

Semua fitur backend menggunakan satu alamat API utama.

const baseUrl = "https://api.legionteknologi.my.id";

Contoh request:

fetch(`${baseUrl}/endpoint`)
    .then(response => response.json())
    .then(data => console.log(data));

## 📤 Upload API

Contoh penggunaan API upload:

const formData = new FormData();

formData.append("file", file);

const response = await fetch(
    `${baseUrl}/upload`,
    {
        method: "POST",
        body: formData
    }
);

const result = await response.json();

console.log(result);

## ⚙️ API Configuration

Jika alamat API berubah, cukup ubah nilai baseUrl:

const baseUrl = "https://api.legionteknologi.my.id";

Seluruh request API dapat menggunakan variable tersebut.

Contoh:

const baseUrl = "https://api.legionteknologi.my.id";

async function request(endpoint, options = {}) {
    const response = await fetch(
        `${baseUrl}${endpoint}`,
        options
    );

    return response.json();
}

Penggunaan:

const data = await request("/endpoint");

console.log(data);

## 🚀 Deployment

Project dapat digunakan pada hosting static seperti Vercel.

### Deploy

1. Fork repository.
2. Import repository ke Vercel.
3. Pilih repository `pos`.
4. Deploy project.
5. Hubungkan custom domain.
6. Gunakan domain:

https://pos.legionteknologi.my.id

## 💻 Local Development

Clone repository:

git clone https://github.com/reyclouddev-ops/pos.git

Masuk ke folder:

cd pos

Jalankan web server lokal:

python3 -m http.server 8080

Kemudian buka:

http://localhost:8080

## 🛠️ Technologies

Project menggunakan:

- HTML
- CSS
- JavaScript
- REST API
- Fetch API
- Web API

## 📱 Responsive

Interface dirancang agar dapat digunakan pada:

- 📱 Smartphone
- 📱 Tablet
- 💻 Laptop
- 🖥️ Desktop

## 🔗 Links

### 🌐 Website

https://pos.legionteknologi.my.id

### 🔌 API

https://api.legionteknologi.my.id

### 📦 Repository

https://github.com/reyclouddev-ops/pos

### 👨‍💻 GitHub

https://github.com/reyclouddev-ops

## 👨‍💻 Developer

ReyCloud

Project: POS

GitHub:

https://github.com/reyclouddev-ops

## 📄 License

Project ini dibuat untuk kebutuhan pengembangan dan penggunaan ReyCloud.

© ReyCloud
