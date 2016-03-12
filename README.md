#Random Wiki New Tab
Read a random wiki page to expand your knowledge when you open a new tab

#Install

Download this [add-on xpi file](https://github.com/shinglyu/tabwebby-firefox/blob/master/dist/@tabwebby-0.0.1.xpi?raw=true) and open it in Firefox 

#Contribute

* Clone this repo
* `npm install -g jpm` (May need `sudo`)
* `jpm run -b </path/to/firefox>` to try it out
* `jpm xpi` to build a install file

## Tips for Firefox 43+ 

* If you use Firefox 43 or about, the unsigned xpi file can't be installed by default.
* Open `about:config`
* Set `xpinstall.signature.required` to `false`

#Credit
Thanks to Sören Hentzschel for his [New Tab Override](https://addons.mozilla.org/en-US/firefox/addon/new-tab-override/) source code
