git init# Code Citations

## License: unknown
https://github.com/gayatrikawade/learn-demo-app/tree/330834874a533d44bbbf8e8e3cb31ca8ba91b76f/server/services/FIleUploadService.js

```
({
     destination: function (req, file, cb) {
       cb(null, 'uploads/');
     },
     filename: function (req, file, cb) {
       cb(null, Date.now() + path.extname(file.originalname))
```


## License: unknown
https://github.com/Sapoconchus/intro_node/tree/5f24276d84fcb3df25bba3f41801b17b6be77f4c/routes/api/ads.js

```
/');
     },
     filename: function (req, file, cb) {
       cb(null, Date.now() + path.extname(file.originalname));
     }
   });

   const upload = multer({ storage: storage });

   //
```

