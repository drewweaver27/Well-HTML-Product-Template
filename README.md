# Well-HTML-Product-Template


### Product template for the Well Coffeehouse with custom dropdown and brew guide button.


To use: 
1. Copy this code. 
2. Place appropriate data on each line AFTER the `</strong>` and before the `<p>` Ex: `<p><strong>Roast: </strong>Dark Roast</p>`
3. Remove any `<p>`'s that are not necessary
4. IF the extra product info is not needed, delete from `<div class="extra-product-info">` down to the bottom of the file. Take care not to delete the `<div>` for the brew guides button! 
5. Make sure to use the "code mode" on the product info section on Shopify. On the description box, click the "Edit HTML" button on the right side (Has this symbol <>)
6. Paste code into the editor!



### Blank Template:
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

### Example with data filled in, missing fields, and no extra coffee details (Coffee: Blue Note Blend)
```
<p><strong>Description: </strong> Our house blend and a favorite among our regulars, this versatile coffee is great brewed your favorite way. We love it on v60, espresso and brewed coffee.</p>
<p><strong>Roast: </strong>A medium roast blend of Natural Ethiopian and Washed Central American coffees</p>
<p><strong>Notes: </strong>blueberry, chocolate, floral</p>
<p><strong>Organic: </strong>Yes</p>
<div class="product_brew-guides"><a href="https://well-coffeehouse.myshopify.com/blogs/brew-guides"> <i class="fas fa-coffee"></i> Brew Guides</a></div>
```

### Example with data filled in and some missing fields (Coffee: Brazil - São Jose, Anaerobic Red Honey)

```
<p><strong>Description: </strong>Although 40% of the world's coffee comes from Brazil, this coffee from Marcos Antonio
  de Freitas in São José shows that not all of them are created equal. He uses his passion to innovate this anaerobic
  red honey processed coffee cherry. This creative process brings out the plum, cherry and caramel notes you will taste
  in this special coffee. </p>
<p><strong>Process: </strong>Anaerobic Red Honey</p>
<p><strong>Notes: </strong>Plum, Cherry, Caramel</p>
<p><strong>Varietal: </strong>Mundo Novo</p>
<div class="product_brew-guides"><a href="https://well-coffeehouse.myshopify.com/blogs/brew-guides"> <i
      class="fas fa-coffee"></i> Brew Guides</a></div>
<div class="extra-product-info">
  <div class="product-dropdown"><button class="collapsible" type="button">Coffee Details</button>
    <div class="content">
      <p><strong>Region: </strong>Sul de Minas</p>
      <p><strong>Subregion/Town: </strong>Perdões</p>
      <p><strong>Farm/Coop/Station: </strong>Fazenda São Jose</p>
      <p><strong>Farm Size: </strong>320 hectares</p>
      <p><strong>Area Under Coffee :</strong>225 hectares</p>
      <p><strong>Harvest Months: </strong>April - September</p>
      <p><strong>Altitude: </strong>950 meters above sea level</p>
    </div>
  </div>
</div>
```
