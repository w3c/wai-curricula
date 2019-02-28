The files in this repository are companion files to the next version of the `wai-website-theme`, developed at `w3c/wai-website-theme-beta`. Repositories that update to the new theme need to use these files as a submodule.

## How to do it

From the base directory of your repository, execute the following commands.

If you already have a `_data` directory, delete it. Then:
```
git submodule add https://github.com/w3c/wai-website-data.git _external/data
mkdir _data
cd _data
ln -s ../_external/data/lang.json
ln -s ../_external/data/navigation.yml
ln -s ../_external/data/techniques.yml
ln -s ../_external/data/translations.yml
ln -s ../_external/data/wcag.yml
```