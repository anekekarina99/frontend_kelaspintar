# Kelas Pintar Web

## Library yang dipakai

- NextJS v13
- ReactJS v18
- Typescript v5
- ReduxJS Toolkit, Jotai
- RTK Query
- Mantine UI v6
- Jest, React Testing Library

## Cara menjalankan aplikasi

*Note: Karena menggunakan package manager baru, semua akan refer ke `bun`. Tapi script nya bisa diganti sesuai kebutuhan misal: `npm`*

### Install

`git clone` (HTTPS/SSH) dari GitLab dan:

```bash
cd kp-frontend
bun install
```

### Start development server

```bash
bun run dev # environment development
bun run staging # environment staging
bun run prod # environment production

## Akses Web Browser di:
http://localhost:1900
```

### Run ESLint

`bun run lint`

### Run Unit Testing

`bun run test`

### Build aplikasi

```bash
bun run build:nolint # skip linter, karena sudah pakai husky di setiap commit
bun run build:local # untuk tes build di local
```

### Start aplikasi hasil build

```bash
bun run start # start production server
bun run start:local # untuk tes start di local
```

=======================================================================

## Run Storybook

```bash
bun run storybook
# or
npm run storybook
# or
yarn storybook

##Web Browser
http://localhost:1997
```

## Important Links

[Guide development Kelas Pintar sisi Frontend - Onboarding FE Web.docx](https://extramarksid.sharepoint.com/:w:/r/sites/technology-Revamp-WebDeveloper/Shared%20Documents/Revamp%20-%20Web%20Developer/Onboarding%20FE%20Web.docx?d=w16bcbdb6630c416f88418271b058a0bf&csf=1&web=1&e=Yp34kG)