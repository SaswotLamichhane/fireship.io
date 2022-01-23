

First, install [Hugo](https://gohugo.io/getting-started/installing/).

```shell
git clone <fireship-repo>

npm install

npm run dev
```

Visit `localhost:1313` and you should be live. You do not need the web components for general content development, but they can be built with:

```shell
cd components && npm install
npm run build
```


## Contribute a Post

Read the [style guide](https://fireship.io/style-guide/) for some tips before contributing. 

```shell
cd hugo
hugo new -k bundle lessons/angularfire-google-oauth
hugo new snippets/my-cool-snippet.md
```

## Web Component Development

Interactive features are built with Angular Elements web components in `components/`


### Add Your Bio

First time? Add your bio and social links to `content/contributors`. 
