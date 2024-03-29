<a href="https://war.ukraine.ua"><img style="height: auto; max-width: 1920px; width: 100%;" src="images/war.png" alt="russia invaded Ukraine"></a><br>
<a href="https://bank.gov.ua/en/news/all/natsionalniy-bank-vidkriv-spetsrahunok-dlya-zboru-koshtiv-na-potrebi-armiyi"><img style="height: auto; max-width: 1920px; width: 100%;" src="images/support-Ukraine.png" alt="support Ukraine"></a>

# Prestashop Snippets Tools README

Prestashop snippets tools for 1.6 and 1.7 versions.<br>
This extension will help you faster to make common using snippets.

PHP snippets to help you be more productive when developing in PHP

Support `tab` to previous/next slug.

<details>
<summary>Snippets PHP</summary>

-   p:ajaxMethod => Ajax Call Your Method
-   p:ajaxAdminController => Ajax Call Your Admin Controller Code
-   p:ajaxFrontController => Ajax Call Your Front Controller Code
-   p:dump => dump('');
-   p:vdump => var_dump('');
-   p:printr => print_r('');
-   p:getIsset => Checks if a key exists either in $\_POST or $\_GET Tools::getIsset('');
-   p:getval => Tools::getValue('');
-   p:getAllValues => Get all values from $_POST/$\_GET. Tools::getAllValues();
-   p:redirectAdmin => Redirect user to another page (using header Location) Tools::redirectAdmin($url);
-   p:redirectLink => Redirect URLs already containing PS_BASE_URI Tools::redirectLink($url);
-   p:redirect => Redirect user to another page Tools::redirect($url);
-   p:token => Give a admin token Tools::getAdminTokenLite('<admin_controller_name>');
-   p:clean => Allows to display the text without HTML tags and slashes
-   p:userBrowser => Get user browser
-   p:userPlatform => Get user platform
-   p:boolVal => Bool Value
-   p:phpVer => Identify the version of php
-   p:camelCaseToKebabCase => Converts SomethingLikeThis to something-like-this
-   p:toUnderscoreCase => Converts SomethingLikeThis to something-like-this
-   p:toCamelCase => Translates a string with underscores into camel case (e.g. first_name -> firstName)
-   p:simplexml_load_file => Function simplexml_load_file()
-   p:class => Create a Prestashop object model sample !
-   p:module => Create a Prestashop Module sample !
-   p:assign => Give a $this->context->smarty->assign(array());
-   p:mail_send => Give a complete Mail::send() call
-

### Functions with PHPStorm

-   As you can see, I add new functions , references by PHPStorm.

| Shortcut | Function                      |
| -------- | ----------------------------- |
| \_c      | build construct method        |
| eco      | echo                          |
| fore     | foreach                       |
| forek    | foreach with key              |
| inc      | include                       |
| inco     | include_once                  |
| prif     | build private method          |
| prisf    | build private static method   |
| prof     | build protected method        |
| prosf    | build protected static method |
| pubf     | build public method           |
| pubsf    | build public static method    |
| rqr      | require                       |
| rqro     | require_once                  |
| thr      | throw new...                  |

<br>

### php snippets

| Shortcut | Output                         |     |     |     |     |     |     |
| -------- | ------------------------------ | --- | --- | --- | --- | --- | --- | --- |
| `$_`     | `$_COOKIE['...']`              |     |     |     |     |     |     |     |
| `$_`     | `$_ENV['...']`                 |     |     |     |     |     |     |     |
| `$_`     | `$_FILES['...']`               |     |     |     |     |     |     |     |
| `$_`     | `$_GET['...']`                 |     |     |     |     |     |     |     |
| `$_`     | `$_POST['...']`                |     |     |     |     |     |     |     |
| `$_`     | `$_REQUEST['...']`             |     |     |     |     |     |     |     |
| `$_`     | `$_SERVER['...']`              |     |     |     |     |     |     |     |
| `$_`     | `$_SESSION['...']`             |     |     |     |     |     |     |     |
| `r`      | `return;`                      |     |     |     |     |     |     |
| `dd`     | `dd(...)`                      |     |     |     |     |     |     |
| `trt`    | `trait ... {`                  |     |     |     |     |     |     |
| `?=`     | `<?= ... ?>`                   |     |     |     |     |     |     |
| `c`      | `class ... {`                  |     |     |     |     |     |     |
| `cc`     | `class ... {` _w/ constructor_ |     |     |     |     |     |     |

