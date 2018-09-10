# shopify-store-theme
Shopify store theme using Slate

# Notes about Shopify's config files

config/ settings_schema.json
  - Allows you to customize the look and feel of your store
  - Here a description of what might be inside
    - Current
      - contains data for the current theme settings
      - them only ever uses the data stored in current 
- Existing input types:
    article 
    blog
    checkbox 
    collection 
    color
    font_picker
    hidden
    html
    image
    image_picker
    layout
    link_list
    number 
    page
    product
    radio
    range
    richtext
    select 
    text
    textarea
    url
    video_url
  
 - These are whitelisted/presentational input types and are over written when applying a them style via the theme editor
    color
    select
    radio
    checkbox
    number
    font_picker
    range
  
 
