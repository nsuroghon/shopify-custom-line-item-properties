# Shopify custom line item properties

Collect custom information for products without a product customization app.

[Line Item Object - Shopify Doc](https://shopify.dev/api/liquid/objects/line_item)

## Product Form

Create new alternate product page template for your customizable product.
Include code block from product-template-customizable.liquid in your new page's form, above the submit button. 

## Cart Item

Display your custom variant / line-item in the cart. 

Find {{ item.product.title }}, or your product item in the cart template. 
Include code block from cart-template-liquid to assign custom variant/ line item properties as part of the product item in the cart. 

# More Info
Github: https://github.com/nsuroghon

Email: nsuroghon@gmail.com

![Screenshot of Product Form.](https://github.com/nsuroghon/shopify-custom-line-item-properties/blob/2b5f90942fe26e4edfe183c52c12b63cf693f458/example-image.png)
