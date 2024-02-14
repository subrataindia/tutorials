```
import ScanIcon from './iconscan.png';
```
in react native typescript the above line works fine but shows the below typescript error

```
Cannot find module './iconscan.png' or its corresponding type declarations.
```

### Solution:

The error encountered indicates that TypeScript can't find type declarations for the module ./iconscan.png. In TypeScript, we need to provide type declarations for non-code assets like images.

To resolve this issue, we can create a file, for example, images.d.ts, and declare the module like this:

```
declare module '*.png' {
  const value: any;
  export default value;
}
```

N.B.: Make sure this file is in a location where TypeScript will include it automatically (e.g., in the same directory as your tsconfig.json).
