# Gói ngôn ngữ Tiếng việt dành cho [Flarum](http://flarum.org/)

French language pack to localize the Flarum forum software, its bundled extensions and libraries.

## Thông tin

Gói ngôn ngữ được tương thích với những thành phần mở rộng sau:

- [Flarum](https://github.com/flarum/core)'s Core [0.1.0 Beta 4](https://github.com/flarum/core/releases/tag/v0.1.0-beta.4)
  - Phần mở rộng:
    - [Akismet](https://github.com/flarum/akismet) [0.1.0 Beta 3](https://github.com/flarum/akismet/releases/tag/v0.1.0-beta.3)
    - [Approval](https://github.com/flarum/approval) [0.1.0 Beta 3](https://github.com/flarum/approval/releases/tag/v0.1.0-beta.3)
    - [Facebook Login](https://github.com/flarum/auth-facebook) [0.1.0 Beta 3](https://github.com/flarum/auth-facebook/releases/tag/v0.1.0-beta.3)
    - [Flags](https://github.com/flarum/flags) [0.1.0 Beta 4](https://github.com/flarum/flags/releases/tag/v0.1.0-beta.4)
    - [GitHub Login](https://github.com/flarum/auth-github) [0.1.0 Beta 3](https://github.com/flarum/auth-github/releases/tag/v0.1.0-beta.3)
    - [Likes](https://github.com/flarum/likes) [0.1.0 Beta 3](https://github.com/flarum/likes/releases/tag/v0.1.0-beta.3)
    - [Lock](https://github.com/flarum/lock) [0.1.0 Beta 3](https://github.com/flarum/lock/releases/tag/v0.1.0-beta.3)
    - [Mentions](https://github.com/flarum/mentions) [0.1.0 Beta 4](https://github.com/flarum/mentions/releases/tag/v0.1.0-beta.4)
    - [Pusher](https://github.com/flarum/pusher) [0.1.0 Beta 3](https://github.com/flarum/pusher/releases/tag/v0.1.0-beta.3)
    - [Sticky](https://github.com/flarum/sticky) [0.1.0 Beta 3](https://github.com/flarum/sticky/releases/tag/v0.1.0-beta.3)
    - [Subscriptions](https://github.com/flarum/subscriptions) [0.1.0 Beta 4](https://github.com/flarum/subscriptions/releases/tag/v0.1.0-beta.4)
    - [Suspend](https://github.com/flarum/suspend) [0.1.0 Beta 3](https://github.com/flarum/suspend/releases/tag/v0.1.0-beta.3)
    - [Tags](https://github.com/flarum/tags) [0.1.0 Beta 4](https://github.com/flarum/tags/releases/tag/v0.1.0-beta.4)
    - [Twitter Login](https://github.com/flarum/auth-twitter) [0.1.0 Beta 3](https://github.com/flarum/auth-twitter/releases/tag/v0.1.0-beta.3)
  - Các thư viện:
    - [Laravel](https://github.com/laravel/laravel)'s Validation [5.1.11](https://github.com/laravel/laravel/releases/tag/v5.1.11)
    - [Moment.js](https://github.com/moment/moment) [2.10.6](https://github.com/moment/moment/releases/tag/2.10.6)

Released under the MIT license. Please see the [license terms](https://github.com/maelsoucaze/flarum/blob/master/LICENSE).

## Installation

### Using Composer

Flarum use Composer to manage its dependencies and extensions. The French language pack is available [on Packagist](https://packagist.org/packages/maelsoucaze/french) and can be managed that way. Make sure that [Composer](https://getcomposer.org/) is installed on your machine, then run the following command in the location where Flarum is installed:

```
composer require maelsoucaze/french
```

The same command can be used to update independently the French language pack, without updating anything else. Note that because the French language pack will be added as a Flarum's dependency, it will also be automatically updated when updating Flarum and its dependencies via Composer.

### Manual Installation

1. Download [the latest stable release](https://github.com/maelsoucaze/flarum/releases) (or [the latest development build](https://github.com/maelsoucaze/flarum/archive/master.zip)).
2. Unpack the downloaded archive with [a file archiver](https://en.wikipedia.org/wiki/Comparison_of_file_archivers).
3. Log in to your server via [FTP](https://en.wikipedia.org/wiki/File_Transfer_Protocol), [SSH](https://en.wikipedia.org/wiki/Secure_Shell) or your provider's control panel.
4. Navigate to the *extensions/* directory of your Flarum installation.
5. Create a *maelsoucaze-french/* subdirectory into it.
6. Upload all the content in the unpacked folder to this subdirectory.

## Contributing

Thank you a lot to wish to contribute. I sincerely appreciate your commitment. Using the language pack is already a huge support, but best other ways to contribute are:

- Star on GitHub. Because if you use it and like it, you can at least be a stargazer!
- Follow on GitHub. You will be notified in real time of all changes. No more misses!
- Report [issues](https://github.com/maelsoucaze/flarum/issues) on GitHub. Any feedback is welcome.
- Open pull requests on GitHub to submit fixes and improvements. Be listed as a [contributor](https://github.com/maelsoucaze/flarum/graphs/contributors)!
- Join [the language pack's discussion](https://discuss.flarum.org/d/615-french-language-pack) on the Flarum community.
- Follow me [on Twitter](https://twitter.com/maelsoucaze). Promise, I don't spam pictures of kittens and puppies (too much).
- Let's have a drink if you are near Paris!
