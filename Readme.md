<!-- default file list -->
*Files to look at*:

* [Form1.cs](./CS/S131055/Form1.cs) (VB: [Form1.vb](./VB/S131055/Form1.vb))
* [Program.cs](./CS/S131055/Program.cs) (VB: [Program.vb](./VB/S131055/Program.vb))
<!-- default file list end -->
# How to implement the word wrap functionality in the ListBoxControl


<p>To implement this feature, you need to handle the MeasureItem event and calculate the required height based on the items text and on the client size. Then, within the DrawItem event handler, you can manually draw item's content using the DrawString method of our TextUtils.</p>

<br/>


