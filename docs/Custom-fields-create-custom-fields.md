# How to create Custom Fields?



<div class="alert alert-warning">
<strong><i class="glyphicon glyphicon-warning-sign"></i> </strong> The maximum number of Custom Fields you can have in your website is <strong><u>65</u></strong>!
</div>

Content:
-   Create New Field
-   Edit Custom Field
-   Tricks

**The maximum number of Custom Fields you can have in your website is  **65**!**

Now there are  **3 types of fields**  that can be added to advertisements.

1.  **Standard**: mandatory and not changeable.

## **Title, Category, Description.**

2.  **Optional**: they are part of the open-classifieds. You have the possibility to turn them on/off

## **Phone, Website, Location, Address, Price, Captcha, Upload file.**

3.  **Custom:**  Fully customizable.


## Create New Field

To create a new field, go to  **Admin Panel**, press  **Classifieds**  select  **Custom Fields**  option.

Then click  **New Field**  button on the right corner.

![custom-fields1](https://user-images.githubusercontent.com/55290441/80696889-c6bffe00-8ae0-11ea-9269-b9a488e8ef58.png) 


This is a  **New Custom Field**  screen. There are 10 options in total.

1.  **Name**: give a name to field.
2.  **Label**: will appear in the form of “Post new ad”, “Edit ad”, and “Advanced search”.
3.  **Tooltip**: assign a text to the custom field tooltip.


## *4. **Type**:*

    
    1.  _Text 256 chars_  (standard input field, string)  
    2.  _Text_  (textarea field, string)  
    3.  _Text BBCode_  (textarea field with bbcode, formats  [BBCode](https://www.bbcode.org/)  tags) 4.  _Number_  (small integer number)  
    5.  _Number Decimal_  (floating point number)  
    6.  _Money_  (formats number to money)  
    7.  _Date_  (date picker, with plugin)  
    8.  _Select_  (select field)  
    9.  _Radio_  (radio buttons)  
    10.  _Checkbox_  (checkbox buttons)  
    11.  _Checkbox Group_  (multiple checkbox buttons)  
    12.  _Email_  (validates email input and creates email link)  
    13.  _Country_  (creates a dropdown menu with all the countries included)  
    14.  _URL_  (creates a link)  
    15.  _Video_  (uploads a video to Cloudinary and embeds the video)  
    16.  _File Dropbox_  (attaches a file from Dropbox and creates a link)  
    17.  _File Google Drive_  (attaches a file from Google Drive and creates a link)  
    

## 5. **Values**:

Note: It only appears to select and for the radio option.

To create values,write them down followed by comma (e.g. Paris, London, Madrid, Others).

## 6. **Categories:**

 the category that the New Custom Field should be applied to.

( see:  [Integrated custome fields into selected categories](Custom-fields-how-to-integrate-your-custom-field-into-selected-categories.md) )

## 7. **Required**

: this will make it a required field needing validation.

## 8. **Searchable**:

 this makes the field searchable.It will appear in Advanced searchs too.

## 9. **Admin privileged**

: this field can be seen and edited only by the admin.

## 10. **Show listing**:

Users will see the custom field in listings view without having to enter the ad.

Once you have written down all the required information, click  **Create**. New field is created and added to database, and it will appear in Post new ad, Edit ad and Advanced search.

### Edit Custom Field

While editing,  **Name**  and  **Type**  **fields**  will become disabled. In case you want to change them, you will have to delete this custom field and start over. This is to prevent messing up with the DataBase.

**Just for your information, the rest of the options are still open to edit and add.*

*Note that custom fields are available only on the sites hosted on  [Yclas.com](https://yclas.com/)  and on  [Yclas Self-Hosted Pro](https://selfhosted.yclas.com/themes/yclas-self-hosted-pro.html)*.


