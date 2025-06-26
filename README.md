# curso_angular_16  
#### Clase 1  
npm install -g typescript
npm install -g @angular/cli@16
ng new repository-ng  
ng serve  
ng negerate help
ng g module auth --dry-run # nos devuelve que va hacer   
ng g module auth --routing --dry-run # nos crea un enrutador mas  
ng g component login --dry-run # genera un componente login  
ng g component auth/pages/login --dry-run --skip-tests # genera todos los archivos menos el archivo de pruevas (test)  
ng g component auth/pages/login --dry-run --inline-style # genera todos los archivos menos el de estilo y lo pone en el archivo en linea  
ng g component auth/pages/login --dry-run --inline-template # genera todos los archivos menos el de html y lo pone en el archivo en linea  
ng g component auth/pages/login --dry-run --skip-tests --inline-style