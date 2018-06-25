# Getting Start Next.js Project

### Init project
```
mkdir 01-hello-next.js
cd 01-hello-next.js
yarn init -y
yarn add react react-dom next --save
mkdir pages
```

### Add npm scripts in package.json
```
"scripts": {
  "dev": "next"
}
```

### Create .gitignore file
```
.next
node_modules
```

### Create pages/index.js file
```
class Index extends React.Component {
  render() {
    return (
      <div>Hello World!</div>
    )
  }
}

export default Index
```

### Start dev server
```
yarn dev
```

### Test URL
http://localhost:3000