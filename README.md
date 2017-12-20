# Webstorm Live Templates

## Javascript

### console.log

`log`

```javascript
console.log($END$);
```

### Section comment

`c.sec`

```javascript
// ===============================================================================
// Section
// ===============================================================================
```

## React

### Class

`r.cls`

```javascript
import React from 'react';
import classNames from 'classnames';

export default class ComponentName extends React.Component {

    render() {

        return (
            <div>
            </div>
        );
    }
}

ComponentName.propTypes = {
    
};

ComponentName.defaultProps = {
    
};
```

### Constructor

`r.cons`

```javascript
constructor(props, context){
    super(props, context);
}
```

### componentDidMount

`r.cdm`

```javascript
componentDidMount() {
  $END$
}
```

### componentWillReceiveProps

`r.cwrp`

```javascript
componentWillReceiveProps(nextProps, nextContext) {
  $END$
}
```

## Tests

### Test File Imports

`t.imp`

```javascript
import React from 'react';
import {mount, shallow} from 'enzyme';
import {fromJS} from 'immutable';
```

### Test Suite

`t.desc`

```javascript
describe('$END$', () => {

});
```

### Test Case

`t.test`

```javascript
test('$END$', () => {

});
```

# CSS

### Section comment

`c.sec`

```css
/*------------------------------------*\
  #$END$
\*------------------------------------*/
```
