# webapp_V2.0-with-typescript-nodejs-express
Demo a webapp made with TypeScript and NodeJS, Express. Also experimenting authentication and authorization
Demo a webapp made by TypeScript and NodeJS, Express. No frontend yet, only backend.  
Also experimenting:  
- Authentication and authorization  
- passport - OAuth - JWT  

Using MySQL as database  

References:  
- ExpressJS :  
d
  
<br>  
////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////  
<br>  
  
## Command to set up environment:

Startup/Install commands:  
>`npm install express express-validator mysql2`  
>`npm install -D typescript ts-node nodemon @types/node @types/express`  
>  
>If the project already came with a `package.json` that has all dependencies, run `npm install` to automatically install all required modules  
><br>  
>`npm init -y`  
>`tsc --init`  
>`create 'nodemon.json' manually (optional, cũng có thể ghi thẳng câu lệnh trong phần "scripts" của package.json)`  

Commands to use during development:  

>`tsc -w`&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp;&nbsp;// Giám sát Giám sát sự thay đổi của các file trong folder, thay đổi thì tự động compile  
>`npm start`&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&nbsp;// Chạy script trong phần "start" ở package.json (trong trường hợp này là chạy nodemon)