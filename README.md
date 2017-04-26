# coba-webpack
Meetup JakartaJs #29

[link slide](https://www.slideshare.net/sofianhw/webpack-75440321)

> git clone https://github.com/sofianhw/coba-webpack.git

> cd coba-webpack

> npm install

> npm start or npm run build

> python -m SimpleHTTPServer

1. branch satu
* Simpel webpack 2  
2. branch dua
* Contoh tentang Modules
3. branch tiga
* Contoh tentang Loader
4. branch empat
* Contoh Plugins
5. branch lima
* Contoh memisahkan CSS
6. branch enam
* Contoh code splitting

_setiap pindah branch jangan lupa npm install ulang siapa tau ada yang belum ke install_
  
> Another way to split our bundle is with System.import or require.ensure. By wrapping sections of code in these functions you create a chunk to be loaded on demand at run time. This can significantly improve load time performance by not sending everything to the client at the start. System.import takes the module name as an argument and returns a Promise. require.ensure takes a list of dependencies, a callback and an optional name for the chunk.
