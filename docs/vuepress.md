# Vuepress 로 TIL 만들기
## VuePress 란?

## VuePress 시작하기
```
# package.json
yarn init

# Install VuePress locally
yarn add -D vuepress

# Create first document
mkdir docs && echo '# Hello VuePress' > docs/README.md

# Serve the documentation site in the local server
```

## Deploying
### netlify
```
Repository : github.com/javapark/TIL
Base directory : Not set
Build command : vuepress build docs
Publish directory : docs/.vuepress/dist
Builds : Active
```

# TIL 접속
https://javapark-til.netlify.app

# Ref
- [Vuepress 로 기술문서 빠르게 만들어보자](https://limdongjin.github.io/vuejs/vuepress/#table-of-contents)
- [VuePress Getting Started](https://vuepress.vuejs.org/guide/getting-started.html#manual-installation)
- [VuePress Deploying](https://vuepress.vuejs.org/guide/deploy.html)