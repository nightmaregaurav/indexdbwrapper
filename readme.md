# IndexDBWrapper
[![npm version](https://badge.fury.io/js/@nightmaregaurav%2Findexdbwrapper.svg)](https://badge.fury.io/js/@nightmaregaurav%2Findexdbwrapper)
[![HitCount](https://hits.dwyl.com/nightmaregaurav/indexdbwrapper.svg?style=flat)](http://hits.dwyl.com/nightmaregaurav/indexdbwrapper)<br>
[![NPM](https://nodei.co/npm/@nightmaregaurav/indexdbwrapper.png?mini=true)](https://nodei.co/npm/@nightmaregaurav/indexdbwrapper/)
***

## Description
IndexDBWrapper is a library that allows you to interact with the IndexedDB API. It is not an ORM. It only provides simple CRD methods to interact with the IndexedDB API.

## Installation
```bash
npm install @nightmaregaurav/indexdbwrapper
```

## Usage

### Creating a Database
```typescript
import {IndexDBWrapper} from "@nightmaregaurav/indexdbwrapper";

const db = new IndexDBWrapper("test_database", 1);
```

### Store a Value
```typescript
    await db.Set("key", {prop1: 1, prop2: "2", prop3: new Date()});
```

### Retrieve a Value
```typescript
    const value = await db.Get("key");
    console.log(value);
```

### Delete a Value
```typescript
    await db.Delete("key");
```

## How to Contribute
* Fork the repository
* Clone the forked repository
* Make changes
* Commit and push the changes
* Create a pull request
* Wait for the pull request to be merged
* Celebrate
* Repeat

*If you are new to open source, you can read [this](https://opensource.guide/how-to-contribute/) to learn how to contribute to open source projects.*<br>
*If you are new to GitHub, you can read [this](https://guides.github.com/activities/hello-world/) to learn how to use GitHub.*<br>
*If you are new to Git, you can read [this](https://www.atlassian.com/git/tutorials/learn-git-with-bitbucket-cloud) to learn how to use Git.*<br>
*If you are new to TypeScript, you can read [this](https://www.typescriptlang.org/docs/handbook/typescript-in-5-minutes.html) to learn how to use TypeScript.*<br>


## License
IndexDBWrapper is released under the MIT License. You can find the full license details in the [LICENSE](LICENSE) file.

Made with ❤️ by [NightmareGaurav](https://github.com/nightmaregaurav).

---
Open For Contribution
---
