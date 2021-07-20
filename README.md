# rn-image-placeholder

## Require
React-native >= 0.46.x

## Installation

```bash
npm install --save rn-image-placeholder
```

## Usage

```jsx
import ImageLoader from 'rn-image-placeholder';

....

<ImageLoader
    style={{ width: 320, height: 250 }}
    loadingStyle={{ size: 'large', color: 'blue' }}
    source={{ uri: 'https://images.pexels.com/photos/5970/road-nature-forest-trees.jpg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940' }}
/>
```
## Options
Supports all [Image](https://facebook.github.io/react-native/docs/images.html) properties.

Option |Default |Info
------ |---- |----
placeholderSource |require('./img/img_empty.png') |Show `placeholderSource` if the `source` can't be loaded or error.
loadingStyle |size: 'small'; color: 'gray' | Style ActivityIndicator
isShowActivity | true | Show ActivityIndicator loading
placeholderStyle | | Style placeholder image
customImagePlaceholderDefaultStyle | | Custom style image placeholder default
borderRadius | | Border radius
## License

ISC
