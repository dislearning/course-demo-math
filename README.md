## Serve course

```sh
npx http-server . -p 8001 -s --cors
```

## Consume course

Put this into url `/src/data/courses.js`:

```js
[
  ...
  'http://localhost:8001/course.json'
  ...
]
```

And start gatsby

```sh
gatsby develop
```