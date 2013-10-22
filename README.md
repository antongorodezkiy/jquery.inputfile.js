jquery.inputfile.js
==================

Small jquery library used to replace the input type file elements with some regular elements so you can change its style.

```javascript
$('input[type="file"]').inputfile({
    uploadText: '<span class="glyphicon glyphicon-upload"></span> Select a file',
    removeText: '<span class="glyphicon glyphicon-trash"></span>',
    restoreText: '<span class="glyphicon glyphicon-remove"></span>',
      
    uploadButtonClass: 'btn btn-primary',
    removeButtonClass: 'btn btn-default',
    
    removeName: '',
    removeValue: 1,
        
    dontRemove: false
});
```
The complete list of parameters

Key |  Description
--- | ---
uploadText | 
removeText | 
