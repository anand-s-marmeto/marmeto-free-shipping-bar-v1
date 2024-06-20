# marmeto-components

Paste the below code snippet in settings-schema.json to get the option to enter the free-shipping-price threshold in global-settings.


{
    "name": "Free shipping bar",
    "settings": [
      {
        "type": "text",
        "id": "free_shipping",
        "label": "Free shipping limit"
      },
      {
        "type": "richtext",
        "id": "free_shipping_heading",
        "label": "Heading",
        "default":"<p>Free shipping</p>"
      }
    ]
  }
