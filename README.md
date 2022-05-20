# awesome-starlette
About A curated list of awesome Starlette resources and extensions

[Docs](https://www.starlette.io/) | [Source](https://github.com/encode/starlette)


## Contents
- [Extensions](#extensions)
    - [Base](#base)
    - [Auth](#auth)
    - [Admin](#admin)
    - [WebSocket](#websocket)
    - [API](#api)
    - [Other](#other)
- [Projects](#projects)
    - [Boilerplate](#boilerplate)
- [Groups](#groups)


## Extensions

### Base
- [starlette-core](https://github.com/accent-starlette/starlette-core) - Basic functionality for every site. Includes database, flash messages, email, pagenation
- [Starsessions](https://github.com/alex-oleshkevich/starsessions) - An alternate session support implementation with customizable storage backends.
- [webargs-starlette](https://github.com/sloria/webargs-starlette) - Declarative request parsing and validation for Starlette, built on top of webargs.Allows you to parse querystring, JSON, form, headers, and cookies using type annotations.

### Auth
- [starlette-auth](https://github.com/accent-starlette/starlette-auth) - provides a SQLAlchemy backend for user authentication within starlette.
- [Authlib](https://github.com/lepture/Authlib) - The ultimate Python library in building OAuth and OpenID Connect clients and servers. Check out how to integrate with Starlette.
- [Imia](https://github.com/alex-oleshkevich/imia) - An authentication framework for Starlette with pluggable authenticators and login/logout flow.
- [Starlette-Login](https://github.com/jockerz/Starlette-Login) - User session management for Starlette. Very much inspired by [Flask-Login](https://github.com/maxcountryman/flask-login)
 
### Admin
- [starlette-admin](https://github.com/accent-starlette/starlette-admin) - Simple, easy to manage admin site for crud operations. Includes all templates required for starlette-auth styled in this theme.

### WebSocket
- [ChannelBox](https://github.com/Sobolev5/channel-box) - Another solution for websocket broadcast. Send messages to channel groups from any part of your code. Checkout MySimpleChat, a simple chat application built using channel-box and starlette.
- [Nejma](https://github.com/taoufik07/nejma) - Manage and send messages to groups of channels using websockets. Checkout nejma-chat, a simple chat application built using nejma and starlette.

### API
- [SpecTree](https://github.com/0b01001001/spectree) - Generate OpenAPI spec document and validate request & response with Python annotations. Less boilerplate code(no need for YAML).
- [Starlette APISpec](https://github.com/Woile/starlette-apispec) - Simple APISpec integration for Starlette. Document your REST API built with Starlette by declaring OpenAPI (Swagger) schemas in YAML format in your endpoint's docstrings.
- [Starlette OAuth2 API](https://gitlab.com/jorgecarleitao/starlette-oauth2-api) - A starlette middleware to add authentication and authorization through JWTs. It relies solely on an auth provider to issue access and/or id tokens to clients.

### Other
- [starlette-docker](https://github.com/accent-starlette/starlette-docker) - Base images for starlette.Base images for starlette.
- [starlette-files](https://github.com/accent-starlette/starlette-files) - Save files using s3 or fs, includes ability to crop, resize, reformat images etc
- [Mangum](https://github.com/erm/mangum) - Serverless ASGI adapter for AWS Lambda & API Gateway.
- [Scout APM](https://github.com/scoutapp/scout_apm_python) - An APM (Application Performance Monitoring) solution that can instrument your application to find performance bottlenecks.
- [Starlette Context](https://github.com/tomwojcik/starlette-context) - Middleware for Starlette that allows you to store and access the context data of a request. Can be used with logging so logs automatically use request headers such as x-request-id or x-correlation-id.
- [Starlette Cramjam](https://github.com/developmentseed/starlette-cramjam) - A Starlette middleware that allows brotli, gzip and deflate compression algorithm with a minimal requirements.
- [Starlette Prometheus](https://github.com/perdy/starlette-prometheus) - A plugin for providing an endpoint that exposes Prometheus metrics based on its official python client.
- [Starlette WTF](https://github.com/muicss/starlette-wtf) - A simple tool for integrating Starlette and WTForms. It is modeled on the excellent Flask-WTF library.

## Projects
### Boilerplate
- [boilerplate](https://github.com/accent-starlette/boilerplate) - Empty boilerplate project for Starlette with docker, auth, css and more.

## Groups
### 中文交流群
- [starlette中文小组] - 加v DeepRedTech拉群
