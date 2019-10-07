# Vanilla UJS

This is an implementation of Rails [jQuery UJS](jq-ujs) in pure JavaScript.
No extra dependencies. This will fix issues found when trying to utilize some Rails helpers that don't work in a webpacker project. e.g.

```erb
<%= link_to('Logout', destroy_user_session_path, method: :delete) %>
```

Does not send the request with a method of `DELETE`.

## Install

```sh
yarn add @airship/vanilla-ujs
```

## Usage

```js
// application.js
import "@airship/vanilla-ujs";
```

## Contribute

1.  Clone repo

        $ git clone git://github.com/hauleth/vanilla-ujs.git
        $ cd vanilla-js/

2.  Install dependencies

        $ yarn install

## License

See [`LICENSE`](LICENSE.txt) file.
