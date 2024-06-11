# Express REST Snippets

## Example

Initialize an express server with `exp` :

```javascript
const express = require('express');

const app = express();

const port = process.env.PORT || 3000;

app.listen(port, () => {
  console.log(`Server running at http://localhost:${port}`);
});
```

## Snippets

| Snippet | Description                                   |
| :------ | --------------------------------------------- |
| `exp`   | initialize an express server                  |
| `rtr`   | initialize an express router                  |
| `mid`   | add an express middleware                     |
| `rmid`  | add an express router middleware              |
| `emid`  | add an express error middleware               |
| `rt`    | add an express route                          |
| `ctrl`  | add an express controller                     |
| `res`   | add an express response expression            |
| `sres`  | add an express success response expression    |
| `eres`  | add an express error response expression      |
| `ncres` | add an express no-content response expression |

**Enjoy!**
