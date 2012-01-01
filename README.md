Emporium Plus TOOLKIT v5 `Sublime Text 2` `Snippets`
=====================

A [Sublime Text 2](http://sublimetext.com/2) snippet library for the popular [Miva Merchant](http://mivamerchant.com) module by [Emporium Plus](http://emporiumplus.com).  

Installation
------------

* Download the Snippets via ZIP, SSH, or `git clone`
* Copy all snippets into your `~/Library/Application\ Support/Sublime\ Text 2/Packages/<bundle_subdir>`

Usage
-----

There is a simple convention that applies to all snippets

	tk/<function-name>

As templates are edited without being saved locally, this library is not tied to a specific filetype.  To avoid conflicts with other snippet libraries, a 'tk/' leader is prepended to all snippet rules.

For example, typing:

	tk/attr + TAB

expand this:

	<mvt:item name="toolkit" param="attr|acount|l.all_settings:product:id" />

Hitting `TAB` or `SHIF + TAB` will toggle through the function parameters.  In this case, starting with `account` and concluding on `l.all_settings:product:id`

Contribution
------------

All these snippets have been tested somewhat trivially.  If you find a bug please open an issue or contact me —  [&#109;&#099;&#104;&#097;&#110;&#064;&#109;&#105;&#118;&#097;&#109;&#101;&#114;&#099;&#104;&#097;&#110;&#116;&#046;&#099;&#111;&#109;](&#109;&#099;&#104;&#097;&#110;&#064;&#109;&#105;&#118;&#097;&#109;&#101;&#114;&#099;&#104;&#097;&#110;&#116;&#046;&#099;&#111;&#109;)


###—CHAN!