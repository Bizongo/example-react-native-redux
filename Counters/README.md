## Counters Example

<p align="center">
    <img src ="https://raw.githubusercontent.com/alinz/example-react-native-redux/master/Counters/demo.gif" />
</p>

#### React-Native 0.32.0 & Redux 3.5.2 & React-Redux 4.4.5

This is a little bit more complex than my previous example, I added as many comments as I can so to prevent confusion. Take your time, there are a lot of
things to read and undrestand. Open an issue if you need to clear something I will do my best to respond back.

### about this example

This example demonstrates my way of using React-Native and Redux for making apps. I found that
using Stateless components makes my code a lot cleaner and simpler. However, using
stateless components are hard, you have to think a lot. But in long run it will pay of. trust me ;)

> I'm not say that Class components are bad. I'm just saying that start with Stateless components first.
If you can't find any other solution, then use the Class Component.

In this example, I'm using [ducks-modular-redux](https://github.com/erikras/ducks-modular-redux) pattern with a small tweak.

This example is also show casing how to use `thunk`. There is an action called `incrementWithDelay`. check that one out.


Cheers,
Ali
