# Local Storage Node Adapter

<p>
    <img alt="Stack: Back-End" src="https://img.shields.io/static/v1?label=stack&message=back-end&color=important&style=flat-square" />
    <a href="https://github.com/sandtr0ut/local-storage-node-adapter#readme">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen?style=flat-square" target="_blank" />
    </a>
    <a href="https://github.com/sandtr0ut/local-storage-node-adapter/graphs/commit-activity">
    <img alt="Maintenance" src="https://img.shields.io/badge/Maintained%3F-yes-blueviolet?style=flat-square" target="_blank" />
    </a>
    <a href="https://github.com/sandtr0ut/local-storage-node-adapter/issues">
    <img alt="Issues" src="https://img.shields.io/github/issues/sandtr0ut/crystals-collector?style=flat-square" target="_blank" />
    </a>
    <a href="https://github.com/sandtr0ut/local-storage-node-adapter/blob/master/LICENSE">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow?style=flat-square" target="_blank" />
  </a>
</p>

An ultra-simple adapter that provides browser-like, local-storage capability for Node.js/file system

## Usage

```
node index.js

    ...checks local storage for user_id
```

**if (no user is found):**

> - Creates new user_id, sets token

**else:**

> - Returns localStorage.json
> - Logs localStorage.length, user_id to the console
> - Removes user and clears localStorage

<br>

## 👤 **Ford Crosby**

- Website: [fordcrosby.com](fordcrosby.com)
- LinkedIn: [@FordCrosby](https://www.linkedin.com/in/fordcrosby/)
- Github: [@sandtr0ut](https://github.com/sandtr0ut)
- Twitter: [@FordCrosby](https://twitter.com/FordCrosby)

## Credit/Thanks

Special thanks to Alex Banks github.com/MoonTahoe
I found this useful bit of code while taking his LinkedIn Learning course, [Node.js: Design Patterns](https://www.linkedin.com/learning/node-js-design-patterns)
