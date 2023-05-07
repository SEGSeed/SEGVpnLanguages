
# SEGVpnLanguages

Welcome to the SEGVpnLanguages repo, where you can find and contribute to the languages and cultures that [SEGVpn](https://t.me/SEGVpnBot) supports. SEGVpn is a Telegram bot that lets you access blocked websites and services with ease and security. We want to make SEGVpn accessible and friendly to users from different backgrounds and regions, so we need your help to add more languages to our project.

If you are interested in joining our community of translators and cultural experts, please follow these steps:

- Fork this repo and clone it to your local machine.
- Choose a language that you are fluent in. You can check the list of supported languages in the `App_GlobalResources` folder.
- Inside the `App_GlobalResources` folder, create a file named `Language.xx-XX.resx` that contains all the text strings used by SEGVpn in your language, where `xx-XX` is the language code and culture code for your language. For example, if you want to add Chinese (Simplified), create a file named `Language.zh-CN.resx`.
- Translate each string from English to your language, keeping the meaning and tone as close as possible. Do not change any placeholders or variables in the strings, such as `{0}`, `{1}`, etc.
- Test your translation. You can do this by setting the `Culture` property of the `Thread.CurrentThread` object to the name of your language file. For example, if you want to test Chinese (Simplified), run `Thread.CurrentThread.Culture = new CultureInfo("zh-CN");`.
- If everything works well, commit your changes and push them to your forked repo.
- Create a pull request to this repo with a brief description of your translation and any issues or feedback you encountered.
- Wait for our review and approval. We will try to merge your pull request as soon as possible.

Thank you for your contribution and support! We hope you enjoy using SEGVpn in your language!
