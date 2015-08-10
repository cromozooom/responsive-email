# Responsive-email

**[sample fiore](https://rawgit.com/cromozooom/responsive-email/master/files/index_fiorentina.html "fiorentina")**

**[sample lazio](https://rawgit.com/cromozooom/responsive-email/master/files/index_lazio.html "lazio")**

**[sample f4u](https://rawgit.com/cromozooom/responsive-email/master/files/index_f4u.html "f4u")**

___

## workflow

![hard stuff](https://rawgit.com/cromozooom/responsive-email/master/icons/legenda.jpg "skils you need")
###!!!! modify only jade file - and use **default** template !!!!

1. **Upload images on server!**
2. Open **PREPROS**
3. Download and open "files" folder in **SUBLIME TEXT**
4. Create copy of **"index.jade"** & rename with your f....dot jade name :)
5. **select and order** your content blocks (see the section: "include some F..... blocks")

___

####!!!! make use of [this file](https://goo.gl/ljfWBR) to !!!!

- Replace the **variable** inside included file

** Pay attention to Traking code **
![tracking code](https://rawgit.com/cromozooom/responsive-email/master/icons/traking.jpg "skils you need")

** CTA explain **

Two type of cta with or without **Price**

1. without price (- var buttonType 	= "01")
2. with price (- var buttonType 	= "02")

![CTA](https://rawgit.com/cromozooom/responsive-email/master/icons/cta_explain.jpg "CTA")

___


####!!!! go to html file !!!!

- After you finish to make the replacement go to INLINE TOOL and copy paste your F......html file

####!!!! go to css file to... [inline CSS](http://templates.mailchimp.com/resources/inline-css/) !!!!

- Insert responsive component from my file (/assets/css/style_col.css)


#include some F..... blocks

(remember to make content for IT / EN)

___

##include_heroImageHeader

![Hero Image](https://rawgit.com/cromozooom/responsive-email/master/icons/heroImage.jpg "Hero Image")

* image (img)
* title (txt)
* ctaLink (txt)

___

##include_singleCTA

![Single CTA](https://rawgit.com/cromozooom/responsive-email/master/icons/singleCTA.jpg "Single CTA")

you can use only one from this 3 elements:
* title (txt)
* subtitle (txt)
* call to action (txt)

___

##include_singleCTA

![Hero Image Header](https://rawgit.com/cromozooom/responsive-email/master/icons/heroImageHeader.jpg "Hero Image Header")

you can use only one from this 3 elements:
* header (img)
* call to action (txt)
* image (img)

___

##include_coupon

![coupon](https://rawgit.com/cromozooom/responsive-email/master/icons/coupon.jpg "Coupon")

* couponCopy (txt)
* Coupon (txt)

___

##include_cowntDown

**is in progress - wee need some files up to php server (now are available only on solopx server)**

![Cownt Down](https://rawgit.com/cromozooom/responsive-email/master/icons/cowntDown.jpg "Cownt Down")

* Cownt Down Copy (txt)
* Cownt Down Data (txt)

___

##include_2prod

![2 prod](https://rawgit.com/cromozooom/responsive-email/master/icons/2prod.jpg "2 prod")

**!!!!! make use of [this file](https://goo.gl/ljfWBR) to !!!!!**

___

##include_3prod

![3 prod](https://rawgit.com/cromozooom/responsive-email/master/icons/3prod.jpg "3 prod")

**!!!!! make use of [this file](https://goo.gl/ljfWBR) to !!!!!**

___

##include_2banner_a

![2banner_a](https://rawgit.com/cromozooom/responsive-email/master/icons/2banner_a.jpg "2banner_a")
___

##include_ourBrand

![ourBrand](https://rawgit.com/cromozooom/responsive-email/master/icons/ourBrand.jpg "ourBrand")

___

##include_linkListA

![hard stuff](https://rawgit.com/cromozooom/responsive-email/master/icons/sublime_red.jpg "dificult for sublime user")
![##include_linkListBinclude_linkListA](https://rawgit.com/cromozooom/responsive-email/master/files/images/fiorentina/include_linkListA.jpg "include_linkListA")

![hard stuff](https://rawgit.com/cromozooom/responsive-email/master/icons/sublime_red.jpg "dificult for sublime user")
![include_linkListB](https://rawgit.com/cromozooom/responsive-email/master/files/images/fiorentina/include_linkListB.jpg "include_linkListB")
___

###### note
- PREPROS* aka "big Brother" - compila i file *.jade to *.HTML)
- SUBLIME Text 2
	- jade plugin

- CSS Inliner Tool:
	- http://templates.mailchimp.com/resources/inline-css/
	- http://zurb.com/ink/inliner.php
