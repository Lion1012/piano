# Empaquetado web


- Tengo ofuscación.
- Tengo mimificacion.
- Tree shaking.
- Tengo preprocesadores de css. (scss)
- Tengo frameworks de css. (tailwind)
- Tengo frameworks de web. (react, vue)
- Uso de lenguajes que no sean javascript. (typescript, jsx)
- Tengo mecanismos de optimizacion del codigo.
- Servidor web de pruebas.
- Testing
- etc..

# Empaquetadores famosos.

- webpack
- rollup
- wmr
- parcel
- vite

# Pasos

## Crear un proyecto a partir de npm
npm init --yes

## Añadir la dependencia con tonejs
npm install tone

## Añadir el empaquetador parcel ( dependencia de desarollo )
npm install --save-dev parcel

## Construimos y arrancamos la aplicación.
npx parcel src/index.html

## Añadimos el framework react
npm install react react-dom

## Commitear a github
git init
git add .
git commit -m "first commit" 
git remote add origin https://github.com/Lion1012/piano.git
git push origin master