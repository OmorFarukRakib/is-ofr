
# Fancy-Loading-Animation

I have created some fancy looking loading animation components to use in your react project. There are many usefull props to easily customize the component to meet any need.


## Demo

Insert gif or link to demo

//LINK 
## Installation

Install my component with npm

```bash
  npm install my-project
```
    
## Screenshots

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)


## Usage/Examples
Import my component and use where you want to show the loading animation.
```javascript
import React from 'react'
import FancyLoadingAnimation from 'fancy-animated-loading'
import 'fancy-animated-loading/dist/index.css'

const App = () => {
  return (
    <FancyLoadingAnimation
      loadingAnimationVarient='bee'
      loadingAnimationDelay={0.3}
      loadingCharacterDirection='right'
      loadingTextStyle={{ color: 'orange' }}
      
    />
  )
}
export default App
```


## API Reference

#### These are the props to customize the component.



| Props     | Type     | Description                | Default   |
| :--------: | :-------: | :------------------------- | :------:    |
| `loadingAnimationVarient`   | `string`  | It will choose the varient of the loading animation among [`bug`, `bee`, `blue-bat`, `ghost`, `green-monster`, `hairy-monster`, `paper-bird`, `puppy` and `robot-ball`] | `bug`   |
| `loadingCharacterDirection`   | `string`  | It will choose the direction of the loading animation among [`left` and `right`] | `left`   |
| `loadingAnimationDelay`   | `number`  | It will slow/fast the loading animation among  | `1`   |
| `loadingSize`   | `number` | It will increase/decrease the whole animation size  | `1`  |
| `loadingSize`   | `number` | It will increase/decrease the whole animation size  | `1`  |
| `loadingContainerVisibility`   | `boolean` | Control the visibility of the container of the animation  | `true`  |
| `loadingContainerWidth`   | `number` | Control the width of the background container of the animation  | `280`  |
| `loadingContainerHeight`   | `number` | Control the height of the background container of the animation  | `280`  |
| `loadingContainerBorder`   | `string` | Modify the border of the background container of the animation [css property of border] | `1px solid rgb(0, 0, 0, 0.3)`  |
| `loadingContainerColor`   | `color` | Modify the color of the background container of the animation [css property of background-color] | `#d8d8d8`  |
| `loadingContainerShadow`   | `string` | Modify the shadow property of the background container of the animation [css property of box-shadow] | `inset 15px 15px 10px #999`  |
| `loadingText`   | `string` | Sets the loading text | `Loading`  |
| `loadingDotShow`   | `boolean` | Select whether to show dots after loading text | `true`  |

### Advance
#### If one wants to dive deeper and modify all the CSS property of all the animation elements [Container, Animation Character, Loading Text] then below props will help

| Props     | Type     | Description                | Default   |
| :--------: | :-------: | :------------------------- | :------:    |
| `loadingContainerStyle` | `CSS style Object` | Value pass through this props will set the style property of the container of the loading animation| `{}`    |
| `loadingAnimationStyle` | `CSS style Object` | Value pass through this props will set the style property of the loading animation character| `{}`    |
| `loadingTextStyle` | `CSS style Object` | Value pass through this props will set the style property of the loading text| `{}`    |

# Acknowledgements
#### I would like to show my gratitude towards below free sources/ assets/ tutorials to help me making this component.

 - [Frankslaboratory](https://www.youtube.com/c/Frankslaboratory)
 - [Free assets](https://bevouliin.com/)
 


## License

[MIT](https://choosealicense.com/licenses/mit/) © [OmorFarukRakib](https://github.com/OmorFarukRakib)


## Support

For support, email omorfarukrakib@gmail.com.




## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://katherinempeterson.com/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/)


