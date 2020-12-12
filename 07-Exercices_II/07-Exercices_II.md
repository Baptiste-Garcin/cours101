## Exercices

### Get all coordinates in an object
example

`{ userName: [] }`

### Get all posts of user
example

`{ userName: [{ posts }, ...], }`

### Get all posts by user with comments
```javascript
{
  userName: [{
    ...posts,
    comments: [],
  },
  {
    ...etc
  }]
}
```