_As much as possible I try and make the ... be where your cursor ends up._

<br>

### Magic constants

| Shortcut | Constant          |
| -------- | ----------------- |
| \_l      | \_\_LINE\_\_      |
| \_f      | \_\_FILE\_\_      |
| \_d      | \_\_DIR\_\_       |
| \_fun    | \_\_FUNCTION\_\_  |
| \_cl     | \_\_CLASS\_\_     |
| \_t      | \_\_TRAIT\_\_     |
| \_m      | \_\_METHOD\_\_    |
| \_n      | \_\_NAMESPACE\_\_ |
| \_cn     | ClassName::class  |

</details>

<details>
<summary>Snippets SQL in PHP</summary>

-   p:sqlDb => $db = Db::getInstance();
-   p:sqlDb1 => $db = Db::getInstance(_PS_USE_SQL_SLAVE_);
-   p:prefix => Get Data base prefix _DB_PREFIX_
-   p:prefix1 => Get Data base prefix Db::getInstance->getPrefix();
-   p:sqlQuery => Show an instance of DBQuery
-   p:sqlExecute => Prestashop DB execute function
-   p:sqlExecuteS => Prestashop DB executeS function
-   p:sqlRow => Give a Db::getInstance()->getRow($sql);
-   p:sqlVal => Give a Db::getInstance()->getValue($sql);
-   p:sqlInsert => SQL prestashop insert into
-   p:sqlInsert1 => SQL insert into 1
-   p:sqlInsert2 => SQL insert into 2
-   p:sqlUpdate => SQL update
-   p:sqlDelete => SQL prestashop delete
-   p:sqlDelete1 => SQL delete
-   p:sqlGetLastId => SQL returns the ID created during the latest INSERT query
-   p:sqlAffectedRows => SQL returns the number of lines impacted by the latest UPDATE or DELETE query
-   p:sqlGetMsgError => SQL returns the latest error message, if the query has failed
-   p:sqlGetNumberError => SQL returns the latest error number, if the query has failed
-   p:sqlEscape => SQL Sanitize data which will be injected into SQL query
-   p:sqlNumRows => SQL Get the number of rows in a result

### Configuration storage service

#### Store configuration data

-   p:configuration::set => Configuration::set(string $key, mixed $value, ShopConstraint $shopConstraint = null);

    > This method returns true if the operation is successful, false otherwise.

#### Check if a configuration data set exists

-   p:configuration::has => Configuration::has(string $key, ShopConstraint $shopConstraint = null);

    > This method returns true if the data exists, false otherwise.

#### Update configuration data

-   p:configuration::updateValue => Configuration::updateValue(string $key, mixed $default = null);

    > This method returns the data for $key if it data exists, or NULL otherwise.

#### Retrieve configuration data

-   p:configuration::get => Configuration::get(string $key, mixed $default = null);

    > This method returns the data for $key if it data exists, or NULL otherwise.
    >
    > If the data is stored as multi language, this will return an array of values indexed by language id.

#### Delete configuration

-   p:configuration::remove = > Configuration::remove(string $key);

    > This method returns nothing, and throws an Exception on error.

</details>

<details>
<summary>Snippets Smarty</summary>

-   p:l => {l s='' mod='' d='Shop.Theme.Action'}
-   p:l => {l s='' sprintf=[$var|intval] mod='<module_name>' d='Shop.Theme.Action'}
-   p:dump => {$var|dump}
-   p:vdump => {$var|var_dump}
-   p:printr => {$var|print_r}
-   p:hook => {hook h='<hook_name>' mod='<hook_name>'}
-   p:widget => {widget name='<module_name>' hook='<hook_name>'}
-   p:token => {Tools::getAdminTokenLite('<admin_controller_name>')}
-   p:s.get => {$smarty.get.<get_parammetr>}
    > display value of page from URL ($\_GET) http://www.example.com/index.php?page=foo
