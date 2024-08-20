# Why using YAML instead of JSON

It offer feature like `comments` and it is more "readable" because there is less "delimiter" chars (`"`, `{`, `}`, `[`, `]`, etc)

# Build the schema from the YAML

Use `yq` to convert the `.yaml` info `.json`

`yq -o j -P src/Gedcomx.schema.yaml > Gedcomx.schema.json`

More about `yq` :
- Install : <https://github.com/mikefarah/yq/#install>
- Docs : <https://mikefarah.gitbook.io/yq>
- Encoding json : <https://mikefarah.gitbook.io/yq/usage/convert#encode-json-simple>