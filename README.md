# Website for NYU CS Theory Students

This website is intended for sharing and broadcasting the brilliant work of the CS Theory PhD students at NYU. Additionally, we will be using the website to organize student seminars and other fun events.

## Sharing a post
If you would like to share a post on the website, you can email the website maintainers (emails below) or make a pull request to the `docs` directory. 

To maintain some uniformity, we will be using the given [Quarto](https://quarto.org) template in the [template](./template/) directory. Copy the entire directory and edit the `template.qmd` file only. Write up your posts and share the `.qmd` file with us. **All posts will be HTML renderings of the `.qmd` files.**

If you would like to use some other typesetting program or share something else, please reach out to us and we can figure something out.

## Editing the website
We welcome edits and updates to the website. The website uses [TailwindCSS](https://tailwindcss.com) to build the CSS. While making CSS edits, please run the following tailwind compile command at the project root:
```bash
npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch
```
You might need to do an `npm install` when setting the project up.

## More documentation to come soon...