# NEXT JS COURSE

Course for the popular ReactJS Framework. NextJS.
You can find more information and documentation about NextJS here

## Essential Links.
📌 [NExt JS Official Website](https://nextjs.org/)

📌 [Next JS Official Documentation](https://nextjs.org/docs)

📌 [ReactJS Docs](https://reactjs.org/docs/getting-started.html)

📌 [Git Docs](https://git-scm.com/doc)

## Requirements.

- Node > 10
- npm
- git
- React JS basic knowledge
- Terminal very basic usage
- A code editor like VSCode, IntelliJ etc.

## 01. Next JS Setup.

Create a folder and Use the JS package manager [npm](https://www.npmjs.com/get-npm) to install Next JS and react libs.

### 01. Init the project and install required libraries.

To initialize a npm project let's create an empty directory and run `npm init`

```bash
mkdir nextjs
npm init -y
```

Only 3 libs required by next. `next` library itself and `react` + `react-dom` libraries for using react

You can install them with these commands in your terminal.

```bash
npm install --save react react-dom next
# -> npm i -G react react-dom next (also works if you're a cool guy)
```

If you open the project in your editor you will see a package.json file like this:

```json
{
  "name": "nextjs",
  "version": "1.0.0",
  "main": "index.js",
  "scripts": {},
  "dependencies": {
    "next": "^10.1.3",
    "react": "^17.0.2",
    "react-dom": "^17.0.2"
  }
}
```

### 02. Add the Next JS scripts

Override the default package.json `scripts` object with this.

```json
  "scripts": {
     "dev": "next dev"
  }
```

The `dev` Script just runs a development environment.

### 03. Create a basic "Hello Next JS" page

Enter in your editor and create a `pages` folder with a file index.js on it.

`pages/index.js`
```jsx
const Index = () => {
	return <h1>Hello Next JS!</h1>
}

export default Index
```

### 04. Start the development env

Just run this in your terminal
```bash
npm run dev
```

Open this URL: `http://localhost:3000/`

You should see: **Hello Next JS!** in the screen.


## License
[MIT](https://choosealicense.com/licenses/mit/)