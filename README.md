# Problem with vite dev in combination with `pnpm` and `@webcomponents/webcomponentsjs`
## Steps to reproduce
```
git clone https://github.com/franktopel/vite-vanilla-webcomponents
cd vite-vanilla-webcomponents
pnpm i
pnpm run dev
```
Open [http://localhost:3000/](http://localhost:3000/) in Firefox or Chrome on MacOS 11.4.
Open developer console. Find the errors described in https://github.com/vitejs/vite/issues/4115.