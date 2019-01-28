# VK Authentication Plugin

This plugin adds support for logging in to a Discourse site via VK.

## Installation

1. Follow the directions at [Install a Plugin](https://meta.discourse.org/t/install-a-plugin/19157) using https://github.com/discourse/discourse-vk-auth as the repository URL.
2. Rebuild the app using `./launcher rebuild app`
3. Create a new application (or use existing one) at https://vk.com/apps?act=manage. (If you are creating a new application, choose "Website" under Platform in the form.)
4. Go to the application settings and note the app ID and Secure key.
5. In your Discourse instance, go to Site Settings, filter by "VK" and enter the app ID and the Secure key.
6. Check the "vk auth enabled" checkbox, and you're done!

## Notes

For issues and requests: https://meta.discourse.org/t/vk-com-login-vkontakte/12987
