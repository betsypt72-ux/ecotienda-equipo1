# Vatio: equipos que ahorran energía

Tienda en línea de equipos eficientes (HTML5, CSS, Bootstrap 5, Sass y JavaScript).

## Compilar los estilos
```
npm install
npx sass --no-source-map scss/estilos.scss css/estilos.css
```

## Subir a GitHub y publicar (cambie N por el número del equipo)
```
git init
git add .
git commit -m "Primera version de la tienda Vatio"
git branch -M main
git remote add origin https://github.com/USUARIO/ecotienda-equipoN.git
git push -u origin main
```
Luego en GitHub: Settings > Pages > Branch main, carpeta / (root). Para la entrega:
```
git tag ea2
git push origin ea2
```
