# vg-legal-documents
                    
## Legal documents that apply to the Vision Group AG ecommerce shops:
  
### For Developers:
  
#### Terms and conditions      
                                                                                                                            
Example for getting terms and conditions page for locale: de, shop: lensvision.de

Locales: `de`, `en`

Template paths for Twig renderer: `['terms-and-conditions', 'terms-and-conditions/de', 'terms-and-conditions/de/lensvision.de']`

Template file to render: `document.md.twig`

Available parameters: `company_name`, `phone_number`, `support_email`

Default values defined in `_base.twig`

    company_name: Vision Group AG
    phone_number: +41 234 56 78
    support_email: info@visiongroup.io

