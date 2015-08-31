#rowHeader template

###block witch contains 3 elements:

1. Header (txt or images - optional)
2. One line of copy
3. Call to action

###variables:

1. set the *trakingSource* inside the **trakingSource** variable
2. *images* are optional for header and for CTA (call to action). If you set the images to false it will display only the text inside **rowHeaderTitle** variable
	images format name is:
		**name_en.jpg** (you must put only the **"name"**)
		ex: if the image name is **promo_02_en.jpg**, you must put only **"promo_02"**
3. you must put the link for any language version inside **linkCTA** variable
4. the text from header is inside **rowHeaderTitle** variable
5. the line of text is inside **row01** variable
6. and copy of CTA is inside **ctaCopy**