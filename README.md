# Tools-Docs
Informational guides for users about all the existing tools
# USER GUIDE TO USE BUY BOX API 
### 1.AMAZON Buy Box eligibility factors:
Sellers can’t just sign up and become eligible to appear on the Buy Box. Amazon considers a variety of factors before approval, although the first four factors listed below.
  *	Fulfilment method.
  * Landed price.
  * Shipping time.
  * Feedback rating.
  * Seller metrics.
#
are the most influential. 
### 2.Why this tool:
Buy Box tool is used to help us to display our products in higher priority when customer search for some products in our listing and also shows our company name in seller and sold by.
Before this tool, they manually updated the prices to get Buy Box and It takes weeks to complete the work but now, the work became easy and time saving and now, they can do more work in less time.

###3.How it works:
The Buy Box API will take no. of ASINS and produces the table of products data. Now download the data using download button. Now open this downloaded file in Excell sheet and apply the filter to get only Buy Box FALSE data. So that we can update pricing rule to this FALSE data to achieve **BUY BOX**. 

### 4.How to use:
* **Step-1:-**  Firstly, open Buy Box API and  paste the ASINS data in the input field and click submit button.
![My Image](1.png "My Image")
* **Step-2:-**  It will produce the list of products , we need to download the file using download file button.
![My Image](2.png "My Image")
* **STEP-3:-** Search for the Buy Box FALSE products in search field and copy the particular ASIN.
![My Image](3.png "My Image")
* **Step-4:-**  Now , open Amazon Seller central and paste the ASIN and reduce the price , apply coupons , update handling time or Automate the pricing to achieve  Buy Box.

> [!NOTE]
>We should be careful while entering Min and Max prices otherwise it will return **FIXED PRICE ERROR**.

### 5.Any Updates (If required):
1.	Some products are displaying FALSE in Is Buy Box field even though the products are already in Buy Box (TRUE).

#

# USER GUIDE TO USE SIMPLE DOT COM TOOL
### 1.Why this Tool:
This Simple Dot Com tool is used to upload the products in bulk, this tool makes operations department’s work easy by providing all the related fields which are required to upload the products in amazon seller central.
Before this tool, they used to enter data manually.

### 2.How it works:
It takes bulk ASINS as input and provides all related data.

### 3.How to use it:
* **Step-1:-** Open Simple Dot Com and paste the listing data ASINS which we want to bulk upload in amazon.in and click submit button.
![My Image](s1.png "My Image")
* **Step-2:-** Simple Dot Com program  automatically produces the output excel sheet which contains ASINS and their related fields including PRICE converted to Indian currency that used to upload the data in Amazon seller central.
![My Image](s2.png "My Image")
* **Step-3:-** Now, download this sheet and Copy only required fields like ASIN , SKU , TITLE , BRAND NAME ,PRICE and WEIGHT data.
* **Step-4:-** And paste these 6 fields in Bulk formula sheet and the formula  will produce SALE PRICE and MRP which are also important to upload products using FLAT file.
![My Image](s3.png "My Image")
* **Step-5:-** Open Amazon’s FLAT file provided by Amazon and Paste the data. And save the file with txt (tab delimiter) extension.
![My Image](s4.png "My Image")
* **Step-6:-** Now, Open amazon seller central and upload this FLAT file and click submit products.
![My Image](s5.png "My Image")
* **Step-7:-** Then Amazon itself automatically uploads this bulk data in Amazon.in.
* **Step-8:-** Now, this data is visible to our amazon customers and shows seller as Peach imports.

### 4.Any Updates (If required):

