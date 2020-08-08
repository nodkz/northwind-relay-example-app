# OUTDATED

If somebody somebody wants take care about this demo - please open an issue. And I'll grant your permissions. Thanks.

## Northwind demo app (on Relay Modern)

> This is a true story. The events depicted took place in Northwind in 1996-1998. At the request of the survivors, the names have been changed. Out of respect for the dead, the rest has been told exactly as it occurred.
> **©Fargo**

This is application shown Component-Based approach on full power 💪💪💪.

Build using React, Relay Modern, GraphQL, React Router 4.

[Live DEMO](https://nodkz.github.io/relay-northwind/)

[Live GraphQL server DEMO](http://graphql-compose.herokuapp.com/northwind/)

Internally implements many cool things:
- Connections with infinite lists and filtering
- Running Relay queries from component (not via routing)
- Display loaders when fetching data
- Build on top of [graphql-compose](https://github.com/nodkz/graphql-compose) auto-generated GraphQL schema from mongoose (MongoDB).
- Eslint with GraphQL fragment validation, Webpack 3, Babel 7.
- Static analysis with Flowtype
- Many thanks to @taion for `react-bootstrap`

![relay-northwind-app](https://cloud.githubusercontent.com/assets/1946920/18013918/488e6830-6be2-11e6-84b6-884c8ab971ac.gif)

### Data models
This APP has 8 basic types, which has many cross-relations (via one-to-one, arrays, connections):
- category
- customer
- employee
- order
- product
- region
- shipper
- supplier

### Previous Relay versions
Working example on **Relay Classic** can be found in [classic branch](https://github.com/nodkz/relay-northwind-app/tree/classic), **Relay Compat** in [compat branch](https://github.com/nodkz/relay-northwind-app/tree/compat).


### About server-side (GraphQL + MongoDB)
[GraphQL server source code](https://github.com/nodkz/graphql-compose-examples/tree/master/examples/northwind) (graphql-compose inside). Also you may find all data in JSON and CSV formats for your needs.


### Thanks to
- [@shayden](https://github.com/shayden) for the csv dump.
- [@tmcnab](https://github.com/tmcnab/northwind-mongo) that converted it to MongoDB.
- [@leisenstein](https://github.com/leisenstein/northwind-mongo) that clean up a CSV data.

### License
MIT
