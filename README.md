# [10270](https://github.com/prisma/prisma/issues/10270)

This repository contains the reproduction code for: https://github.com/prisma/prisma/issues/10270

## Usage

```
$ npm install
...

$ npx prisma generate
Environment variables loaded from .env
Prisma schema loaded from prisma\schema.prisma

> testing@ generator D:\testing\prisma
> bad-ts-node src

$ echo $LASTEXITCODE
0
```
