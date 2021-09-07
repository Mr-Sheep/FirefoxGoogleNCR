# Google NoCountryRedirect(NCR) Addon for Firefox

When using Google in behind proxy servers, Google will be redirected to the "local Google" where the proxy server is located by default. This is very user unfriendly.

Quoting from an [2019 post from Google Search Help](https://support.google.com/websearch/thread/5969357/has-google-non-country-specific-function-been-taken-down-https-www-google-com-ncr?hl=en&msgid=5969357): The NCR page (https://www.google.com/ncr) has always been a default search method for multi-lingual/multi-cultured individual as the region specific or personal tailored search results are heavily skewed due to multiple inputs they use.  

In order to enable Google NCR functionality, users first need to access google.com/ncr. However, user's preferences are stored in cookies so it does not function properly with addons like Temporary Containers.

This addon disables Google's personal web search and safe search by default, and the default country code is US.