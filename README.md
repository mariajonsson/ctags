# ccontent
A module for basic content management in Anax-MVC

Requires CDatabase to work (mos/cdatabase) [https://github.com/mosbth/cdatabase](https://github.com/mosbth/cdatabase).

## Getting started

Move the example file `basiccontent.php` to your Anax-MVC webroot folder to try the module. The package includes view templates needed by the `basiccontent.php` file. Move the files from  `cdatabase\view\content` to `app\view\content` in Anax-MVC. 

Before you can use CContent the database need to be configured, look at the CDatabase documentation.

### `ContentBasicController()`
`basiccontent.php` demonstrates some of the methods of the controller `ContentBasicController()`:  

* Setup database with test data, `setupPopulateAction()`
* See contents, `listAction()`
* Add new content, `addAction()` 

Before you can see contents or add new contents you need to set up the database with `setupPopulateAction` or `setupAction`. 

There is also functionality to view a single content post and to edit a post.

