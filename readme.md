redirect_on_delete
---
redirect_on_delete is a module development concept that will attempt to redirect url-redirects after as a node is deleted. Thus avoiding unnessesary 404 pages.


### Helpful code snips
- (http://stackoverflow.com/questions/5009221/looking-for-a-drupal-module-that-will-redirect-pathauto-urls-when-a-node-is-dele/5013664#5013664)
hook_nodeapi() $op == 'delete' 
path_redirect_save()
*/
