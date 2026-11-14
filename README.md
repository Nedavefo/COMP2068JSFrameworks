# COMP2068 JavaScript Frameworks – Labs

Node.js labs for the COMP2068 *JavaScript Frameworks* course.

| Folder | What it is |
|---|---|
| `LAB01` | First Node.js script (`lab1.js`) |
| `LAB02` | Rock, paper, scissors in the terminal: validates input with `prompt-sync`, picks a random move and decides the winner |
| `LAB03` | Calculator HTTP server with `connect`: reads `method`, `x` and `y` from the query string, supports add, subtract, multiply and divide, and validates numbers and division by zero |
| `ASSIGNMENT01`, `ASSIGNMENT02` | Placeholders (empty) |

## Run

```bash
npm install prompt-sync connect
node LAB02/LAB01.js
node LAB03/server.js
```

Example request for LAB03: `http://localhost:3000/lab3?method=add&x=2&y=3`
