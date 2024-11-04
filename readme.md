# Shopify Reels Page Template

This project provides a **Reels Page Template** for Shopify, allowing store owners to create an Instagram-like reels view for showcasing products on their website. With this template, you can add a scrolling video reel display to your Shopify site, enhancing user experience and engagement.

## Features

- **Reel View Interface**: Mimics Instagram's reel view, allowing users to scroll through product videos.
- **Product Video Card**: Each reel links directly to its product page, encouraging conversions.
- **Vertical Scrolling Slider**: Built using the Slick slider (in vertical mode), creating a smooth reel-like scrolling effect.
- **Customizable Template**: Modify the template, CSS, and metafield names as needed for your store.

## Files Included

- **`reels-product.liquid`**: Main template file to add reels to your Shopify site.
- **`reels.css`**: Basic styling for the reels template, adaptable to your store's design.
- **`product-video-card`**: Contains code linking each reel to its corresponding product.

## Prerequisites

- **Slick Slider**: This template uses the [Slick Slider](https://kenwheeler.github.io/slick/) library to achieve the vertical scrolling effect. Ensure it's included in your project.
- **Custom Metafield**: A metafield called `reel` is required in the product setup to enable reel functionality. You can change the metafield name in the template if needed.

## Setup Instructions

1. **Upload Files**: Add `reels-product.liquid` to your Shopify theme's templates and `reels.css` to your CSS assets.
2. **Add Metafield**: In the Shopify admin panel, add a custom metafield to each product you want to feature in the reel. Name it `reel` (or rename it in `reels-product.liquid` if using a different name).
3. **Product Video Card Setup**: Ensure each product in the reel has a video in the metafield.
4. **Modify CSS**: Customize `reels.css` as desired to match your store's branding.

## Customization

- **Changing Metafield Name**: To use a different metafield name for reels, update the `reels-product.liquid` file where it references the `reel` metafield.
- **CSS Adjustments**: Modify `reels.css` to fit the aesthetic of your site, adjusting spacing, colors, and other styling elements as needed.

## Contributing

Feel free to open issues or pull requests if you would like to contribute to improving this project.

## License

This project is open-source under the MIT License.
