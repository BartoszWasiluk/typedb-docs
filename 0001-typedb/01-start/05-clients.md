---
pageTitle: TypeDB Clients
keywords: typedb, console, studio, client, api, 
longTailKeywords: typedb client api, typedb api, client api, typedb studio, typedb console
Summary: All you need to know about the architecture of a TypeDB Client.
toc: false
---

A TypeDB Client is meant to be used at the application layer for the purpose of managing and performing operations over 
databases on the TypeDB server. Client uses `gRPC` to interact with the TypeDB server and provides a more user-friendly interface: API, GUI or CLI.

Here is a list of existing TypeDB Clients:

- [TypeDB Console](../02-console/01-console.md)
- [TypeDB Studio](../07-studio/00-overview.md)
- [TypeDB drivers](../03-client-api/00-overview.md)
  - Native drivers
    - [**Java**](../03-client-api/01-java.md)
    - [**Node.js**](../03-client-api/03-nodejs.md)
    - [**Python**](../03-client-api/02-python.md)
  - [Community drivers](../03-client-api/04-other-languages.md)

If you can't find a suitable client, consider [creating a new client](../03-client-api/05-new-client.md).