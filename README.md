# bootstrap-scrollspy

[Bootstrap 4 Scrollspy (Advanced)](https://www.w3schools.com/bootstrap4/bootstrap_scrollspy.asp)  
[Bootstrap 滾動監聽(Scrollspy)](http://www.runoob.com/bootstrap4/bootstrap4-scrollspy.html)  

> 滾動監聽（Scrollspy）插件，即自動更新導航插件，會根據滾動條的位置自動更新對應的導航目標。其基本的實現是隨著您的滾動，基於滾動條的位置嚮導航欄添加 .active class。

`data-spy="scroll" data-target=".navbar"`   
`<nav class="navbar`  

# Deploy

`npm init`  package.json  
`npm i gulp  gulp-webserver -save-dev`  

package.json 
```json
"devDependencies": {
    "gulp": "^3.9.1",
    "gulp-webserver": "^0.9.1"
  }
```

`$ gulp` http://localhost:2015/  

`$git subtree push --prefix dist origin gh-pages`    
https://jacobhsu.github.io/bootstrap-scrollspy