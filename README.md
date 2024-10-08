# Node Js + Gulp
### Summering:
* Demonstration av NodeJs och Gulp. Syftet med automatiseringen är att minska inladdningstiden och för att lättare kunna navigera när man ska göra ändringar i källkoden.
* Använda paket i projektet är: Gulp, gulp-browsersync, gulp-clean-css, gulp-concat, gulp-uglify, gulp-image.
### Testa koden
Man kan starta upp webbplatsen genom att köra gulp från terminalen lokalt. När man gör det så skapas en publik mapp med kopia av källkodens index.html, js-filer i källkoden slås ihop och minimeras och läggs in i publika mappen, css-filer slås ihop och en minimerad version läggs in i publika mappen och bilder från src-mappen komprimeras och läggs in i den publika mappen. Ändras dessa nämnda filer så uppdateras de i den publika mappen. Resultatet av den publika mappen kan ses i webbfönstret, då detta vid start av gulp öppnas på localhost med livereload.
