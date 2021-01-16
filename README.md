# panel-binder-app
test deploying a simple webapp with panel on mybinder.org

Pangeo Binder

[![Binder](https://aws-uswest2-binder.pangeo.io/badge_logo.svg)](https://aws-uswest2-binder.pangeo.io/v2/gh/scottyhq/panel-binder-app/main?urlpath=%2Fpanel%2Fapp)


mybinder.org

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/scottyhq/panel-binder-app/main?urlpath=%2Fpanel%2Fapp)



Run locally
```
git clone https://github.com/scottyhq/panel-binder-app.git
cd panel-binder-app
conda env create -f environment.yml
conda activate panel
panel serve myapp
```
