# rax-snippets

## Snippets

| Snippet | Renders                     |
| ------- | --------------------------- |
| `imc`   | Import Rax                  |
| `imcc`  | Import Rax / Component      |
| `imv`   | Import View                 |
| `imt`   | Import Text                 |
| `ima`   | Import All                  |
| `cc`    | Class Component             |
| `rct`   | Class Component Template    |
| `rft`   | Function Component Template |
| `hoc`   | Higher Order Component      |
| `view`  | view tag                    |
| `text`  | text tag                    |

## Full Expansions

### imc - Import Rax

```javascript
import { createElement } from 'rax';
```

### imcc - Import rax, Component

```javascript
import { createElement, Component } from 'rax';
```

### imv - Import View

```javascript
import View from 'rax-view';
```

### imt - Import Text

```javascript
import Text from 'rax-text';
```

### ima - Import All

```javascript
import { createElement, Component } from 'rax';
import Text from 'rax-text';
import View from 'rax-view';
```

### cc - Class Component

```javascript
class | extends Component {
  state = { | },
  render() {
    return ( | );
  }
}

export default |;
```

### rct - Class Component Template

```javascript
import { createElement, Component } from 'rax';
import Text from 'rax-text';
import View from 'rax-view';
class | extends Component {
  state = { | }

  render() {
    return ( | );
  }
}

export default |;
```

### rft - Function Component Template

```javascript
import { createElement } from 'rax';
import Text from 'rax-text';
import View from 'rax-view';
function |() {

  return ( | );
}

export default |;
```

### hoc - Higher Order Component

```javascript
function | (|) {
  return class extends Component {
    constructor(props) {
      super(props);
    }

    render() {
      return < | {...this.props} />;
    }
  };
}
```

### view - View

```javascript
<View></View>
```

### text - Text

```javascript
<Text></Text>
```


