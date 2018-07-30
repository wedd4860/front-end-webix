## 개인용으로 사용

라이브러리 URL
* webix : http://www.webix.com/

## pivot

- [1.0](#1.0) <a name='1.0'></a> 샘플 구조

  ```js
  var grida = { 
    view:"datatable",
    columns:[
      { id:"title", header:"Film title", width:250 },
      { id:"year", header:"Release year", width:80 },
      { id:"votes", header:"Votes", width:100 }
    ],
    autoheight:true,
    autowidth:true,
    data:[
      { id:1, title:"The Shawshank Redemption", year:1994, votes:678790},
      { id:2, title:"The Godfather", year:1972, votes:511495} 
    ]
  };
    
  webix.ready(function(){  
    webix.ui(grida);
  });
  ```