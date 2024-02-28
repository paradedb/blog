# ParadeDB Blog

The ParadeDB [blog](https://blog.paradedb.com) is built using [Mintlify](https://mintlify.com/docs/quickstart).

## 👩‍💻 Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify) to preview
the blog changes locally. To install, use the following command:

```bash
npm i -g mintlify
```

Run the following command at the root of the blog (where `mint.json` is):

```bash
mintlify dev
```

## 😎 Publishing Changes

Changes will be deployed to production automatically after pushing to the default
branch.

You can also preview changes using PRs, which generates a preview link of the blog.

## Troubleshooting

- Mintlify dev isn't running - Run `mintlify install` it'll re-install dependencies.
- Page loads as a 404 - Make sure you are running in a folder with `mint.json`
