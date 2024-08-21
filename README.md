# sweetalert2-sveltekit-typescript-issue-demo
a minimal reproduction repo for an issue with sweetalert in combination with sveltekit using typescript.

## ⚠️ this is resolved: checkout https://github.com/sweetalert2/sweetalert2/issues/2752#issuecomment-2302129790

## how to run?

### clone
```
git glone git@github.com:lukas-runge/sweetalert2-sveltekit-typescript-issue-demo.git
```

### install dependencies
```
yarn install
```

### checkout demo for missing types
```
git checkout missing-type-demo
```

&rarr; see error in Line 5 of src/routes/+page.svelte: `Could not find a declaration file for module 'sweetalert2/dist/sweetalert2.js'. '[..]/node_modules/sweetalert2/dist/sweetalert2.js' implicitly has an 'any' type.`

### checkout demo for missing theme
```
git checkout missing-theme-demo
```

### run demo app
```
yarn dev
```

&rarr; see the dark theme not being applied
