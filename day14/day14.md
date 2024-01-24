<p> height and width properties are used to set the height and width of an element. </p>
<br>
<strong>max-width </strong> <p>property is used to set the maximum width of an element.</p>
<br>
<h2>The height and width properties may have the following values: </h2>
<br>
<strong>auto<strong><p> - This is default. The browser calculates the height and width </p>
<br>
<strong>length<strong><p> - Defines the height/width in px, cm, etc. </p>
<br>
<strong>%<strong><p> - Defines the height/width in percent of the containing block </p>
<br>
<strong>initial<strong><p> - Sets the height/width to its default value </p>
<br>
<strong>inherit</strong> <p> - The height/width will be inherited from its parent value</p>
<br>
<p>If you for some reason use both the width property and the max-width property on the same element, and the value of the width property is larger than the max-width property; the max-width property will be used (and the width property will be ignored).</p>

<p>height and width properties do not include padding, borders, or margins! They set the height/width of the area inside the padding, border, and margin of the element!</p>

<p>The margin property also affects the total space that the box will take up on the page, but the margin is not included in the actual size of the box. The box's total width and height stops at the border. </p>

<h2> The total width of an element should be calculated like this: </h2>

<p>Total element width = width + left padding + right padding + left border + right border </p>

<h2>The total height of an element should be calculated like this: </h2>

<p> Total element height = height + top padding + bottom padding + top border + bottom border <p>