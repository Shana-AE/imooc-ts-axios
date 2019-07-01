# imooc-ts-axios

imooc typescript refactored axios

project of Imooc Lesson *Typescript Refactored Axios*

## Requirements

- Use `XMLHttpRequest` object to communicate in browser
- Support `Promise` API
- Support interceptor of request and response
- Support data transform of request and response
- Support cancellation of the request
- auto-transformation of JSON data.
- client XSRF-prevented.

Node side axios is not included.

project use [typescript-library-starter](https://github.com/alexjoverm/typescript-library-starter), but there are lots of vulnerability, so I change the `npm` to `yarn`, and remove `travis-deploy-once` since it's deprecated. I don't know how it will have influence on this project. but I preferred to try it out.
