# Birdfeed API Schema
This repository holds a valid [Swagger 2.0](https://github.com/swagger-api/swagger-spec/blob/master/versions/2.0.md) schema.

![](http://online.swagger.io/validator?url=https://raw.githubusercontent.com/birdfeed/api-schema/master/swagger.json)

# Making edits
To make edits, it is probably easier to read and make changes to `swagger.yaml`. To generate a JSON file from the schema, as some of the `swagger-api` toolkit does not support YAML markup, just do the following...

```bash
bundle install
rake generate:json
```

`swagger.json` should automagically appear in the root of this repository. 

# Contributions
All contributions are welcome, please submit a pull request. 