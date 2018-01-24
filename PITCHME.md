### Serverless Architecture with AWS Lambda

<span class="subtitle">for your next mobile project.</span>

---

## The Technology?

- Lambda |
- API Gateway |
- Dynamo |
- Serverless Framework |
- A Client/Front-end |

---

## How it works?

- Mobile Apps in JavaScript |
- Cross-platform |
- Declarative |
- Uses the React Paradigm |
- Learn once build anywhere |

---

## React - JSX

```
import React, { Component } from 'react';
import ReactDOM from 'react-dom';

class App extends Component {
    render() {
        return (
            <div>
                <h1>Hello App!</h1>
            </div>
        );
    }
}
ReactDOM.render(<app></app>, document.getElementById('root'));
```

@[1,2](Remember you can use the GitPitch code presenting feature too)
@[4,12](So you can step through your code just like you would within an IDE)
@[7-9](But do this from  directly within your slideshow presentation)
@[1-13](Great for you, and great for your audience to follow along.)

---

## React - JSX

```
import React, { Component } from 'react';
import ReactDOM from 'react-dom';

class App extends Component {
    constructor () {
        super();
        this.state = {
            count: 0
        };
        this.add = this.add.bind(this);
    }

    add () {
        this.setState({
            count: this.state.count + 1
        });
    }

    render () {
        return (
            <div>
                <h1>Count = {this.state.count}</h1>
                <button>Add</button>
            </div>
        );
    }
}
ReactDOM.render(<app></app>, document.getElementById('root'));
```

---

## React Native - JSX

```
import React, { Component } from 'react';
import { AppRegistry, View, Text } from 'react-native';

class App extends Component {
    render() {
        return (
            <view>
                <text>Hello App!</text>
            </view>
        );
    }
}
AppRegistry.registerComponent('AwesomeProject', () =&gt; App);
```

---

## React Native - JSX

```
import React, { Component } from 'react';
import {
    AppRegistry,
    View,
    Text,
    TouchableOpacity
} from 'react-native';

class App extends Component {
    constructor () {
        super();
        this.state = {
            count: 0
        };
        this.add = this.add.bind(this);
    }

    add () {
        this.setState({
            count: this.state.count + 1
        });
    }

    render() {
        return (
            <view>
                <text>Count: {this.state.count}</text>
                <touchableopacity>
                <text>Add One</text>
                </touchableopacity>
            </view>
        );
    }
}
AppRegistry.registerComponent('AwesomeProject', () =&gt; App);
```

---

## Default Styling with Flexbox

```yaml
display: 'flex'
flex-direction: 'column'
```

---

## Benefits of React Native

- Fast Developer Iteration
- Cross-platform code sharing
- Native Views
- Performance
- Built in developers tools
- Re-use web skills

---

## Web Ecosystem

- Geolocation
- Fetch
- WebGL
- NPM/JS Libraries

---

### End of Demo

@fa[smile-o fa-big-smile]

