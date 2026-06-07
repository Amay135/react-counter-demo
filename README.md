# react counter demo

Aplikasi sederhana React yang dibuat menggunakan Vite untuk mempelajari dasar-dasar React seperti komponen, state, event handling, dan Hot Module Replacement (HMR).

## Fitur

- Menggunakan React + Vite
- Counter interaktif dengan React Hooks (`useState`)
- Hot Module Replacement (HMR)
- Tampilan sederhana dan responsif
- Logo React dan Vite dengan animasi

## Teknologi

- React
- Vite
- JavaScript (ES6+)
- CSS

## Struktur Project

```
src/
├── assets/
│   └── react.svg
├── App.jsx
├── App.css
├── index.css
└── main.jsx
```

## Instalasi

Clone repository:

```bash
git clone https://github.com/username/react-vite-counter-app.git
```

Masuk ke folder project:

```bash
cd react-vite-counter-app
```

Install dependency:

```bash
npm install
```

Jalankan project:

```bash
npm run dev
```

Buka browser:

```text
http://localhost:5173
```

## Cara Kerja Counter

State counter dibuat menggunakan Hook `useState`:

```jsx
const [count, setCount] = useState(0);
```

Saat tombol diklik, nilai counter akan bertambah:

```jsx
<button onClick={() => setCount((count) => count + 1)}>
  count is {count}
</button>
```

## Screenshot

Tambahkan screenshot aplikasi di sini setelah project selesai.

## Tujuan Pembelajaran

Project ini dibuat untuk mempelajari:

- JSX
- Functional Component
- React Hooks (`useState`)
- Event Handling
- Styling dengan CSS
- Struktur project React menggunakan Vite

## License

MIT License
