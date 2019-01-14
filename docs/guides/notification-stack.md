# Notification Stack

```js
import { Component } from 'react';
import { NotificationStack } from 'react-notification';

class MyNotificationStack extends Component {
  constructor (props, context) {
    super(props, context);
    this.state = {
      notifications: []
    };
  }

  addNotification () {
    const newCount = count + 1;

    return this.setState({
      notifications: []
    });
  }

  removeNotification (count) {
    this.setState({
      notifications: this.state.notifications.filter(n => n.key !== count)
    })
  }

  render () {
    return (
      <NotificationStack
        notifications={this.state.notifications.toArray()}
        onDismiss={notification => this.setState({
          notifications: this.state.notifications.delete(notification)
        })}
      />
    );
  }
}
```
