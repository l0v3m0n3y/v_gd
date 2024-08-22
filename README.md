# v_gd
JavaScript library for v.gd
# main
```js
async function main(){
    const {v_gd} = require('./v_gd');
    const url= new v_gd();
    let req=await url.short_url("url")
    console.log(req)
}
main()
```
