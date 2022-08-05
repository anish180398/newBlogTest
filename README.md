# gatsby-starter-hygraph-blog

> A [Gatsby](httsp://gatsbyjs.com) starter for creating a basic blog with [Hygraph](https://hygraph.com)

• [Demo](blog.withheadlesscms.com) • [`gatsby-source-hygraph`](https://github.com/Hygraph/gatsby-source-hygraph)

[![Clone project](https://hygraph.com/button)](https://app.graphcms.com/clone/a1cd264ab6d3448d9b4d1e2cc2162620?name=Blog)
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FGraphCMS%2Fgatsby-starter-graphcms-blog&env=GRAPHCMS_ENDPOINT,GRAPHCMS_TOKEN&envDescription=GraphCMS%20API%20Endpoint%20and%20Token&envLink=https%3A%2F%2Fgithub.com%2FGraphCMS%2Fgatsby-starter-graphcms-blog%23quick-start&project-name=graphcms-blog&repo-name=graphcms-blog&demo-title=GraphCMS%20Blog&demo-description=Gatsby%20starter%20for%20creating%20a%20basic%20blog%20with%20GraphCMS&demo-url=https%3A%2F%2Fblog.withheadlesscms.com%2F&demo-image=https%3A%2F%2Frepository-images.githubusercontent.com%2F283171327%2F1dc64780-e3de-11ea-9661-8f89688dc13c)

## Quick start

1. **Create a new Gatsby project via the [Gatsby CLI](https://www.npmjs.com/package/gatsby-cli)**

```shell
gatsby new hygraph-blog https://github.com/Hygraph/gatsby-starter-hygraph-blog
```

2. **Provide your Hygraph project keys**

> In order to use this starter, you'll need to have created a new Hygraph project using our `Blog Template`.

Navigate into your new site’s directory and copy the `.env.sample` file.

```shell
cd hygraph-blog
cp .env.sample .env
```

Inside of your newly created `.env` file, provide values for each variable. These variables can be found in the [project settings UI](https://hygraph.com/docs/guides/concepts/apis#working-with-apis).

```env
HYGRAPH_ENDPOINT=""
HYGRAPH_TOKEN=""
```

3. **Start building!**

Install the dependencies and start the gatsby dev server:

```shell
yarn
yarn dev
```

## Features

- Use [`gatsby-image`](https://www.gatsbyjs.org/packages/gatsby-image) with your Hygraph image assets.
- MDX support via [`gatsby-plugin-mdx`](https://www.gatsbyjs.org/packages/gatsby-plugin-mdx) on Hygraph `RichText` fields.
- Built with [Tailwind CSS](https://tailwindcss.com/).
