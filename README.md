# ravennareading.github.io

The website for Ravenna Reading: the home page, privacy policy and support page. Plain static HTML served by GitHub
Pages at https://ravennareading.github.io/; no build step.

- `index.html`: home page
- `privacy.html`: privacy policy (the stores' "Privacy Policy URL")
- `support.html`: support, FAQ, terms and credits (App Store "Support URL")
- `img/`: screens, icon and share image, made by `tool/store_art.sh` in the app repo (`store/web/`)
- `video/`: the trailer and its poster, made by `tool/make_trailer.sh` in the app repo (`store/web/video/`)
- `fonts/`: Fredoka (SIL Open Font License), self-hosted so the site loads nothing from third parties

To update the pictures or the trailer, run those tools in the app repo and copy `store/web/` over this folder.
