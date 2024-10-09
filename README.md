# Install NodeJS

```bash
python3 -m venv ~/python/nodejs
source ~/python/nodejs/bin/activate
pip install nodejs-bin nodejs-cmd
```

# Start the Slide Show

- `npm install`
- `npm run dev`
- visit http://localhost:3030

## Export

- `npm i -D playwright-chromium`
- `npx slidev export`
- `npx slidev export --with-clicks`

Edit the [slides.md](./slides.md) to see the changes.

Learn more about Slidev on [documentations](https://sli.dev/).

# Some Notes

## Correctness -> To Test Part?
- How would we define correct in terms of software?
- How can we proof that software is correct?
    - Writing correct software is a craft which requires discipline.
- What is the value of incorrect software?
    - software which is not correct has *no* value.