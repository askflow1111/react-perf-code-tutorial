This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).

# React performance code tutorial

## Objectives:

1. Explain React performance pitfalls
2. Implement `shouldComponentUpdate`
3. Implement `PureComponent`
4. Understand why component methods should be bound in `constructor`
5. Utilize `why-did-you-update`
6. Understand the use and necessity of immutability

The code is commented out, refer there for explanations. Feel free to open a pull request to add additional comments, etc.

Notice right now that if you toggle the pointless state, `List.jsx` is re-rendered unnecessarily. `why-did-you-update` warns us about this in the console. The point of this tutorial is to implement either `shouldComponentUpdate` or `PureComponent` to avoid that re-render. Immutability is an important component of that.