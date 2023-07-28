
# FeedHive 🐝

NewsLoader / Loader News or Feednews 📰🔄

## What's this? 

It's very simple, it's a loader for news or feednews, with the chance to make comments and put a thumbs up 👍 on a post. I took a version from the internet and found several bugs, but I've resolved many of them in this beta version. However, it's still working partially. Remember, you need to have MongoDB installed and running.

## Instructions 📝

Just run the following commands:

```bash
npm install
npm start
```

That will install the dependencies and start the app. Easy! 🚀

#### Notes 📌

If you encounter any problem during the installation, especially with js-bson, try this:

```
npm install -g node-gyp
```

Or, alternatively, use Yarn. With Yarn, there should be no problem. 🧶

#### Github instructions 🐙
```
git clone https://github.com/mongodb/js-bson.git
cd js-bson
npm install
node-gyp rebuild
```
Also, don't forget to install the following correctly and run up MongoDB:
```
mongoose
bson
node-gyp (globally)
Port: 3000 🚪
```

## Contribs. 🤝

If you want to help me out with the bugs, reach me at falfonso@res-ear.ch - Software Engineer & Developer 🛠️


## MIT License

This project is licensed under the MIT License, which means you are free to use, modify, and distribute it subject to the terms of this license.

#### Permissions

- You are allowed to use this project for commercial or personal purposes.
- You can modify the source code and adapt it to your needs.
- You are permitted to distribute copies of the original or modified project.

#### Limitations

- The project is provided "as is," without any warranty. The copyright holder and contributors will not be liable for any damages or claims related to the use of this software.

#### Conditions

- You must include a copy of the MIT License text in all modified files.
- You must include the copyright notice and disclaimer in all copies and derivative works of the project.

#### Attribution Example

If you decide to use this project in your work or product, you can provide attribution as follows:

"This project uses code from FeedHive, available under the MIT License."

Please note that this is only a general explanation of the MIT License and its terms. For complete and accurate legal information, refer to the LICENSE file in the project repository.
