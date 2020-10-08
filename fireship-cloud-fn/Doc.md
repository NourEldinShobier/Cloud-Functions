# 1) Setup

```
1- npm install firebase-tools -g
2- firebase login
3- create project folder
4- firebase init
5- cd functions
```

### Notes

```json
"engines": {
    "node": "12"
},
```

# 2) Deployment

```powershell
firebase deploy --only functions
firebase deploy --only functions:your-function-name
```


