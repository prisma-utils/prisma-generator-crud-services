# prisma-generator-crud-services

> This generator was bootstraped using [create-prisma-generator](https://github.com/YassinEldeeb/create-prisma-generator)

# Usage

Simply add a new generator to the `schema.prisma` file, like so:

```
generator crudservices {
  provider   = "node ../../node_modules/prisma-generator-crud-services"
  output     = "./../crud-services"
  stubFile   = "./../../stubs/crud.service.stub" // optional
  barrelFile = true // optional
}
```

and run `npx prisma generate`.
