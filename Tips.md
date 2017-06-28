3 ways to popup keyboard gracefully:
- Use KeyboardAvoidingView, setting behavior to "padding"
- Use react-native-keyboard-aware-scroll-view (not sure if it interfere with the child ScrollView or ListView)
- Use keyboardWillShow and keyboardWillHide events and animate some elements on the screen

