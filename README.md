# Bike Route

### Getting Started

Download https://data.lacity.org/A-Safe-City/Crime-Data-from-2010-to-Present/y8tr-7khq.

In `dataExtractor.js`, edit the `file` variable to point to where that file is and what the file is called:

```js
const file = "./Crime_Data_from_2010_to_Present.csv";
```

```
$ npm install
$ node dataExtractor.js
```

Open 2 terminals. One for hosting the index.html and the other for the python server.
For the python server:

```
$ export FLASK_APP=server.py
$ python -m flask run
```
