---
home: true
actionText: Hello VuePress →
actionLink: /docs/
features:
- title: Feature title
  details: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean pulvinar ligula magna, ut suscipit orci tempus nec. Sed dignissim lacus sapien, vel rhoncus est mollis pulvinar. Nunc aliquet varius .
- title: Feature
  details: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean pulvinar ligula magna, ut suscipit orci tempus nec. Sed dignissim lacus sapien, vel rhoncus est mollis pulvinar. Nunc aliquet varius.

footer: MIT Licensed | <Org> Copyright © 2018-present <Name>
---

# VuePress Site & Netlify deploy

```bash
git clone git@github.com:zavolokas/vueblog-template.git template
mkdir myblog
cd myblog
git init
```

Go to template folder and copy the content to the myblog (except `.git` folder).

Then create a new repo for your blog on GitHub.

Commit and push the content of myblog.

```bash
git add -A
git commit -m "initial commit"
git remote add origin <your repo address>
git push -u origin master
```

After that go to [Netlify](http://netlify.com) and login with your GitHub accout.

Click **New site from Git**

Choose GitHub

Choose your repo for myblog

Click **Deploy site**

## Local Development

To try it out locally, clone this repo and generate a static site.

```bash{3}
cd myblog
npm install

To start a local server execute
```bash{3}
npm run dev
```

Or to generate site
```bash{3}
npm run build 
```

For more information, see [VuePress Docs](https://vuepress.vuejs.org)