-   p:s.post => {$smarty.post.<post_parammetr>}
    > display the variable "page" from a form ($\_POST['page'])
-   p:s.cookie => {$smarty.cookies.username}
    > display the value of the cookie "username" ($\_COOKIE['username'])
-   p:s.server_name => {$smarty.server.SERVER_NAME}
    > display the server variable "SERVER_NAME" ($\_SERVER['SERVER_NAME'])
-   p:s.path => {$smarty.env.PATH}
    > display the system environment variable "PATH"
-   p:s.session.id => {$smarty.session.id}
    > display the php session variable "id" ($\_SESSION['id'])
-   p:s.request.username => {$smarty.request.username}
    > display the variable "username" from merged get/post/cookies/server/env

### Link to admin controller

-   p:link-admin-controller => {$link->getAdminLink('<admin_controller_name>')}

### Link to page (new-products, specials, my-account etc.)

-   p:link-page-1.6 => {$link->getPageLink()}
-   p:link-page-1.7 => {url entity='my-account' params=['edited' => 1, 'id' => $id]}

### Link to category

-   p:link-category-1.6 => {$link->getCategoryLink()}
-   p:link-category-1.7 => {url entity='category' id=<id_category> id_lang=<id_lang>}

### Link to product

-   p:link-product-1.6 => {$link->getProductLink()}
-   p:link-product-1.7 => {url entity='product' id=<id_product>}

### Link to module

-   p:link-module-1.6 => {$link->getModuleLink('<module_name>','<controller_name>','<array_of_params>')}
-   p:link-module-1.7 => {url entity='module' name='myModule' controller='myController' params = ['paramKey1' => $paramValue1, 'paramKey2' => $paramValue2]}

### Link to image

-   p:link-image-1.6 => {$link->getCatImageLink()}
-   p:link-image-1.7 => {url entity='categoryImage' id=$id_category name='imageType'}

    > imageType

    cart_default (125px x 125px)
    small_default (98px x 98px)
    medium_default (452px x 452px)
    home_default (250px x 250px)
    large_default (800px x 800px)
    category_default (141px x 180px)
    stores_default (170px x 115px)

</details>

<details>
<summary>Snippets SCSS, SASS, LESS, CSS</summary>

Generate media queries for these devices

-   p:media_phone => Generate Media Query Phone

    ```
    @media screen and (max-width: 767px) {

    }
    ```

-   p:media_tablet => Generate Media Query Tablet

    ```
    @media screen and (min-width: 768px) and (max-width: 991px) {

    }
    ```

-   p:media_desktop => Generate Media Query Desktop

    ```
    @media screen and (min-width: 992px) {

    }
    ```

-   p:flex-center => Display Flex Center attributes

    ```
    display: flex;
    justify-content: center;
    align-items: center;
    ```

</details>

<details>
<summary>Snippets Vanila JS, jQuery</summary>

### Vanila JS

-   p:for => For Loop
-   for => For Loop
-   loop => For Loop

    ```
    for (var index = 0; index < array.length; index++) {
        var element = array[index];
    }
    ```

-   p:log => Print to console
-   clg => Print to console
-   log => Print to console

    `console.log();`

### jQuery

-   p:eachBasic => Basic jQuery.each()

    ```
    $('element').each(function(index, value){"
        console.log(this.text());
    "});
    ```

-   p:eachArray => Array jQuery.each()

    ```
    $.each(array, function(index, value){
        console.log(`${index}: ${value}`);
    });
    ```

-   p:eachJSON => JSON jQuery.each()

    ```
    const colors = [
        { 'red': '#f00' },
        { 'green': '#0f0' },
        { 'blue': '#00f' }
    ];

    $.each(colors, function() {
        $.each(this, function(name, value) {
            console.log(`${name} = ${value}`);
        });
    });
    ```

-   p:eachCLASS => CLASS jQuery.each()

    ```
    $.each($('.link'), function(index, value) {
        console.log(index + ':' + $(value).text());
    });
    ```

-   p:ajaxFrontController => jQuery Ajax Call Your Front Controller
-   p:ajaxAdminController => jQuery Ajax Call Your Admin Controller

</details>

<!-- ## Features
Describe specific features of your extension including screenshots of your extension in action. Image paths are relative to this README file.

