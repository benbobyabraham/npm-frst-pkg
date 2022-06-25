Here we have created a simple NPM package. Anyone can install it and use it.

Once you have published the package, you can refactor the code or add functionality. If you do this, change the version number in the package.json before Publishing.

It is also suggested that you add a README.MD, a markdown file, that gives a description and some examples of how to use your package.

### Publish

- **Export**

Use `module.exports` to export functions that are to be used from the package

```
module.exports = removeArrayDuplicates
```

- **Configure package.json**

Name must be unique in NPM registry.
Change any other information that is necessary.

- **Login to NPM registry**

```
npm login
```

- **Publish package***

```
npm publish
```

### Making Changes
If you need to make changes,

- Make the changes.
- Open the package.json and change the version number.
- Login to the NPM registry and run npm publish again.