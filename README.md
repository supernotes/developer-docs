# Supernotes Developer Documentation 

The developer documentation for Supernotes. If you notice any problems, please open an issue or submit a pull request.

### Installation 

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify) to preview the documentation changes locally. To install, use the following command

```
npm i -g mintlify
```

Run the following command at the root of your documentation (where mint.json is)

```
mintlify dev
```

#### Troubleshooting

- Mintlify dev isn't running - Run `mintlify install` it'll re-install dependencies.
- Page loads as a 404 - Make sure you are running in a folder with `mint.json`
- Images up to 5MB are supported, otherwise please link to images hosted on S3 or another service.
