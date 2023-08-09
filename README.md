# איך לתרום לפרוייקט הזה ולתרגל תרומה לקוד פתוח?

## 1. יש לפתוח אישיו

תבקשו לתקן את האתר ולהוסיף קובץ md עם פרטים עליכם בתוך תיקיית docs/people .
לפני המעבר לשלב הבא יש להמתין עד שהמיינטייר של הפרוייקט יגדיר אתכם assign.

[מדריך באנגלית של גיטהאב לפתיחת issue](https://docs.github.com/en/issues/tracking-your-work-with-issues/creating-an-issue)



## 2. יש לעשות fork לפרוייקט כדי שתוכלו לערוך אותו

[מדריך באנגלית של גיטהאב לפתיחת fork](https://docs.github.com/en/get-started/quickstart/fork-a-repo)


## 3. יש לעשות clone למחשב האישי שלכם.

[מדריך באנגלית של גיטהאב לפתיחת clone מקומי](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository)

## 4. פתחו בראנץ' חדש ובצעו בו את השינויים הרצויים.

[מדריך באנגלית של גיטהאב לפתיחת בראנץ'](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-and-deleting-branches-within-your-repository)


## 5. לאחר ביצוע commit יש לבצע push לריפו האישי שלכם.

הפקודות הנדרשות ל commit ול push הן:
```
git commit -m "your commit message" 
git push --set-upstream origin <branch-name>
```
שימו לב ששם branch זה משהו שיצרתם בסעיף 4

## 6. פתחו pull-request. נא לציין איזה issue אתם מעוניינים לסגור.

[מדריך באנגלית של גיטהאב לפתיחת pull-request](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/working-with-your-remote-repository-on-github-or-github-enterprise/creating-an-issue-or-pull-request-from-github-desktop)


ומה שנשאר זה שהמתחזק של הפרוייקט יאשר את ה pull-request שלכם!
ואז תוכלו לראות את הקובץ שהוספתם בכתובת הזו באינטרנט:
https://melodious-muffin-2be5a1.netlify.app/docs/intro/
כשתפתחו בתפריט את people :)

# Website

This website is built using [Docusaurus 2](https://docusaurus.io/), a modern static website generator.

### Installation

```
$ npm install
```

### Local Development

```
$ npm start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
$ npm run build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

Using SSH:

```
$ USE_SSH=true yarn deploy
```

Not using SSH:

```
$ GIT_USER=<Your GitHub username> yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.
