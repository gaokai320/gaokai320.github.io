My website forked from [Hugo Academic CV Theme](https://github.com/HugoBlox/theme-academic-cv)

## Customize Specification

1. `content` folder contains all content on the site. `en` subfolder for English version and `zh` subfolder for Chinese version.
2. Change `content/en/authors/admin/_index.md` and `content/zh/authors/admin/_index.md` for the `Biography` part in the `Home` page. Also, replace the `content/en/authors/admin/avatar.jpg` and `content/zh/authors/admin/avatar.jpg` to your own profile picture accordingly.
3. Do not change the folder name of `content/en/publication/` and `content/zh/publication/` to let the site generate publication filtering widget and cite pop-ups automatically.
4. Change `content/en/_index.md` and `content/zh/_index.md` to your own preference. You can refer to [the original file](https://raw.githubusercontent.com/HugoBlox/theme-academic-cv/main/content/_index.md) for more fancy customization.
5. Change `title` in `config/_default/hugo.yaml`.
6. Configure menus in the header for other language pages in `config/_default/languages.yaml`.
7. Configure menus in the header for English papes in `config/_default/menus.yaml`.
8. You can customize the theme in `data/themes/myminimal.toml` and font in `data/fonts/myfont.toml`.
9. Upload your resume in `static/uploads/` and your papers in `static/papers/`.