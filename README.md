# firebase-samples
Firebase samples

## Firebase Hosting

### Configure custom domain
- Create a project in Firebase console
- Install firebase tools 

  ```
  $ npm install -g firebase-tools
  ```
  
- Firebase tools commands

  ```
    firebase login
    firebase init
    firebase deploy
  ```
- Selected the option " connect domain "

- Added register type TXT to Domain manager

- Added register type A to Domain manager

- Configure domain with WWW . Example "www.gdglima.com" an then selected "redirect to gdglima.com"

- Added register type A

### Create the first website

- Start Firebase Tool
- Run the commands

```
  firebase init
  firebase serve //local server
  firebase deploy
```
- Open it in browser

```
  http://localhost:5000/
```

References

- https://firebase.google.com/docs/hosting/quickstart?hl=es-419
