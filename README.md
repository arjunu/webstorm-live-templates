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

import React, { Component } from 'react';
import classNames from 'classnames';

class $TM_FILENAME_BASE$ extends Component {
  render() {
    return <div>$END$</div>;
  }
}

$TM_FILENAME_BASE$.propTypes = {
    
};

$TM_FILENAME_BASE$.defaultProps = {
    
};

export default $TM_FILENAME_BASE$;
```

### Constructor

`r.cons`

```javascript
constructor(props){
    super(props);
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
componentWillReceiveProps(nextProps) {
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
  test('', () => {

  });  
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
