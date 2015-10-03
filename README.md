# ctags
A module for tags in Anax-MVC

Requires CDatabase to work (mos/cdatabase) [https://github.com/mosbth/cdatabase](https://github.com/mosbth/cdatabase).

To install with Composer and Packagist, add cdatabase and ccontent to your composer.json file in Anax. 

    "require": {
        "php": ">=5.4",
        "meax/ctags": "dev-master",
        "mos/cdatabase": "dev-master"
    },
    
Before you can use Tags the database need to be configured, look at the CDatabase documentation.

## Getting started

Move the example file `basictags.php` to your Anax-MVC webroot folder to try the module. The package also includes view templates needed by the `basictags.php` file. You need to move the files from  `cdatabase\view\tags` to `app\view\tags` in Anax-MVC. 

### `TagBasicController()`
`basiccontent.php` demonstrates some of the methods of the controller `ContentBasicController()`:  

* Setup database with test data, `setupPopulateAction()`
* See contents, `listAction()`
* Add new content, `addAction()` 

Before you can see contents or add new contents you need to set up the database with `setupPopulateAction` or `setupAction`. 

There is also functionality to view a single content post, `idAction($id)` and to edit a post `updateAction($id)`.

