# j-Binder

This component can help with changing of dynamic content, class or visibility. The component can be hooked on a `body` element. It's optimized for the performance.

__Supported attributes__:

- `data-b="SOME.PATH"`
- `data-b-visible="value => value > 100 && value < 1000"` - optional, toggles `hidden` class
- `data-b-class="value => value === 100 ? '+selected +animate -border -margin' : '-selected -animate +border +margin'` - optional, adds and removes classes
- `data-b-content="value => value && value.price ? value.price.format(2) : 'without price'` - optional, sets HTML content
- HTML content can contain Tangular template `{{ value }}`