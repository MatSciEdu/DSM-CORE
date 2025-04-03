# DSM-CORE
Data Science for Materials - a Collection of Open Resources for Education

The DSM-CORE repository is an assembly of teaching materials for applied data science and machine learning in the field of materials science. As many groups are developing similar courses and materials we hope to facilitate sharing of materials and ideas by providing an easy place to upload new content and search through past materials. Note that the materials themselves are not hosted here and therefore contributors are asked to provide a brief description following the included template and links to their own hosting platform of choice. After the initial creation of the resource here, there should be minimal to no future updates that are needed unless the content changes drastically and the initial description and tags no longer match.

# Goals
1. Easy maintenance. Information provided here should be a general overview to give users an idea of what is the content, it's scope, and structure.
3. Everything should link out to where it is being maintained elsewhere with a permanent link. Periodically, resource maintainers will check for stale links and reach out for an update.

# Contribute by creating a new resource ".md" file from the template
These instructions assume you are purely interacting through the github website interface and don't require installing git or working with any seperate tools. If you are familiar with the git workflow the TLDR is you will fork the repository, commit your own .md file to your forked repository in the _resources directory, then submit a pull request to merge back into the main branch that is rendered on the website.

1. Download the [Template](https://github.com/MatSciEdu/DSM-CORE/blob/main/template-resource.md) which is a markdown file that gets processed into the resource webpage. It is a text file and can be edited with any text editor of your choice.
2. consider opening and following along with an [existing resource](https://matsciedu.github.io/DSM-CORE/resource-collection) to get a sense of what might be useful to include.
3. Fill in the main sections by replacing every UPDATE tag with your information. Keep any surrounding formatting such as square brackets, commas, astrisks, etc. as they help create a consistent style. Note that any links should ideally be to locations where you aim to maintain the materials and users might automatically see updates.  
Here are a few resources that might be useful for formatting in markdown:  
[basic markdown syntax](https://markdownguide.offshoot.io/basic-syntax/)  
[And more complex syntax](https://www.markdownguide.org/extended-syntax/)  
[And the Specific Style layout that is used](https://pages-themes.github.io/leap-day/)
4. Save the file as: yourlastname-shortitle.md
5. Create a Fork of the repository using the "Fork" button at the top right of the repository page
6. Navigate to the _resources directory in your new fork and select "Add File" -> "Upload Files" and upload your ".md" file. 
7. Commit your upload using the "Commit Changes" button.
8. Your repo should now say "1 commit ahead...", select "Contribute" -> "Open Pull Request". Fill in an informal title that identifies the request, then submit the pull request. A resource maintainer will check that everything looks correct and accept the update.
9. Once you get a confirmation that your pull request has been merged, check to verify that your resource is showing up correctly.
10. If you need to make any edits you can edit your file directly via the webpage on your forked branch and submit another pull request.

# [View Resource Collection](https://MatSciEdu.github.io/DSM-CORE/resource-collection)  
<br/><br/>
## Search Resource Collection
<form action="{{ site.baseurl }}/search.html" method="get">
  <label for="search-box">Search</label>
  <input type="text" id="search-box" name="query">
  <input type="submit" value="search">
</form>
<br/><br/>
## Support
This resource  supported by the National Science Foundation under Grants No. 2017072 & 2334411 . Any opinions, findings, and conclusions or recommendations expressed in this material are those of the author(s) and do not necessarily reflect the views of the National Science Foundation. 
