---
hide:
  - toc
  - navigation
---

{% import 'tiles.md' as tiles %}

# Contact

{% call tiles.contact_tile_wall() %}

  {{ tiles.contact_tile_image('../images/nihal.png', 
                              'Nihal Pasham', 
                              'Mailbox.pasham.nihalgoud@in.bosch.com') }}
  {{ tiles.contact_tile('Nihal<br/>Pasham', 
                        'Rust<br/>Developer', 
                        '', 
                        'Mailbox.pasham.nihalgoud@in.bosch.com', 
                        color='green-slight-fade') }}

  {{ tiles.contact_tile_image('../images/yashwanth.png', 
                              'Yashwanth M Singh', 
                              'Mailbox.yashwanth.singhm@in.bosch.com') }}
  {{ tiles.contact_tile('Yashwanth<br/>M Singh', 
                        'Rust<br/>Developer', 
                        '', 
                        'Mailbox.yashwanth.singhm@in.bosch.com', 
                        color='green-slight-fade') }}

  {{ tiles.contact_tile_image('../images/brian.png', 
                              'Brian Dcosta', 
                              'Mailbox.brianfrancisolaf.dcosta@in.bosch.com') }}
  {{ tiles.contact_tile('Brian<br/>Dcosta', 
                        'Rust<br/>Developer', 
                        '', 
                        'Mailbox.brianfrancisolaf.dcosta@in.bosch.com', 
                        color='green-slight-fade') }}
  
  {{ tiles.contact_tile_image('../images/anand.png', 
                              'Anand Gedam', 
                              'Mailbox.anand.bhauraojigedam@in.bosch.com') }}
  {{ tiles.contact_tile('Anand<br/>Gedam', 
                        'Rust<br/>Developer', 
                        '', 
                        'Mailbox.anand.bhauraojigedam@in.bosch.com', 
                        color='green-slight-fade') }}
  
   {{ tiles.contact_tile_image('../images/imran.png', 
                              'Imran K', 
                              'Mailbox.imran.khaleelsab@in.bosch.com') }}
  {{ tiles.contact_tile('Imran K<br/>', 
                        'Rust<br/>Developer',
                        '',
                        'Mailbox.imran.khaleelsab@in.bosch.com', 
                        color='green-slight-fade') }}

   {{ tiles.contact_tile_image('../images/sarath.png', 
                              'Sarath Kumar', 
                              'Mailbox.bobbili.sarathkumar@in.bosch.com') }}
  {{ tiles.contact_tile('Sarath<br/>Kumar', 
                        'Rust<br/>Developer',
                        '',
                        'Mailbox.bobbili.sarathkumar@in.bosch.com', 
                        color='green-slight-fade') }}

{% endcall %}
