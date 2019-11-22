# PHP Builder

Super small jenkins friendly php building and deploying docker image

```
pipeline {
    agent {
        docker { image "codayblue/php-builder" }
    }
}
```

## License MIT

See License file.