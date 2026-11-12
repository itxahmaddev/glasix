[Glasix](https://glasix.vercel.app) is a faithful implementation of Apple's Liquid Glass for the web.

## Usage

To start using the library, install it in your project:

```bash
npm install glasix
```

Then use the components anywhere. Their styles come with them.

```tsx
import { Button, Switch } from "glasix";

function Settings() {
  return (
    <div>
      <Switch aria-label="Wi-Fi" defaultChecked />
      <Button variant="filled">Continue</Button>
    </div>
  );
}
```

## Documentation

See every component, with live examples and code, at [Glasix](https://glasix.vercel.app).

## License

MIT