# Prestashop Snippets README

Prestashop snippets for 1.6 and 1.7 versions.

## Snippets PHP

-  p:getval => Tools::getValue('');
-  p:prefix => Db::getInstance->getPrefix();
-  p:token => Give a admin token Tools::getAdminTokenLite('<admin_controller_name>');
-  p:psquery => Show an instance of DBQuery
-  p:sqlrow => Give a Db::getInstance()->getRow($sql);
-  p:sqlval => Give a Db::getInstance()->getValue($sql);
-  p:class => Create a Prestashop object model sample !
-  p:module => Create a Prestashop Module sample !
-  p:assign => Give a $this->context->smarty->assign(array());
-  p:mail_send => Give a complete Mail::send() call

## Snippets Smarty

-  p:l => {l s='' mod='' d=''}
-  p:l => {l s='' sprintf=[$var|intval] mod='<module_name>' d=''}
-  p:dump => {$var|dump}
-  p:vdump => {$var|var_dump}
-  p:hook => {hook h='<hook_name>' mod='<hook_name>'}
-  p:widget => {widget name='<module_name>' hook='<hook_name>'}
-  p:token => {Tools::getAdminTokenLite('<admin_controller_name>')}

### Link to admin controller

-  p:link-admin-controller => {$link->getAdminLink('<admin_controller_name>')}

### Link to page (new-products, specials, my-account etc.)

-  p:link-page-1.6 => {$link->getPageLink()}
-  p:link-page-1.7 => {url entity='my-account' params=['edited' => 1, 'id' => $id]}

### Link to category

-  p:link-category-1.6 => {$link->getCategoryLink()}
-  p:link-category-1.7 => {url entity='category' id=3 id_lang=2}

### Link to product

-  p:link-product-1.6 => {$link->getProductLink()}
-  p:link-product-1.7 => {url entity='product' id=26}

### Link to module

-  p:link-module-1.6 => {$link->getModuleLink('<module_name>','<controller_name>')}
-  p:link-module-1.7 => {url entity='module' name='myModule' controller='myController' params = ['paramKey1' => $paramValue1, 'paramKey2' => $paramValue2]}

### Link to image

-  p:link-image-1.6 => {$link->getCatImageLink()}
-  p:link-image-1.7 => {url entity='categoryImage' id=$id_category name='imageType'}

> imageType
> <br>

    1. cart_default (125px x 125px)
    2. small_default (98px x 98px)
    3. medium_default (452px x 452px)
    4. home_default (250px x 250px)
    5. large_default (800px x 800px)
    6. category_default (141px x 180px)
    7. stores_default (170px x 115px)

## Snippets CSS,LESS,CSS

-  p:media_phone / p:media_tablet / p:media_desktop => Generate media queries for these devices
-  p:flex-center => Display Flex Center attributes

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

Author : [Roman Matviy](https://roman.programist.top)
<br>
Site : [https://matviy.pp.ua](https://matviy.pp.ua)
<br>
Source : [https://marketplace.visualstudio.com/items?itemName=apartner-top.prestashop-snippets](https://marketplace.visualstudio.com/items?itemName=apartner-top.prestashop-snippets)

### For more information

-  [https://apartner.top](https://apartner.top)
-  [https://programist.top](https://programist.top)
-  [https://ogo.biz.ua](https://ogo.biz.ua)
-  [https://matviy.pp.ua](https://matviy.pp.ua)
-  [https://roman.programist.top](https://roman.programist.top)

<!-- -  [Visual Studio Code's Markdown Support](http://code.visualstudio.com/docs/languages/markdown)
-  [Markdown Syntax Reference](https://help.github.com/articles/markdown-basics/) -->

**Enjoy!**
