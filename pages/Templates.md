- Templates allow you to quickly use often used content types. You define a template block once, and can then use it in any other page or block.
- **USAGE**
	- To create a template
		-
		  1. Right click a block bullet and select `Make template`, or 
		  2. Create a new page and add a page-level [[property]] `template: myTemplate`
		- You can choose to include the parent block.
		-
		  #+BEGIN_TIP
		  It is easiest to use a single page to contain _all_ of your templates, and then have each template be a different block.
		  #+END_TIP
	- To use a template, use the `/Template` [[command]]
	- To update a template, simply change the content of the original template page.
	  #+BEGIN_TIP
	  Updates to a template page are not propagated to the instances where you have used the template.
	  #+END_TIP
	- To delete a template, simply remove the `template::` property.
	  #+BEGIN_TIP
	  Deleting a template page will not delete or modify any of the instances where you have used the template.
	  #+END_TIP
-
  #+BEGIN_WARNING
  Templates simply copy text. They cannot contain any advanced logic.
  #+END_WARNING
- Templates support [[Dynamic Variables]].