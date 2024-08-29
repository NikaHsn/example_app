# example_app
this is a minimal full-stack application with express

### To install the app dependencies, run:
```shell
example_app% npm i
```
if facing any issue delete the package-lock.json and run `npm i`

### To start the app locally, run:
```shell
example_app% npm run dev
```
### To start the app locally on an specified port, run:
```shell
example_app% PORT=3000 npm run dev
```
Then open your browser and go to `http://localhost:3000/exampleapp`
To See the SPA version of the application navigate to `http://localhost:3000/exampleapp/spa`

### If need to check for a process running on a specific port ex. port 3000
```shell
%lsof -i:3000
%kill -9 PID