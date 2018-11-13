# angular-service-worker-demo
Running through the angular service worker documentation and understanding how it works.

Steps to create new angular app with service worker

1) npm install -g @angular/cli@latest
2) ng new [project-name]
 -> this allows specify type of CSS files and whether include routing module
3) cd [project-name]
4) ng add @angular/pwa --project [project-name]

then we can build and test using http-server
5) npm install http-server
6) ng build --prod
7) http-server -p 8080 -c-1 dist/[project-name]