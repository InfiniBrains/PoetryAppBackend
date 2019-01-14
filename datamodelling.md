author
-	id
-	name
-   pseudonym
-	borndate
-	bornlocation
-	bio
-	countries

location
-	id
-	name
-	geolocation

contentroot
-	id
-	authorid
-	locationid
-	datewriten
-   school
-   category

content
-	id
-	contentrootid
-	content
-	dateinserted
-	idiom
-	tags
-	submitedbyuserid

category
- id
- name
# fable, cite, chronicle, poem, haiku, 

poem
-	id
-	contentid
-	categories
-	school

school
-	id
-	name
-	datestart
-	dateend

analytics
-   contentrootid
-   date
-   hits 