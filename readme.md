# Chrome extension analytics

currently our analytic output looks like...

```
{ 'content_security_policy': Counter({ 'connect-src': 25,
                                       'script-src': 21,
                                       'img-src': 10,
                                       'object-src': 7,
                                       'frame-src': 7,
                                       'default-src': 6,
                                       'style-src': 6,
                                       'font-src': 3,
                                       'sandbox': 2,
                                       'frame-ancestors': 1,
                                       'form-action': 1,
                                       'base-uri': 1}),
  'misc': Counter(),
  'num_apps_evaluated': 28,
  'num_content_scripts': Counter({1: 9, 2: 1, 4: 1, 5: 1}),
  'permissions': Counter({ 'storage': 12,
                           'contextMenus': 9,
                           'tabs': 8,
                           'notifications': 8,
                           'unlimitedStorage': 7,
                           'http://*/*': 6,
                           'https://*/*': 6,
                           'webRequest': 5,
                           'activeTab': 4,
                           '<all_urls>': 4,
                           'webRequestBlocking': 4,
                           'nativeMessaging': 4,
                           'clipboardRead': 3,
                           'clipboardWrite': 3,
                           'webNavigation': 3,
                           'identity': 3,
                           'cookies': 2,
                           'idle': 2,
                           '*://scholar.google.com/': 1,
                           'declarativeWebRequest': 1,
                           'downloads': 1,
                           '*://clients2.google.com/service/update2/crx*': 1,
                           '*://clients2.googleusercontent.com/crx/download/*': 1,
                           'background': 1,
                           '*://*.webex.com/*': 1,
                           '*://*.qa.webex.com/*': 1,
                           '*://*.webex.com.cn/*': 1,
                           'declarativeContent': 1,
                           'file:///*': 1,
                           'file://*/*': 1,
                           'webview': 1,
                           'system.display': 1,
                           'fileSystem': 1,
                           'fileSystem.write': 1,
                           "{'socket': ['tcp-connect:*:*": 1,
                           "tcp-listen:*:*']}": 1,
                           'http://student.mit.edu/catalog/': 1,
                           'chrome://favicon/*': 1,
                           'http://*.google.com/': 1,
                           'http://*.com/': 1,
                           'https://*.reddit.com/*': 1,
                           'history': 1,
                           'https://www.gstatic.com/prettyearth/*': 1,
                           'fileBrowserHandler': 1,
                           'alarms': 1,
                           'gcm': 1}),
  'unsafe': Counter({"'unsafe-inline'": 4, "'unsafe-eval'": 3})}
```
