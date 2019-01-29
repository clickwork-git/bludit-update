# bludit-update
Variables that have changed in Bludit


|2.3.4                      |3.0.0                        |
|---------------------------|-----------------------------|
|$Language	                |$L                           |
|($pages as $Page)          |($content as $page)		      |
|$Page                      |$page				                |
|$staticPages as $staticPage|$staticContent as $staticPage|
|$Site                      |$site                        |				
|$tags                      |$pageTags	                  |		
|$Url                       |$url				                  |
|$page->status()            |$page->type()			          |
|                           |$page->contentBreak();       |
|array_shift($pages)        |array_shift($content)		    |
|                           |dbPages                      |
|$this->getDbField()        |$this->getValue('')		      |
|Paginator::prevPageUrl()   |Paginator::previousPageUrl()	|


