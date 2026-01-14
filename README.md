### Purpose of Mintlify for Sans Paper
- Providing first hand updates for our customers regarding new features
- Source of documentation for fellow developers, complete with step by step guides

### Development

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


### Running Mintlify on your local as Developer

- Copy contents of mint_dev.json into mint.json
- Run the command `mintlify dev`

