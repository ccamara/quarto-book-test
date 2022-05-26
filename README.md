This is a readme file. It should be embedded within a book's page by following [these instructions]()

This is what I've done so far:

1. Create a default project: `quarto create-project mybook --type book`
2. Create a `README.md`file in the project's root
3. Edit `index.md` (in the project's root) and added `{{< include README.md >}}`
4. Run `quarto preview`
5. I get a warning stating `WARNING: Shortcode include is not recognized.`
6. `index.md` does not render `README.md`contents, instead it displays the include shortcode as a regular text.