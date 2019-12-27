## Description

Demo Repo to demonstrate the auto reload flow of VSCode while debugging node JS scripts.

## Usage

Run nodemon process via

```
  npm run debug
```

This opens a process which reruns the script on each file change. When the connected debugger is not 
canceling the connection, this will hang.


In Visual Studio code just set a break point in the `index.js` and run the `Debug and Watch` profile. 
This handles the start of nodemon and the reconnection automatically.