# Getting Started with Create React App Test

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)




Perfect! You're using:

* **GitHub** (for code)
* **React.js** (so it’s a static SPA)
* **GoDaddy Hosting** (likely a shared hosting plan)

Now let’s walk through how to **host your React site** from GitHub on **GoDaddy Hosting** and point your domain to it.

---

## ✅ Step-by-Step: Host React Site on GoDaddy (Shared Hosting)

---

### 🔧 Step 1: Build Your React App

In your local project folder:

```bash
npm run build
```

This creates a `build/` folder with static HTML/CSS/JS files.

---

### 📁 Step 2: Upload to GoDaddy Hosting

Assuming you're using **GoDaddy’s cPanel hosting**:

1. Log in to [GoDaddy Account](https://www.godaddy.com/)
2. Go to **My Products** > Find your hosting > Click **Manage**
3. Open **cPanel** → Go to **File Manager**
4. Navigate to: `public_html` folder
5. **Delete existing files** (optional, if it's a new site)
6. Upload the contents of your `build/` folder (not the folder itself — just the files inside)

---

### 🌐 Step 3: Point Your Domain to Hosting (Should already be done)

If your domain and hosting are both with GoDaddy, this may be auto-linked. Just in case:

1. Go to GoDaddy Dashboard > **My Products**
2. Check your **domain is connected** to the correct hosting
3. Under **DNS**, ensure:

   * **A Record** points to your hosting IP address (GoDaddy sets this automatically)

---

### 🔁 Step 4: Optional – Connect GitHub to GoDaddy (Automation)

GoDaddy doesn’t directly auto-deploy from GitHub. If you want that:

1. Use **GitHub Actions** to auto-build and deploy via FTP
2. Or consider switching to **Netlify/Vercel** (auto-deploy + React-friendly)

Let me know if you'd like the **GitHub Actions → GoDaddy via FTP** setup.

---

### ✅ You’re Done!

Visit your domain: `https://yourdomain.com`
You should see your React site live 🎉

---

Want help automating deployments or setting up routing for React?
