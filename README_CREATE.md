# Build and Deploy a React Admin Dashboard App With Theming, Tables, Charts, Calendar, Kanban and More

Source: https://youtu.be/jx5hdo50a2M

## Steps
1. Run `npx create-react-app` on code directory
2. Delete all file under `src/` folder
3. Create `src\index.js`

```js
import React from 'react';
import ReactDOM from 'react-dom';

import App from './App';

ReactDOM.render(<App/>, document.getElementById('root'));
```

4. Create `scr\App.js`
5. On `App.js`, type `rafce` to create a React Arrow Function Component with ES7 module system
    - To enable the shortcutfunction `rafce`, install the extension ES7+ snippets

6. Install necessary dependencies (check package.json in this repository for a copy)
    - Run `npm install --legacy-peer-deps`
        - Command is to ensure to install only the right dependencies

7. Create `src\index.css` and `src\App.css` and use the same CSS from the files in this repository

8. Since [Tailwind CSS](https://tailwindcss.com/) will be used, ensure it was installed in the package.json
9. Create `tailwind.config.js` in root folder and copy teh contents of the same file in this repository
10. Create `craco.config.js` in root folder and copy teh contents of the same file in this repository

11. Import `index.css` in `index.js` by adding the following line:
```js
import './index.css';
```
12. Import `App.css` in `App.js` by adding the following line:
```js
import './App.css';
```

13. Test tailwind by editing App.js to return the following HTML:
```html
<h1 className='underline text-3xl'>App</h1>
```

This should be the end of the set-up and copying of code

