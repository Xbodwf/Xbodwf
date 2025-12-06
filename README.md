## Hi there 👋

![](https://komarev.com/ghpvc/?username=Xbodwf)

```typescript
import { registerUser as register,Info } from '@/register'

register(
  class Xbodwf extends Info {
    readonly name: string = 'Xbodwf'
    description: string = 'A busy student developer'

    readonly contacts: {[key:string]: string|Array<string>} = {
      "Bilibili": "space.bilibili.com/1552375363",
      "X": "@Xbodwf",
      "Youtube": "@xbodwf",
      "Facebook": "www.facebook.com/profile.php?id=61578291371044",
      "Email": ["xbodwf@outlook.com","xbodw@gmail.com"]
    }
    constructor() {
      super()
      console.log("Loaded")
    }
    get status(): string {
      return 'Write all kinds of strange code into repositories...'
    }
  }
)
```
