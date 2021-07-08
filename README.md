# Simple Snipcart Shop

This theme is a simple, customizable, single pages marketplace designed to work with [Snipcart](https://snipcart.com)

![Screenshot](https://raw.githubusercontent.com/tylerjlawson/simple-snipcart-shop/master/images/screenshot.png)

## Features

- Easy sections for selling and displaying reviews
- PostCSS for autoprefixing
- SCSS for easy styling
- [Snipcart](https://snipcart.com)

## Install theme on your hugo site

```
hugo new site your-site-name # if you already have a site ignore this line and the next
cd your-site-name
cd themes
git clone https://github.com/tylerjlawson/simple-snipcart-shop.git
```

Once you have done this, you may use the `exampleSite` folder as an example for how to set your project up. The two main things to pay attention to is to first set this in your `config.toml` file:

```toml
theme = "simple-snipcart-shop"
```

Then you will need to replicate the data used in the `exampleSite/data/reviews/` if you want to show reviews. Please also see the `exampleSite/config.toml` for guidance on setting up the more general site configurations.

## Contributing

Please feel free to post issues or make pull requests at any time. I am always open to collaboration.
