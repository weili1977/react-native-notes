## 3 ways to popup keyboard gracefully ([reference](https://medium.freecodecamp.com/how-to-make-your-react-native-app-respond-gracefully-when-the-keyboard-pops-up-7442c1535580)):
- Use KeyboardAvoidingView, setting behavior to "padding"
- Use react-native-keyboard-aware-scroll-view (not sure if it interfere with the child ScrollView or ListView)
- Use keyboardWillShow and keyboardWillHide events and animate some elements on the screen

## Clean up app after upgrading RN version 

Delete node_modules folder, shut down all processes, yarn install, cmd+shift+k to clean the build, cmd+shift+b to create the build, and then cmd + r
