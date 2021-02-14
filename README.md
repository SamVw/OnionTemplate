# OnionTemplate

This repository contains a ready to use .Net template with the Onion Architecture in mind.

> Most of the traditional architectures raise fundamental issues of tight coupling and separation of concerns. _Onion Architecture_ was introduced by Jeffrey Palermo to provide a better way to build applications in perspective of better testability, maintainability, and dependability. Onion Architecture addresses the challenges faced with 3-tier and n-tier architectures, and to provide a solution for common problems. Onion architecture layers interact to each other by using the Interfaces.

- [Tapas Pal](https://www.codeguru.com/csharp/csharp/cs_misc/designtechniques/understanding-onion-architecture.html#:~:text=Onion%20Architecture%20is%20comprised%20of,on%20the%20actual%20domain%20models.)

Link to blog: [Guide](https://jeffreypalermo.com/2008/07/the-onion-architecture-part-1/)

## Install

`cd ./OnionTemplate`

`dotnet new -i .`

## Use

Replace "CustomProject" with your own project name!

`mkdir CustomProject`

`cd ./CustomProject`

`dotnet new onionwebapi -n CustomProject`