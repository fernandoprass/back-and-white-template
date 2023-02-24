# Available Tags

Tags are used to show dinamic data in the site pages, they are used with the follow format: `{@origin.name}`. For example, `{author.name}` shows the name of the author 


Kennis has tags three different origns: site, author, and content (what can be a page or a post).

## Site

**Site** provide information thats came from the project configuration file (for more information see [ADD LINK TO KENNIS DOCUMENTATION]. The only exceptions are the tags `deployed`, which show the date when the page was generated. and `index` which references to the index page take into account the language.  

| Site Tags        | Index |Blog - Post List|Blog - Archive| Blog - Categories|Blog - Tags|Blog - Posts|
|:-----------------|:-----:|:--------------:|:------------:|:----------------:|:---------:|:----------:|
| @site.baseUrl    |X      |X               |X             |X                 |X          |X           |
| @site.deployed   |X      |X               |X             |X                 |X          |X           |
| @site.description|X      |X               |X             |X                 |X          |            
| @site.title      |X      |X               |X             |X                 |X          |            |
| @site.keywords   |X      |X               |X             |X                 |X          |            |
| @site.language   |X      |X               |X             |X                 |X          |X           |
| @site.index      |X      |X               |X             |X                 |X          |X           |
| @site.subtitle   |X      |X               |X             |X                 |X          |            |
| @site.googleAnalyticTrackingId|X      |X               |X             |X                 |X          |X           |


## Author

Author provides infomation about the author of the site, also the tag site, it came from the project configuration file.

| Author Tags      | Index |Blog - Post List|Blog - Archive| Blog - Categories|Blog - Tags|Blog - Posts|
|:-----------------|:-----:|:--------------:|:------------:|:----------------:|:---------:|:----------:|
| @author.avatar   |X      |X               |X             |X                 |X          |X           |
| @author.bio      |X      |X               |X             |X                 |X          |X           |
| @author.email    |X      |X               |X             |X                 |X          |X           |
| @author.location |X      |X               |X             |X                 |X          |X           |
| @author.name     |X      |X               |X             |X                 |X          |X           |
