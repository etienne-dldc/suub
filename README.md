# Suub

> A simple pub/sub written in Typescript

## Gist

```ts
import { Subscription } from '../dist';

const mySub = Subscription.create<number>();

const unsub = mySub.subscribe(num => {
  console.log('num: ' + name);
});

mySub.call(45); // num: 45

unsub();
```