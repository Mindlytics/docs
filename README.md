# Mindlytics Developer Documentation 

This is a [Mintlify](https://mintlify.com) based project.

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview the documentation changes locally. To install, use the following command

```sh
npm i -g mint
```

Run the following command at the root of your documentation (where docs.json is)

```sh
mint dev
```

## OpenAPI Specification 

Part of this development documentation includes an OpenAPI "live" sandbox for some of the Mindlytics service endpoints.  For this to work, the "./openapi.json" file must exist at the top of this repository.  If the production endpoints change for some reason, you can regenerate this file:

```sh
curl https://app.mindlytics.ai/openapi.json -o openapi.json
```
