# Cody Lang's Website!

This website is made using `Hugo` and the `Congo theme`.


https://github.com/user-attachments/assets/8b7b291d-5655-46cb-848b-ad4865ae3dbd


To view a development page of this webite,

- Clone the github repository, `git clone https://github.com/liamadale/cody-lang-website.git`
- Make sure Hugo is installed, `winget install Hugo.Hugo.Extended`
- Run the development server from the root directory using: `hugo server`

## Layout and other important files

`/content/` folder is responsible for hosting markdown files which turn into pages.

`/config/params.toml` contains a lot of the configuration lines for the Congo theme. [Read more here.](https://jpanther.github.io/congo/docs/configuration/)

`/config/menus.en.toml` contains the configuration for the navbar in the header, you can add or remove entries here.

`/config/languages.en.toml` contains information regarding the profile located on this website. Fill this out with your own information and links to make sure that it properly reflects what is accurate.

In addition to the contact info in the `languages.en.toml` file, you should also update the `/content/_index.md` at the bottom to reflect the correct email address for the href and text section of the button, also, you should update the `/content/services.md` as well, the button can be found at the bottom of the page.

## Deploying to github pages

[To deploy this website using github pages, I suggest that you read the Congo theme's own documentation on the matter here.](https://jpanther.github.io/congo/docs/hosting-deployment/)
