## 1 Website Template<br>
 1 create amazona folder<br>
 2 create template folder<br>
 3 create index.html<br>
 4 add default html code<br>
 5 link to style.css<br>
 6 create header, main and footer<br>
 7 style elements<br><br>


## 2 Display Products<br>
  1 create products div<br>
  2 add product attributes<br>
  3 add link, image, name and price<br>

## 3 Create Node.js Server<br>
  1 Create Node.JS Server<br>
  2 run npm init in root folder<br>
  3 Update package.json set type: module<br>
  4 Add .js to imports<br>
  5 npm install express<br>
  6 create server.js<br>
  7 add start command as node backend/server.js<br>
  8 require express<br>
  9 create route for / return backend is ready.<br>
  10 move products.js from frontend to backend<br>
  11 create route for /api/products<br>
  12 return products<br>
  13 run npm start<br>
  14 install for backend automatic reload:- npm install --save-dev nodemon<br>
  15 Update package.json remove test inside script set "start": "nodemon --watch backend --exec node --experimental-modules backend/server.js"<br>
  16 run npm start to run backend api


## Load Products From Backend
1 edit HomeScreen.js<br>
2 define products, loading and error.<br>
3 create useEffect<br>
4 define async fetchData and call it<br>
5 install axios<br>
6 get data from /api/products<br>
7 show them in the list<br>
8 create Loading Component<br>
9 create Message Box Component<br>
10 use them in HomeScreen<br>

