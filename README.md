# Well-HTML-Product-Template


### Product template for the Well Coffeehouse with custom dropdown and brew guide button.


To use: 
1. Copy this code. 
2. Place appropriate data on each line AFTER the `</strong>` and before the `<p>` Ex: `<p><strong>Roast: </strong>Dark Roast</p>`
3. Remove any `<p>`'s that are not necessary
4. IF the extra product info is not needed, delete from `<div class="extra-product-info">` down to the bottom of the file. Take care not to delete the `<div>` for the brew guides button! 
5. Make sure to use the "code mode" on the product info section on Shopify. On the description box, click the "Edit HTML" button on the right side (Has this symbol <>)
6. Paste code into the editor!
```
<p><strong>Description: </strong></p>
<p><strong>Roast: </strong></p>
<p><strong>Process: </strong></p>
<p><strong>Notes: </strong></p>
<p><strong>Organic: </strong></p>
<p><strong>Coffee Grade: </strong></p>
<p><strong>Varietal: </strong></p>
<div class="product_brew-guides"><a href="https://well-coffeehouse.myshopify.com/blogs/brew-guides"> <i
      class="fas fa-coffee"></i> Brew Guides</a></div>
<div class="extra-product-info">
  <div class="product-dropdown"><button class="collapsible" type="button">Coffee Details</button>
    <div class="content">
      <p><strong>Origin (Country): </strong></p>
      <p><strong>Region: </strong></p>
      <p><strong>Subregion/Town: </strong></p>
      <p><strong>Farm/Coop/Station: </strong></p>
      <p><strong>Farm Size: </strong></p>
      <p><strong>Area Under Coffee :</strong></p>
      <p><strong>Harvest Months: </strong></p>
      <p><strong>Owner: </strong></p>
      <p><strong>Farmer: </strong></p>
      <p><strong>Altitude: </strong></p>
    </div>
  </div>
</div>

```
