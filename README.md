# ru.hqcdn.target



https://stackoverflow.com/questions/21741841/detecting-ios-android-operating-system


// Huawei Phone must come first because its UA also contains "Android"
    if (userAgent.includes("HUAWEI")) {
    
    
    


function getPlatform() {
   var platform = ["Win32", "Android", "iOS"];

   for (var i = 0; i < platform.length; i++) {

       if (navigator.platform.indexOf(platform[i]) >- 1) {

           return platform[i];
       }
   }
}

getPlatform();