# README #

** Install **

    npm install git+ssh://git@bitbucket.org:teraficswagger/swagger-editor.git --save

#swagger-editor
swagger-editor

**Example**  
```javascript
    var editor = require("swagger-editor");
```

##swagger-editor.edit(swaggerFile)
opens the browser and enables live edit of the swagger api file

**Params**

- swaggerFile `string` - the path to the swagger api file  

**Example**  
```javascript
    editor.edit(swaggerFile);
```