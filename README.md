# Campus Canteen

## Rencana arsitektur

- React + TypeScript + Vite untuk aplikasi frontend.
- Tailwind CSS dan shadcn/ui untuk UI.
- React Router DOM untuk navigasi.
- Lucide React untuk ikon.
- Recharts untuk grafik bila diperlukan.
- React Hook Form + Zod untuk formulir dan validasi.
- `localStorage` sebagai satu-satunya penyimpanan. Tanpa backend, database, Firebase, atau Supabase.

## Struktur folder rencana

```text
kantin/
├── index.html
├── package.json
├── vite.config.ts
├── tsconfig*.json
├── components.json
├── postcss.config.js
├── tailwind.config.ts
└── src/
    ├── main.tsx
    ├── App.tsx
    ├── index.css
    ├── components/
    ├── pages/
    ├── lib/
    │   └── storage.ts
    ├── schemas/
    └── types/
```

Belum ada implementasi aplikasi atau dependency yang dibuat.
