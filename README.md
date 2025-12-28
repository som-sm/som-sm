##### Hi 👋, I’m Som — a passionate web developer and TypeScript enthusiast 🚀

##### 🌱 I'm currently contributing to two of the most popular TypeScript utility libraries: [type-fest](https://github.com/sindresorhus/type-fest) and [ts-essentials](https://github.com/ts-essentials/ts-essentials). Checkout my contributions: [type-fest](https://github.com/sindresorhus/type-fest/pulls?q=is%3Apr+author%3Asom-sm+is%3Aclosed) and [ts-essentials](https://github.com/ts-essentials/ts-essentials/pulls?q=is%3Apr+is%3Aclosed+author%3Asom-sm) 🐙


<!--
**som-sm/som-sm** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

<br>

<!-- OSS_CONTRIBUTIONS:START -->
## 🧩 Open Source Contributions

### 📦 sindresorhus/type-fest
- [#1320](https://github.com/sindresorhus/type-fest/pull/1320)Sort numbers in unions while validating twoslash (`//=>`) types in codeblocks
- [#1310](https://github.com/sindresorhus/type-fest/pull/1310)Fix `validate-jsdoc-codeblocks` rule to run diagnostics using latest file contents
- [#1309](https://github.com/sindresorhus/type-fest/pull/1309)Add linting to validate types specified via twoslash (`//=>`) inside JSDoc codeblocks
- [#1301](https://github.com/sindresorhus/type-fest/pull/1301)Remove `test-export` workflow job
- [#1300](https://github.com/sindresorhus/type-fest/pull/1300)Add custom processor to lint JSDoc codeblocks
- [#1291](https://github.com/sindresorhus/type-fest/pull/1291)`ArraySlice` / `StringSlice`: Fix behaviour with unions
- [#1280](https://github.com/sindresorhus/type-fest/pull/1280)`GreaterThanOrEqual` / `LessThan`: Fix behaviour with operands like `N` and `N | N + >0`
- [#1278](https://github.com/sindresorhus/type-fest/pull/1278)Add `ExclusifyUnion` type
- [#1276](https://github.com/sindresorhus/type-fest/pull/1276)`IfNotAnyOrNever`: Add note regarding tail recursion
- [#1274](https://github.com/sindresorhus/type-fest/pull/1274)`ExcludeRestElement`: Fix generic assignability with arrays
- [#1269](https://github.com/sindresorhus/type-fest/pull/1269)`If`: Add note regarding tail recursion in documentation
- [#1267](https://github.com/sindresorhus/type-fest/pull/1267)Ensure `import-path` lint rule works on re-exports
- [#1266](https://github.com/sindresorhus/type-fest/pull/1266)Add `ArrayReverse` type
- [#1265](https://github.com/sindresorhus/type-fest/pull/1265)Add lint rule to validate JSDoc codeblocks using TS compiler
- [#1260](https://github.com/sindresorhus/type-fest/pull/1260)`UnionToIntersection`: Fix incorrect test case

 [View 81 more PRs](https://github.com/sindresorhus/type-fest/pulls?q=is%3Apr%20is%3Aclosed%20author%3Asom-sm)
### 📦 ts-essentials/ts-essentials
- [#450](https://github.com/ts-essentials/ts-essentials/pull/450)Fix: `Prettify` when instantiated with classes containing private/protected members
- [#436](https://github.com/ts-essentials/ts-essentials/pull/436)Fix: `IsTuple<Type>` when `Type` is an array containing rest element
- [#435](https://github.com/ts-essentials/ts-essentials/pull/435)Fix: `DeepReadonly<Type>` & `DeepRequired<Type>` when `Type` is an array containing rest element
- [#425](https://github.com/ts-essentials/ts-essentials/pull/425)Fix: `Head` type with union of empty and non-empty tuple
- [#424](https://github.com/ts-essentials/ts-essentials/pull/424)Fix: `Tail` with optional, readonly and non-tuple arrays
- [#422](https://github.com/ts-essentials/ts-essentials/pull/422)Feat: Prettify output of Mark-* & Merge types
- [#421](https://github.com/ts-essentials/ts-essentials/pull/421)Fix: `MarkRequired` and `MarkWritable` types when `Keys` is `any`
- [#418](https://github.com/ts-essentials/ts-essentials/pull/418)Fix: Make `MarkOptional<Type, Keys extends keyof Type>` assignable to `Partial<Type>`
- [#417](https://github.com/ts-essentials/ts-essentials/pull/417)Fix: Failing `test:fix` script
- [#416](https://github.com/ts-essentials/ts-essentials/pull/416)Fix: `ReadonlyKeys` and `WritableKeys` types with unions, arrays and index signatures
- [#415](https://github.com/ts-essentials/ts-essentials/pull/415)Fix: Behaviour of `Prettify` when instantiated with functions
- [#414](https://github.com/ts-essentials/ts-essentials/pull/414)Fix: Behaviour of `OptionalKeys` when instantiated with primitives and arrays
### 📦 orta/vscode-twoslash-queries
- [#46](https://github.com/orta/vscode-twoslash-queries/pull/46)Remove extra spaces from inlay hint
- [#44](https://github.com/orta/vscode-twoslash-queries/pull/44)Allow `CMD+6` shortcut to position queries based on previous line's first available hint
- [#42](https://github.com/orta/vscode-twoslash-queries/pull/42)Disable inlay hints when there are characters following ^?
- [#41](https://github.com/orta/vscode-twoslash-queries/pull/41)Add command for inline comment (// =>)
### 📦 sindresorhus/eslint-plugin-unicorn
- [#2692](https://github.com/sindresorhus/eslint-plugin-unicorn/pull/2692)`prefer-string-raw`: Refactor implementation of helper function
- [#2691](https://github.com/sindresorhus/eslint-plugin-unicorn/pull/2691)`prefer-string-raw`: Add support for template literals
- [#2690](https://github.com/sindresorhus/eslint-plugin-unicorn/pull/2690)Add more test cases for `prefer-string-raw` rule
### 📦 xojs/xo
- [#816](https://github.com/xojs/xo/pull/816)Fix: Behaviour of `print-config` option with relative file path
- [#805](https://github.com/xojs/xo/pull/805)Fix: Error while loading configs with custom plugins
### 📦 DavidHDev/haiku
- [#123](https://github.com/DavidHDev/haiku/pull/123)Fix `useLeaveDetection` to always invoke latest callback
<!-- OSS_CONTRIBUTIONS:END -->
