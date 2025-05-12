# csci571-homework-6-server-side-scripting-using-python-flask-json-and-ebay-api-solved
**TO GET THIS SOLUTION VISIT:** [CSCI571 Homework 6-Server-side Scripting using Python Flask, JSON and eBay API Solved](https://www.ankitcodinghub.com/product/csci571-homework-6-server-side-scripting-using-python-flask-json-and-ebay-api-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91191&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI571 Homework 6-Server-side Scripting using Python Flask, JSON and eBay API Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Homework 6: Server-side Scripting using Python Flask, JSON and eBay API

1. Objectives

<ul>
<li>● &nbsp;Get experience with Python programming language and Flask framework.</li>
<li>● &nbsp;Get experience creating web pages using HTML, CSS, JavaScript, HTML DOM and
XMLHTTPRequest object
</li>
<li>● &nbsp;Get experience with eBay Finding API.</li>
<li>● &nbsp;Get experience using JSON format.
1.1 Cloud Exercise

• The backend of this homework must be implemented in the cloud on GCP using Python.

• See homework 5 for installation of Google Cloud platform.

• See the hints (section 3) at the bottom; a lot of reference material is given to you.

• For Python and Flask kickstart please refer to the Lecture slides on the class website.

• You must refer to the grading guidelines, the video, the specs and Piazza. Styling is graded this time and the points breakup is mentioned in guidelines.

2. Description

In this exercise, you are asked to create a webpage that allows users to search items for sale on eBay.com using their API, and the results will be displayed in a tabular format. Instructions on how to use the API are given in section 3.1. The user first opens a page as shown below in Figure 1, where he/she can enter a query in the keywords textbox.

Figure 1: Initial search page

Once the user has provided valid data (a keyword is required), your script will make a request to your web server providing it with the form data that was entered. You must use GET to transfer the form data to your web server (do not use POST, as you would be unable to provide a sample link to your cloud services). A python script using Flask will retrieve the data and send it to the eBay API Web
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Service “findItemsAdvanced”. The API call to eBay is done simply using a URL REST request. For example, if you are just searching for “harry potter” and you want to retrieve the results sorted by ascending price (i.e., from low to high price including shipping cost) in JSON format, the URL will be:

https://svcs.eBay.com/services/search/FindingService/v1?OPERATION- NAME=findItemsAdvanced&amp;SERVICE-VERSION=1.0.0&amp;SECURITY- APPNAME=YourEBayAppKey&amp;RESPONSE-DATA- FORMAT=JSON&amp;keywords=harry%20potter&amp;sortOrder=PricePlusShippingLowest

A sample result snippet of 2 results is shown below in Figure 2.

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 2. Results page

2.1. DESCRIPTION OF THE SEARCH FORM

The following is a brief description of the fields in the search form (see Figure 1) which you need to

implement in your homework.

1. Key Words: This is a text box, which enables the user to search for matching items by entering keywords. This must be a non-empty string. If the search button is clicked while this text box is empty, an alert should inform the user that this is a mandatory field (see Figure 3), and no query to the server should be performed.

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 3. Empty query

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
2. Price Range:

numbers [0.0, ∞). You must ensure that Minimum Price &lt;= Maximum Price and

MinimumPrice, Maximum Price &gt;=0.0. For specifying the price range,

minimum price &gt; maximum price, an error message should be displayed as shown in Figure

</div>
</div>
<div class="layoutArea">
<div class="column">
These are two boxes, displaying numeric values, which enable the user to

</div>
</div>
<div class="layoutArea">
<div class="column">
assign a price range for the matching items.

</div>
</div>
<div class="layoutArea">
<div class="column">
If the 4. An error message for negative price value should be displayed as shown in Figure 5.

</div>
</div>
<div class="layoutArea">
<div class="column">
only the lower price range or the higher price range, or both of them, or none of them.

</div>
</div>
<div class="layoutArea">
<div class="column">
3. Condition: These are

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 4. Incorrect Price Range

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 5. Negative Price Value

</div>
</div>
<div class="layoutArea">
<div class="column">
<ol start="4">
<li>Seller: Specifies if the user wants only items sold by a seller who accepts returns.</li>
<li>Shipping: Specify if only “free shipping” items should be returned; if only items available with expedited shipping should be returned or combination of both. Default is not specified which
means “any” filter.
</li>
<li>Sort By: This specifies the ordering of the results table, which can be one of:
<ol>
<li>Best Match – THIS IS THE DEFAULT</li>
<li>Price: highest first</li>
<li>Price + Shipping: highest first</li>
<li>Price + Shipping: lowest first</li>
</ol>
</li>
</ol>
The search form has two buttons:

1. SEARCH button: this button validates whether the user provided all the mandatory field (i.e.,

key words) and verifies the correctness of the provided data in the fields (the price range is valid). The validation should be implemented in a JavaScript function. Then, an HTTP

</div>
</div>
<div class="layoutArea">
<div class="column">
These can be positive integers or decimal

</div>
</div>
<div class="layoutArea">
<div class="column">
it is possible to assign

</div>
</div>
<div class="layoutArea">
<div class="column">
five checkboxes “New, Used, Very Good, Good, and Acceptable” which

</div>
</div>
<div class="layoutArea">
<div class="column">
enable the user to control the item condition retrieved in the results. The user can select one

</div>
</div>
<div class="layoutArea">
<div class="column">
of the options or a combination of them to search for items in specific conditions.

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
request is made to your web server in the cloud providing it with the form data that was entered. You need to use GET to transfer the form data as query/path parameters to the web server.

2. CLEAR button: This button must clear the result area, all text fields, uncheck all checkboxes and reset the “sort by” field to its default value mentioned above. The clear operation is done using a JavaScript function.

NOTE: In the video, you should notice the change in styling for the two buttons when hovering. Also, notice that the selected sort criteria in the Sort By filter is center aligned.

2.2. DISPLAYING RESULTS

The list of results should be displayed as shown in Figure 2 along with ta headline indicating the number of results, i.e. the total number of entries on eBay retrieved for a given keyword, and the corresponding filters. The headline is separated from the list of results by a horizontal line. Items are to be stacked vertically (1 item per row). Inside the item card, to the left, is the item’s display image. On the top right, the item title is displayed in bold. Below it, the Category (in which the item is tagged) is displayed in the second line, “condition” of the item is displayed in the third line and lastly the “Price” in USD is displayed. Additionally, if applicable, you must also indicate whether the item is top rated to the right of the Category field using the image topRatedImage.jpg.

NOTE: If any attribute is missing or empty or blank, do not display the item to the user.

If more than 3 articles are returned in the results, you should display the first 3 items along with the Show More button underneath. On clicking the button, a maximum of 7 more items (for a total of 10 items) should be displayed and the Show More button changes to Show Less as shown in Figure 6. After clicking the Show More button, all the items will be displayed and a Show Less button will be displayed. Clicking the Show Less button will again display just 3 results. Additionally, when the Show More button is clicked, the page should automatically scroll to the bottom and it should scroll to the top of the page when the Show Less button is clicked. The Show More and Show Less buttons should have the same styling as the clear and search buttons of the form. See the behavior in the video.

Figure 6: Show More and Show Less Buttons

In case the item does not contain images, the eBay server returns a default image with the URI as https://thumbs1.ebaystatic.com/ pict/04040_0.jpg. Replace this image with the Item Default Image given to you (See section 5, Images).

Additionally, the item image magnifies when the user hovers on the image and has a transition while magnifying, as shown in figure 7. See the video for the effect.

</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
Figure 7: Zoomed in image on mouse hover

The item is initially in the summary state as shown in Figure 7. The fields used from the JSON Response for creating the item summary card and the number of results headlines are shown in Table 1 below.

</div>
</div>
<div class="layoutArea">
<div class="column">
Item Information in the Card

Total Results Found Item’s image URL Item Title

Item Category tag

eBay product link for redirection Condition of the item

</div>
<div class="column">
Tags in eBay JSON response

paginationOutput-&gt;totalEntries searchResult-&gt;item-&gt;galleryURL searchResult-&gt;item-&gt;title searchResult-&gt;item-&gt;primaryCategory- &gt;categoryName searchResult-&gt;item-&gt;viewItemURL searchResult-&gt;item-&gt;condition- &gt;conditionDisplayName

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Item Top Rated Image (If the current listing is top rated for the given item)

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
if the value of searchResult–&gt;item- &gt;topRatedListing is true, display the image topRatedImage.jpg. You can find the image at URL Link

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Item Price

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
The price of the item is displayed in the format:

Price: $x (+ $y for shipping)

The item price value is read from searchResult- &gt;item-&gt;sellingStatus-&gt; convertedCurrentPrice

The shipping cost is read from searchResult- &gt;item-&gt;shippingInfo-&gt;shippingServiceCost

The shipping cost phrase (+ $YY for shipping) is mentioned if and only if the value of shippingServiceCost field is greater than ZERO

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Table 1. Summary Card information

Note: All the numeric values in the JSON response are strings and need to be converted into JavaScript Number type for comparisons.

Each summary card is clickable and results in additional information being displayed as shown in Figure 8 below.

</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
Figure 8: Detailed Item card

The mapping between the information populated in the expanded card result and the JSON object is shown in Table 2 below. For styling of the card, refer to Figure 8 and the video.

</div>
</div>
<div class="layoutArea">
<div class="column">
Item Information in the Result Card

Item image URL Item Title

Item Category

eBay product link for redirection Condition of the item

</div>
<div class="column">
Tags in eBay JSON response

searchResult-&gt;item-&gt;galleryURL searchResult-&gt;item-&gt;title searchResult-&gt;item-&gt;primaryCategory- &gt;categoryName searchResult-&gt;item-&gt;viewItemURL searchResult-&gt;item-&gt;condition- &gt;conditionDisplayName

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Item Top Rated Image (If the current listing is top rated for the given item)

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
if the value of searchResult–&gt;item- &gt;topRatedListing is true, display the image itemTopRated.jp. You can find the image at URL LINK

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Seller Accepts return?

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
searchResult-&gt;item-&gt;returnsAccepted is either true or false. If field is false, show “Seller does not accept returns” and “Seller accepts returns” otherwise.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Free Shipping available?

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
If the value of the tag searchResult–&gt;item- &gt;shippingInfo-&gt;shippingServiceCost is equal to 0.0, print “Free Shipping”. Otherwise, print “No Free Shipping”. (Refer video for styling)

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Expedited Shipping available?

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
searchResult-&gt;item-&gt;shippingInfo- &gt;expeditedShipping is either true or false. If the field is true, append “– Expedited Shipping available” to the Free Shipping status. (Refer Video for styling)

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Price

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
The price is displayed in the format:

Price: $20 (+ $3 for shipping)

The price value is read from searchResult-&gt; item-&gt;sellingStatus-&gt; convertedCurrentPrice

The shipping cost is read from searchResult-&gt; item-&gt;shippingInfo-&gt;shippingServiceCost

The shipping cost phrase (+ $$$ for shipping) is mentioned if and only if the value of shippingServiceCost is greater than ZERO

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Ships from Location

</div>
<div class="column">
searchResult-&gt;item-&gt;location

Table 2. Detailed Card Information

</div>
</div>
<div class="layoutArea">
<div class="column">
6

</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="layoutArea">
<div class="column">
In the expanded card, you must indicate, if applicable, if the seller accepts returns.

</div>
</div>
<div class="layoutArea">
<div class="column">
Shipping information about the item also needs to be displayed:

<ol>
<li>Whether it is a “Free Shipping” item;</li>
<li>Whether expedited shipping is available for that item;</li>
</ol>
In the last line of the details, the price of the item (+ $x for shipping, if applicable) is displayed in bold,

followed by the sender location for the item in italics.

At the top of the results, you should mention the total of the entries matching the search criteria and the key words used in the search (the headline containing the the number of results). An example of the result title is shown in Figure 2.

2.3. SAVING PREVIOUS INPUTS

In addition to displaying the results, your page should maintain the provided filter values while displaying the current results. For example, if one searches for “Free Shipping” items for “harry potter”, one should see what was provided in the search form and the corresponding results. Same goes for all fields and input types. It follows that you need to keep the whole search box/input fields and buttons, even while displaying results/errors. Also, the keyword text field should provide previous keywords searched as suggestions (default behavior for text fields but can be toggled to enable this feature).

2.4. NO RESULTS

In case where the eBay API returns no items for a specific keyword such as “alcnkajcsnkacnka”, you should display “No results found” or any similar message as shown in Figure 9.

Figure 9: An example when No Results is found

</div>
</div>
<div class="layoutArea">
<div class="column">
7

</div>
</div>
</div>
<div class="page" title="Page 8">
<div class="layoutArea">
<div class="column">
3. How to Use the eBay “findItemsAdvanced” API

3.1. HOW TO CREATE THE eBay App ID

To use any of the eBay APIs, you should first register for membership in the eBay Developer Program at https://developer.ebay.com/signin?tab=register. The activation of the account takes 1 business day so register early to avoid delays.

After registration, login into the developer portal and create an application with any title. Once you have a valid application title, complete the registration form by selecting individual as the account type. Then, create a “Production Keyset”. Do not create more than one Key Set (set of 3 keys, DEVID, AppID, CertID). When you have created your Key Set, your account page may look something like Figure 10 (ignore the “Sandbox Keys”)

Figure 10: How to Create an eBay App ID

Under the “Application Keys” section, “Production” sub-section, you’ll find your AppID. In Figure 10, the application ID is marked in red. When constructing the URL to call the eBay APIs, your Application ID should be provided as a value for the parameter SECURITY-APPNAME. Each AppID only allows 5000 API calls a day. Please ensure you do not exceed the daily usage limit. After reaching the limit, any subsequent calls will fail for 24 hours.

3.2 CONSTRUCTING URL FOR eBay API CALLS.

In this homework, we will use the eBay “findItemsAdvanced” API. A comprehensive reference about this API is available at:

http://developer.eBay.com/DevZone/finding/CallRef/findItemsAdvanced.html.

Table 3 shows the mapping between the search fields and the URL parameters to call the eBay API. Some of the search fields are handled through ItemFilter. The item filter is specified using two parameters: itemFilterName and itemFilterValue. The Condition parameter can take multiple values. The reference for the URL parameters can be found at:

https://developer.ebay.com/DevZone/finding/CallRef/extra/fnditmsadvncd.rqst.tmfltr.nm.html

</div>
</div>
<div class="layoutArea">
<div class="column">
8

</div>
</div>
</div>
<div class="page" title="Page 9">
<div class="layoutArea">
<div class="column">
Search Field

Key words

Sort by (A drop-down list displaying:

<ol>
<li>Best Match</li>
<li>Price: highest first</li>
<li>Price + Shipping: highest first</li>
<li>Price + Shipping: lowest first)</li>
</ol>
Price Range From

Price Range To

Seller – Returns Accepted

Shipping – Free Shipping

Shipping – Expedited shipping available

Condition (a set of check boxes: New, Used, Very Good, Good, and Acceptable)

</div>
<div class="column">
URL parameter in the API Call

The name of the query parameter is Keywords

sortOrder. The possible values are: 1. BestMatch

2. CurrentPriceHighest

3. PricePlusShippingHighest 4. PricePlusShippingLowest

The name of the item filter is MinPrice. The value of the filter is the value of “Price Range From” field. Values have to be decimal and greater than or equal to 0.0. Additional parameters to pass with this filter are paramName=Currency and paramValue=USD

The name of the item filter is MaxPrice. The value of the filter is the value of “Price Range To” field. Values have to be decimal and greater than or equal to 0.0. Additional parameters to pass with this filter are paramName=Currency and paramValue=USD

The name of the item filter is ReturnsAcceptedOnly. The possible values are true or false.

The name of the item filter is FreeShippingOnly. The value can be true/false.

The name of the item filter is ExpeditedShippingType. One of the allowed values is: Expedited. If checked, pass Expedited value else do not apply this filter in the API call.

The name of the item filter is Condition. This filter defaults to OR logic if multiple values are provided. The possible values are:

1. 1000 (means New)

2. 3000 (means Used)

3. 4000 (means Very Good)

4. 5000 (means Good)

5. 6000 (means Acceptable)

If no value is checked, do not apply this filter in the API call.

</div>
</div>
<div class="layoutArea">
<div class="column">
Table 3: Mapping between the search fields and the URL parameters

In addition to the parameters mentioned in the above table, there are five parameters which should be included in every call. The name of these parameters and their values are listed below:

● OPERATION-NAME=findItemsAdvanced

● SERVICE-VERSION=1.0.0

● SECURITY-APPNAME=YourEBayAppKey ● RESPONSE-DATA-FORMAT=JSON

● REST-PAYLOAD

</div>
</div>
<div class="layoutArea">
<div class="column">
9

</div>
</div>
</div>
<div class="page" title="Page 10">
<div class="layoutArea">
<div class="column">
Every item filter should have two parameters (name and value). When listing the filters, they should be indexed starting from ZERO. An Example of listing three parameters:

itemFilter(0).name=filter1NAME&amp;itemFilter(0).value=filter1Value&amp;itemFilter(1).name=filter2NAME&amp; &amp;itemFilter(1).value=filter2Value&amp;itemFilter(2).name=filter3NAME&amp;itemFilter(2).value=filter3Value

If the filter is assigned multiple values, the values should be mentioned in a list of parameters and the list of the values should be indexed from ZERO. For example, in order to filter items based on their Condition to be NEW or USED or Very Good can be written as:

itemFilter(X).name=Condition&amp;itemFilter(X).value(0)=1000&amp;itemFilter(X).value(1)=3000&amp;itemFilter( X).value(2)=4000

For more information about filters, you can read this page:

http://developer.ebay.com/DevZone/finding/CallRef/types/ItemFilterType.html

An example URL constructed from the parameters will look similar to:

https://svcs.ebay.com/services/search/FindingService/v1?OPERATION- NAME=findItemsAdvanced&amp;SERVICE-VERSION=1.0.0&amp;SECURITY- APPNAME=YourAppID&amp;RESPONSE-DATA-FORMAT=JSON&amp;REST- PAYLOAD&amp;keywords=iphone&amp;paginationInput.entriesPerPage=10&amp;sortOrder=BestMatch&amp;itemFilt er(0).name=MaxPrice&amp;itemFilter(0).value=25&amp;itemFilter(0).paramName=Currency&amp;itemFilter(0).par amValue=USD

In the example URL above, the paginationInput.entriesPerPage parameter can be used to reduce the number of items returned by the eBay API. This parameter is optional and if omitted, the eBay API will return a maximum of 100 items by default. You need to only display a maximum of 10 items on the web page but might need to request more items to ensure having 10 items even when some listings have to be removed due to missing fields or errors.

3.3 PARSING JSON RESULTS

To view a sample JSON response from the findItemsAdvanced API, just copy and paste the URL below and hit Enter in your Firefox browser.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
https://svcs.ebay.com/services/search/FindingService/v1?OPERATION-

</div>
</div>
<div class="layoutArea">
<div class="column">
NAME=findItemsAdvanced&amp;SERVICE-VERSION=1.0.0&amp;SECURITY-APPNAME=YourAPIKey&amp;RESPONSE-

</div>
</div>
<div class="layoutArea">
<div class="column">
DATA-FORMAT=JSON&amp;REST-

</div>
</div>
<div class="layoutArea">
<div class="column">
PAYLOAD&amp;keywords=iphone&amp;paginationInput.entriesPerPage=25&amp;sortOrder=BestMatch&amp;itemFilter(0).name

</div>
</div>
<div class="layoutArea">
<div class="column">
=MaxPrice&amp;itemFilter(0).value=25&amp;itemFilter(0).paramName=Currency&amp;itemFilter(0).paramValue=USD&amp;itemF

</div>
</div>
<div class="layoutArea">
<div class="column">
ilter(1).name=MinPrice&amp;itemFilter(1).value=10&amp;itemFilter(1).paramName=Currency&amp;itemFilter(1).paramValue=

</div>
</div>
<div class="layoutArea">
<div class="column">
USD&amp;itemFilter(2).name=ReturnsAcceptedOnly&amp;itemFilter(2).value=false&amp;itemFilter(3).name=Condition&amp;item

</div>
</div>
<div class="layoutArea">
<div class="column">
Filter(3).value(0)=2000&amp;itemFilter(3).value(1)=3000

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
Please note that the SECURITY-APPNAME parameter is developer-specific as described in section 3.2. Figure 11 below is an example of the high level JSON response of the findItemsAdvanced API.

</div>
</div>
<div class="layoutArea">
<div class="column">
10

</div>
</div>
</div>
<div class="page" title="Page 11">
<div class="layoutArea">
<div class="column">
Figure 11: High-level successful response JSON

In Figure 11, the item tags have been minimized. Each value for a field is enclosed inside an array in the JSON response. The mandatory requirement for the homework is to reduce the number of items returned to 10 and only those items that have all required fields be sent to the web page. You can send the additional fields which are not used by the webpage as well in your response. However, the preferred approach will be to parse the Ebay API JSON for validation and retrieval of data and then create a new JSON in python that will only contain the required information.

The case where no results are found is shown in Figure 12 below. You can then query the value of paginationOutput-&gt;totalEntries. If the value of totalEntries is zero, display “no results were found” in the results area.

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 12: No Results JSON

The item tags from which you should extract information for display are given in Table 1. Your Python program should parse the resulting JSON and extract the information for all items.

</div>
</div>
<div class="layoutArea">
<div class="column">
11

</div>
</div>
</div>
<div class="page" title="Page 12">
<div class="layoutArea">
<div class="column">
All information specific to an item will be within its item element as shown above. The root “item” tag for will be findItemsAdvancedResponse-&gt;searchResult-&gt;item[index].

4. Hints

● For Flask/Python Backend, refer:

o For setting up a server – https://flask.palletsprojects.com/en/1.1.x/

o For making requests from Python to the eBay APIs, use the Requests module –

https://requests.readthedocs.io/en/master/

● Styling hints

o Button styling – https://www.w3schools.com/css/css3_buttons.asp o Shadow on a card –

https://www.w3schools.com/howto/tryit.asp?filename=tryhow_css_cards2 o For close button – https://wesbos.com/times-html-entity-close-button

<ul>
<li>● &nbsp;Flask/Python
<ol>
<li>Flask should be used to implement RESTful services to eBay</li>
<li>Flask templates should not be used</li>
<li>Flask send_static_file() or send_from_directory() should be used to send “static” HTML,
CSS and JavaScript
</li>
</ol>
</li>
<li>● &nbsp;Google Cloud Platform (GCP)</li>
</ul>
1. Follow the steps mentioned in Homework 5 to deploy your web application on GCP.

5. Images

eBay Logo: https://www.csci571.com/hw/hw6/images/eBayLogo.png

Top Rate Image: https://www.csci571.com/hw/hw6/images/topRatedImage.png Item Default Image: https://www.csci571.com/hw/hw6/images/ebay_default.jpg Redirect: https://www.csci571.com/hw/hw6/images/redirect.png

</div>
</div>
</div>
<div class="page" title="Page 13">
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
</div>
