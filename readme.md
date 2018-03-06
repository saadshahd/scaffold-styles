### Scaffold styles

Scaffold styles folder based on the guides of [cssguidelin.es](https://cssguidelin.es/)


#### Features
  - Structures as the guides
  - Includes [modern-normalize](https://github.com/sindresorhus/modern-normalize)
  - Includes [trump-maker](https://github.com/saadshahd/scss-mixin-trump-maker) mixin
  - Includes [object-scroller](https://github.com/saadshahd/scss-mixin-object-scroller) singletone object

#### Usage
  First make sure to change `./src/styles` to where you want to scaffold your styles

  - Clone the repo:
    ```
    git clone --depth=1 git@github.com:saadshahd/scaffold-styles.git ./src/styles
    ```
  - Remove **.git/** folder:
    ```
    rm -rf ./src/styles/.git
    ```
  - Add dependencies to your project package.json
    ```json
    {
      "scripts": {
        "postinstall": "npm --prefix ./src/styles install ./src/styles"
      }
    }
    ```
