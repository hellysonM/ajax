# SIMPLE AJAX VANILLA JS LIBRARY - POST AND GET 


### OPTIONS

```
ajax.request({
  type: "GET",
  data: {},
  sucess:(data)=>{
    alert(data)
  } 
});
```
#### GET METHOD
```
ajax.get('URL',function sucess(data){},function beforeSend(){})
```
#### POST METHOD
```
ajax.post('URL',data,function sucess(data){},function beforeSend(){})
```
