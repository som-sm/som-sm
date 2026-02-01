```
        ▄▄▄   ▄▄▄          ▄▄▄▄▄ ▄            ▄▄▄▄▄▄▄
▄▄      ███   ███ ▀▀        ███  ▀           █████▀▀▀
 ▀█▄    █████████ ██        ███   ███▄███▄    ▀████▄  ▄███▄ ███▄███▄
  ▄█▀   ███▀▀▀███ ██        ███   ██ ██ ██      ▀████ ██ ██ ██ ██ ██
▄█▀     ███   ███ ██▄ ▄▄   ▄███▄  ██ ██ ██   ███████▀ ▀███▀ ██ ██ ██
                     ▄█▀   A PASSIONATE WEB DEVELOPER AND TYPESCRIPT ENTHUSIAST
```

🌱 Maintainer of [`type-fest`](https://github.com/sindresorhus/type-fest), one of the most popular TypeScript utility libraries.


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
<table>
	<tr>
		<td>`Paths`: Fix behavior with generic types</td>
		<td>[#1343](https://github.com/sindresorhus/type-fest/pull/1343)</td>
	</tr>
	<tr>
		<td>`SimplifyDeep`: Fix behaviour with arrays</td>
		<td>[#1337](https://github.com/sindresorhus/type-fest/pull/1337)</td>
	</tr>
	<tr>
		<td>Fix incorrect ignore of temporary `.d.ts` files from fixtures in `xo.config.js`</td>
		<td>[#1333](https://github.com/sindresorhus/type-fest/pull/1333)</td>
	</tr>
	<tr>
		<td>`Merge`: Fix behavior with unions</td>
		<td>[#1327](https://github.com/sindresorhus/type-fest/pull/1327)</td>
	</tr>
	<tr>
		<td>Ignore temporary `.d.ts` files from `fixtures` in `xo.config.js`</td>
		<td>[#1326](https://github.com/sindresorhus/type-fest/pull/1326)</td>
	</tr>
	<tr>
		<td>Add `ObjectMerge` type</td>
		<td>[#1324](https://github.com/sindresorhus/type-fest/pull/1324)</td>
	</tr>
	<tr>
		<td>Sort numbers in unions while validating twoslash (`//=&gt;`) types in codeblocks</td>
		<td>[#1320](https://github.com/sindresorhus/type-fest/pull/1320)</td>
	</tr>
	<tr>
		<td>Fix `validate-jsdoc-codeblocks` rule to run diagnostics using latest file contents</td>
		<td>[#1310](https://github.com/sindresorhus/type-fest/pull/1310)</td>
	</tr>
	<tr>
		<td>Add linting to validate types specified via twoslash (`//=&gt;`) inside JSDoc codeblocks</td>
		<td>[#1309](https://github.com/sindresorhus/type-fest/pull/1309)</td>
	</tr>
	<tr>
		<td>Remove `test-export` workflow job</td>
		<td>[#1301](https://github.com/sindresorhus/type-fest/pull/1301)</td>
	</tr>
	<tr>
		<td>Add custom processor to lint JSDoc codeblocks</td>
		<td>[#1300](https://github.com/sindresorhus/type-fest/pull/1300)</td>
	</tr>
	<tr>
		<td>`ArraySlice` / `StringSlice`: Fix behaviour with unions</td>
		<td>[#1291](https://github.com/sindresorhus/type-fest/pull/1291)</td>
	</tr>
	<tr>
		<td>`GreaterThanOrEqual` / `LessThan`: Fix behaviour with operands like `N` and `N | N + &gt;0`</td>
		<td>[#1280](https://github.com/sindresorhus/type-fest/pull/1280)</td>
	</tr>
	<tr>
		<td>Add `ExclusifyUnion` type</td>
		<td>[#1278](https://github.com/sindresorhus/type-fest/pull/1278)</td>
	</tr>
	<tr>
		<td>`IfNotAnyOrNever`: Add note regarding tail recursion</td>
		<td>[#1276](https://github.com/sindresorhus/type-fest/pull/1276)</td>
	</tr>
	<tr>
		<td colspan="2">[View 87 more PRs](https://github.com/sindresorhus/type-fest/pulls?q=is%3Apr%20is%3Amerged%20author%3Asom-sm)</td>
	</tr>
</table>

### 📦 ts-essentials/ts-essentials
<table>
	<tr>
		<td>Fix: `Prettify` when instantiated with classes containing private/protected members</td>
		<td>[#450](https://github.com/ts-essentials/ts-essentials/pull/450)</td>
	</tr>
	<tr>
		<td>Fix: `IsTuple&lt;Type&gt;` when `Type` is an array containing rest element</td>
		<td>[#436](https://github.com/ts-essentials/ts-essentials/pull/436)</td>
	</tr>
	<tr>
		<td>Fix: `DeepReadonly&lt;Type&gt;` & `DeepRequired&lt;Type&gt;` when `Type` is an array containing rest element</td>
		<td>[#435](https://github.com/ts-essentials/ts-essentials/pull/435)</td>
	</tr>
	<tr>
		<td>Fix: `Head` type with union of empty and non-empty tuple</td>
		<td>[#425](https://github.com/ts-essentials/ts-essentials/pull/425)</td>
	</tr>
	<tr>
		<td>Fix: `Tail` with optional, readonly and non-tuple arrays</td>
		<td>[#424](https://github.com/ts-essentials/ts-essentials/pull/424)</td>
	</tr>
	<tr>
		<td>Feat: Prettify output of Mark-* & Merge types</td>
		<td>[#422](https://github.com/ts-essentials/ts-essentials/pull/422)</td>
	</tr>
	<tr>
		<td>Fix: `MarkRequired` and `MarkWritable` types when `Keys` is `any`</td>
		<td>[#421](https://github.com/ts-essentials/ts-essentials/pull/421)</td>
	</tr>
	<tr>
		<td>Fix: Make `MarkOptional&lt;Type, Keys extends keyof Type&gt;` assignable to `Partial&lt;Type&gt;`</td>
		<td>[#418](https://github.com/ts-essentials/ts-essentials/pull/418)</td>
	</tr>
	<tr>
		<td>Fix: Failing `test:fix` script</td>
		<td>[#417](https://github.com/ts-essentials/ts-essentials/pull/417)</td>
	</tr>
	<tr>
		<td>Fix: `ReadonlyKeys` and `WritableKeys` types with unions, arrays and index signatures</td>
		<td>[#416](https://github.com/ts-essentials/ts-essentials/pull/416)</td>
	</tr>
	<tr>
		<td>Fix: Behaviour of `Prettify` when instantiated with functions</td>
		<td>[#415](https://github.com/ts-essentials/ts-essentials/pull/415)</td>
	</tr>
	<tr>
		<td>Fix: Behaviour of `OptionalKeys` when instantiated with primitives and arrays</td>
		<td>[#414](https://github.com/ts-essentials/ts-essentials/pull/414)</td>
	</tr>
</table>

### 📦 orta/vscode-twoslash-queries
<table>
	<tr>
		<td>Fix query insertion with multiple cursors</td>
		<td>[#49](https://github.com/orta/vscode-twoslash-queries/pull/49)</td>
	</tr>
	<tr>
		<td>Allow `CMD+6` shortcut to position queries based on previous line's first available hint</td>
		<td>[#44](https://github.com/orta/vscode-twoslash-queries/pull/44)</td>
	</tr>
	<tr>
		<td>Disable inlay hints when there are characters following ^?</td>
		<td>[#42](https://github.com/orta/vscode-twoslash-queries/pull/42)</td>
	</tr>
	<tr>
		<td>Add command for inline comment (// =&gt;)</td>
		<td>[#41](https://github.com/orta/vscode-twoslash-queries/pull/41)</td>
	</tr>
</table>

### 📦 sindresorhus/eslint-plugin-unicorn
<table>
	<tr>
		<td>`prefer-string-raw`: Refactor implementation of helper function</td>
		<td>[#2692](https://github.com/sindresorhus/eslint-plugin-unicorn/pull/2692)</td>
	</tr>
	<tr>
		<td>`prefer-string-raw`: Add support for template literals</td>
		<td>[#2691](https://github.com/sindresorhus/eslint-plugin-unicorn/pull/2691)</td>
	</tr>
	<tr>
		<td>Add more test cases for `prefer-string-raw` rule</td>
		<td>[#2690](https://github.com/sindresorhus/eslint-plugin-unicorn/pull/2690)</td>
	</tr>
</table>

### 📦 xojs/xo
<table>
	<tr>
		<td>Fix: Behaviour of `print-config` option with relative file path</td>
		<td>[#816](https://github.com/xojs/xo/pull/816)</td>
	</tr>
	<tr>
		<td>Fix: Error while loading configs with custom plugins</td>
		<td>[#805](https://github.com/xojs/xo/pull/805)</td>
	</tr>
</table>

### 📦 DavidHDev/haiku
<table>
	<tr>
		<td>Fix `useLeaveDetection` to always invoke latest callback</td>
		<td>[#123](https://github.com/DavidHDev/haiku/pull/123)</td>
	</tr>
</table>

<!-- OSS_CONTRIBUTIONS:END -->
