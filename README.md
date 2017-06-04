# React-Native Snippets

Made for Atom

To use:
1. Copy and paste the code from the snippets.cson file
2. Open Atom, click Atom in the toolbar, then click Snippets... from the dropdown
3. Paste code in the file that opened and save the file

## Class Component
### nccom + enter will return:
```javascript
import React from 'react';
import {
  View,
  Text.
  } from 'react-native';

    export default class $1 extends Component {
      render(){
        return(
          <View>
            <Text>$2</Text>
          </View>
        );
      }
    }
```
## Functional Component
### nfcom + enter will return:
```javascript
import React from 'react';
import {
  View,
  Text.
  } from 'react-native';

  const $1 = () => {
      return(
        <View>
          <Text>$2</Text>
        </View>
      );
    };

export default $3;
```
## Constructor
### ncon + enter will return:
```javascript
constructor(props){
  super(props);

  this.state = {$1};
}
```
## StyleSheet
### nsty + enter will return:
```javascript
const styles = StyleSheet.create({
  container: {
    $1: $2,
  },
});
```