For example if there is an image subfolder under your extension project workspace:

\!\[feature X\]\(images/feature-x.png\)

> Tip: Many popular extensions utilize animations. This is an excellent way to show off your extension! We recommend short, focused animations that are easy to follow. -->

<!-- ## Requirements
If you have any requirements or dependencies, add a section describing those and how to install and configure them. -->

<!-- ## Extension Settings

Include if your extension adds any VS Code settings through the `contributes.configuration` extension point.

For example:

This extension contributes the following settings:

-  `myExtension.enable`: enable/disable this extension
-  `myExtension.thing`: set to `blah` to do something -->

<!-- ## Known Issues
Calling out known issues can help limit users opening duplicate issues against your extension. -->

<!-- ## Release Notes
Users appreciate release notes as you update your extension.
### 0.0.1
Added snippets php, css, and smarty.
---
### 0.0.2
Added snippets smarty, html.
---

-->

<!-- ## Working with Markdown

**Note:** You can author your README using Visual Studio Code. Here are some useful editor keyboard shortcuts:

-  Split the editor (`Cmd+\` on macOS or `Ctrl+\` on Windows and Linux)
-  Toggle preview (`Shift+CMD+V` on macOS or `Shift+Ctrl+V` on Windows and Linux)
-  Press `Ctrl+Space` (Windows, Linux) or `Cmd+Space` (macOS) to see a list of Markdown snippets -->

## Extension Dependencies

Smarty language pack & PHP Symbols & PHP DocBlocker & HTML $ CSS!

Author : [Roman Matviy](https://roman.matviy.pp.ua)
<br>
Site : [https://matviy.pp.ua](https://matviy.pp.ua)
<br>
Source : [https://marketplace.visualstudio.com/items?itemName=apartner-top.prestashop-snippets](https://marketplace.visualstudio.com/items?itemName=apartner-top.prestashop-snippets)

# Donate

<p>Buy me a coffee :)</p>
<p>QR Code</p>
<p><a href="https://github.com/MatviyRoman/resass/blob/master/img/qr-code.png?raw=true" target="_blank" rel="noopener noreferrer"><img src="https://github.com/MatviyRoman/resass/raw/master/img/qr-code.png?raw=true" alt="donation resass media queries" style="max-width:100%;"></a></p>
<p>Or PayPall</p>
<p><a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=E2H8329XLYRKQ&source=url" rel="nofollow"><img src="https://camo.githubusercontent.com/361950b331ef676b7eec436a4dbe5a7ce47211a6623dcc889b1f5b7b611b27df/68747470733a2f2f7777772e70617970616c6f626a656374732e636f6d2f656e5f55532f692f62746e2f62746e5f646f6e61746543435f4c472e676966" alt="Donate" data-canonical-src="https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif" style="max-width:100%;"></a></p>
<p>Thank You!</p>
<br>

### For more information

-   [https://matviy.pp.ua](https://matviy.pp.ua)
-   [https://roman.matviy.pp.ua](https://roman.matviy.pp.ua)

### Our partners

-   [https://apartner.top](https://apartner.top)
-   [https://programist.top](https://programist.top)
-   [https://tools.apartner.top](https://tools.apartner.top)
-   [https://monitor-test.apartner.top](https://monitor-test.apartner.top)
-   [https://ogo.biz.ua](https://ogo.biz.ua)
-   [https://keytest.pp.ua](https://keytest.pp.ua)

<!-- -  [Visual Studio Code's Markdown Support](http://code.visualstudio.com/docs/languages/markdown)
-  [Markdown Syntax Reference](https://help.github.com/articles/markdown-basics/) -->

## Note

<!-- ### **This is a major work in progress that...*I've just started.* ** -->

If you have a snippet that you use a lot submit a pull-request!

An issue would also be an easy way to suggest a snippet to be added.

Just add the code that you'd want to be turned in to a snippet and I'll see if I can't get it added.

## Known issues

I've not found a way to start a snippet with the leading less than symbol (`<...`). VS Code also seems to use the opening PHP tag to define it's context insead of the selector in the bottom right of the window (or the extension). So far I've not been able to add a snippet that would twig out an entire script yet.

**Enjoy!**
