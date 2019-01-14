# React Notification
[![Build Status](https://travis-ci.org/pburtchaell/react-notification.svg)](https://travis-ci.org/pburtchaell/react-notification) [![npm downloads](https://img.shields.io/npm/dm/react-notification.svg?style=flat)](http://badge.fury.io/js/react-notification)

React Notification provides snackbar notification messages.

```js
import { Notification } from 'react-notification';

<Notification
  message="This is a notification"
  action="Dismiss"
  isActive={this.state.isActive}
  onClick={() => {
    this.setState({
      isActive: false
    });
  }}
/>
```

The default visual style and interaction follows [Material Design guidelines for snackbars](http://www.google.com/design/spec/components/snackbars-toasts.html#snackbars-toasts-usage) and can be fully customized.

## Documentation and Help
- [Introduction](/docs/introduction.md)
- [Guides](/docs/guides/)
- [Examples](/examples)

## Maintainers
- [Patrick Burtchaell](http://github.com/pburtchaell)
- [Berkeley Martinez](https://github.com/BerkeleyTrue)
- [Joey Figaro](https://github.com/joeyfigaro)

## License
[Code licensed with the MIT License (MIT)](/LICENSE).

[Documentation licensed with the CC BY-NC License](https://creativecommons.org/licenses/by-nc/4.0/).
