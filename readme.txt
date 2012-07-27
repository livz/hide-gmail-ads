/* 
 * Chrome extension to hide Gmail ads using CSS.
 * Itoafa Liviu
 *
 * o Hides text ads from the right side of the message
 * o Expands message to fit the width of the page
 *
 */
 
 
  
1. The css could be tested also by modifying this file:
Windows: 
   %userprofile%\Local Settings\Application Data\Google\Chrome\User Data\Default\User StyleSheets\Custom.css
Ubuntu 9.04 (Backtrack 5 R2):
  ~/.config/chromium/Default/User StyleSheets/gedit Custom.css
  
2. Directory of already installed extensions:
Windows:
   %userprofile%\Local Settings\Application Data\Google\Chrome\User Data\Default\Extensions\
Ubuntu:
   ~/.config/chromium/Default/Extensions/

3. Start Chromium with extensions allowed:
- Create a panel shortcut and add "--enable-extensions" to command line:
/usr/bin/chromium-browser %U --enable-extensions

4. Other extensions:
 - Ad-blocker for Gmail
   https://chrome.google.com/webstore/detail/coibnogmjcpbccgjofoiklnfpbbjbapo

5. References:
  * http://code.google.com/chrome/extensions/getstarted.html
  * http://code.google.com/chrome/extensions/content_scripts.html
  * http://code.google.com/chrome/extensions/faq.html
  * http://code.google.com/chrome/extensions/devguide.html
  * http://thecodingbug.com/blog/2010/3/7/creating-a-to-do-extension-for-chrome-part-1/
  * http://www.iconfinder.com
  * http://jsfiddle.net/
  * http://www.w3.org/TR/2001/CR-css3-selectors-20011113/
 
