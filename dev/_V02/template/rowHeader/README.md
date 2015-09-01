#rowHeader template

###Contains 3 elements:

1. Title (txt or images - optional)
2. row - line of text
3. and CTA - call to action (txt or images - optional)
All this element are optional (you must set to false if you want to not be display)

####note variables:

1. set the *trakingSource* inside the **trakingSource** variable
2. *images* are optional for header and for CTA (call to action). If you set the images to false it will display only the text inside **rowHeaderTitle** variable
	images format name is:
		**name_en.jpg** (you must put only the **"name"**)
		ex: if the image name is **promo_02_en.jpg**, you must put only **"promo_02"**
3. you must put the link for any language version inside **linkCTA** variable
4. the text from header is inside **rowHeaderTitle** variable
5. the line of text is inside **rowHeaderRow** variable
6. and copy of CTA is inside **ctaCopy**

###In two version (you can set this in *colorScheme* variable)

1. **dark** scheme
2. **light** scheme