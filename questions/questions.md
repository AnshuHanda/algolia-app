*Question 1*: Hello,

I'm new to search engines, and there are a lot of concepts I'm not educated on. To make my onboarding smoother, it'd help if you could provide me with some definitions of the following concepts:

Records 
Indexing 

I'm also struggling with understanding what types of metrics would be useful to include in the "Custom Ranking." 
Cheers, George

***ANSHU: Please find below the required definitions.
Records: This is basically a set of key-value pairs called attributes. Each individual product in your catalog is having few properties mapped to it like "title", "product Id", "price", "image URL", "product page URL". Set of all these properties makes a single record.
Indexing: Indexing is a process of creating the collection of records which are uploaded to the system at the same time. You can create multiple indices that contain different set of objects.
If you would like to rank your products in a specific order, you can add business-metric attributes like "number of orders", "ratings", "likes" which can be used to influence the existing ranking formula. These attributes should be either in BOOLEAN or NUMERIC format.***


*Question 2*: Hello,

Sorry to give you the kind of feedback that I know you do not want to hear, but I really hate the new dashboard design. Clearing and deleting indexes are now several clicks away. I am needing to use these features while iterating, so this is inconvenient.
Regards, Matt

***ANSHU: Thank you for sharing your feedback regarding the dashbaord UI. But just to help you with your concern, there are multiple ways for clearing or deleting indexes from the system. 
	1. If the records share some common attributes, you can use "Delete By" method to bulk delete multiple records at the same time.
	2. In case of unrelated records, you can use "Custom batch" method to bulk update/delete multiple records at the same time.***


*Question 3*: Hi,

I'm looking to integrate Algolia in my website. Will this be a lot of development work for me? What's the high level process look like?
Regards, Leo

***ANSHU: We have an in house Search UI kit, we can be used if you dont want to put too much development hours from your end. This kit has predefined UI templates for search experience which will require very minimal integration effort. 
Otherwise, we have set of SDKs and libraries which can be used to build a search interface in your front-end application.***