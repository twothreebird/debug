# Debug

Provides a universal URL that can be used to echo failure messages to aid in debugging undesirable behaviors when no other endpoint is available.

## Usage

All you need to do is make use the [pages URL](https://twothreebird.github.io/debug/?tag=project&message=My%20message%20that%20explaines%20the%20implementation%20issue!) of this repository and pass in the following **two query string**.

| Query Parameter | Description                                                                                               |
|-----------------|-----------------------------------------------------------------------------------------------------------|
| tag             | Displays a tag above the debug message, useful to identify the application where the bug originated from. |
| message         | The debugging message, should explain the reason for the exception failure.                               |

### Example

[View example](https://twothreebird.github.io/debug/?tag=project&message=My%20message%20that%20explaines%20the%20implementation%20issue!)

```text
https://twothreebird.github.io/debug/?tag=project&message=My%20message%20that%20explaines%20the%20implementation%20issue!
```

![Example](https://twothreebird.github.io/debug/img/screenshot.png)
