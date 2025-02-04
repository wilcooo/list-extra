# Convenience functions for working with `List`

Feedback and contributions are very welcome!

## Tests

This package uses [elm-test](https://github.com/elm-explorations/test) and [elm-verify-examples](https://github.com/stoeffel/elm-verify-examples).

## Contributing

Pull requests are welcome. You can expect some kind of response within 14 days.

If you are proposing a new function be added, please adhere to the following..

1. Include [documentation](http://package.elm-lang.org/help/documentation-format) and make sure your documentation has a code snippet demonstrating what the function does. We use [elm-verify-examples](https://github.com/stoeffel/elm-verify-examples) in our travis set up which verifies our examples that our example code is correct, so please take advantage of that.
2. Provide a detailed use case where your new function would be useful. Also, compare your new function to the best possible implementation that doesn't include use your function.
3. Add tests to `Tests/Tests.elm`

If you are improving existing functions please demonstrate the performance gains in something like [Ellie](https://ellie-app.com/) and by using a benchmark library like [this one](https://github.com/elm-explorations/benchmark). I usually copy and paste the last ellie bench mark I made, like [this one](https://ellie-app.com/gm9X8yfPLXMa1), so I don't have to set up the whole benchmark from scratch every time.
