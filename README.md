**_UPDATE: Pull request created with slightly modified code._**
[**Repo**](https://github.com/dev-dano/react-native-elements)

<img src='https://github.com/dev-dano/react-native-elements-multiAvatar/blob/master/src/images/comment1.png?raw=true' width="80%" height="80%">

<img src='https://github.com/dev-dano/react-native-elements-multiAvatar/blob/master/src/images/comment3.png?raw=true' width="80%" height="80%">

<img src='https://github.com/dev-dano/react-native-elements-multiAvatar/blob/master/src/images/comment2.png?raw=true' width="80%" height="80%">

------

# react-native-elements-multiAvatar
Avatar component can now take an array of image sources to render multiple images in a single avatar.

## Example

```js
<Avatar
  rounded
  size='large'
  source={{ uri: '...' }}
/>
```
&emsp;or
```js
<Avatar
  rounded
  size='large'
  source={ [{ uri: '...' }, { uri: '...' }, { uri: '...' }] }
/>
```

## Use case
Group chat

<img src='https://github.com/dev-dano/react-native-elements-multiAvatar/blob/master/src/images/example.png?raw=true' width="40%" height="40%">
