# codewind-templates
Central repository for storing list of supported code templates for use in codewind

# /devfiles/index.json
This file is generated and MUST NOT be manually edited. 

1. Run [build.sh](https://github.com/codewind-resources/codewind-templates/blob/master/build.sh) to build the dockerfile.
2. Run the dockerfile mounting a local directory
```sh
docker run -v /myDirectory/codewind-templates/devfiles:/build/devfiles/ codewind-resources/codewind-templates