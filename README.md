# Meteor Blaze Skeleton

Empty Meteor project with the Blaze client framework.

# How i created this project ?

1. Executed `meteor create --bare`
2. Removed meteor package `static-html`
3. Added meteor packages `blaze-html-templates` , `jquery` and `fourseven:scss`
4. Added npm package `jquery`
4. Executed npm package `meteor update`
5. Created the following file structure:

``` 
client/
  main.html
  main.js
  main.scss
both/
  main.js
server/
  main.js
```

6. Configured the entry points in the `package.json`

``` json
{
  ...
  "meteor": {
    "mainModule": {
      "client": "client/main.js",
      "server": "server/main.js"
    }
  }
}
```
