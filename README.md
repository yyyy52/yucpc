## How to post
- [Netlify CMSとは](https://lab.sonicmoov.com/web-service/netlify-cms/)
- [Use <!-more--> to split the article.](https://gohugo.io/content-management/summaries/)  
- [Hugoにおける記事要約の仕組み](https://qiita.com/DQNEO/items/4cc651aa1c2d0ced9fae)
- [Markdown記法 サンプル集](https://qiita.com/tbpgr/items/989c6badefff69377da7)
- [Hugo Shortcode](https://gohugo.io/content-management/shortcodes/)
...  


## The Document and Site for contributor
- Git   
    - [Git Cheat Sheet](https://github.github.com/training-kit/downloads/github-git-cheat-sheet.pdf)  
    - [Git Doc](https://git-scm.com/book/en/v2)

- Netlify CMS
   - [NetlifyCMS Docs](https://www.netlifycms.org/docs/)  
   - [NetlifyCMS config.yml](https://www.ravness.com/2019/05/netlifycms/)  
    
- HUGO
   - [Hugo Docs](https://gohugo.io/documentation/)  
   - [Hugo (Japanese)](http://staff.feedtailor.jp/categories/hugo/)
   - [HUGO THEME STAR RANKING](https://hugo-theme-ranking.oika.me/)

- Vector Hugo
   - [vetcor-hugo github](https://github.com/netlify-templates/victor-hugo)
    
- Hugo Universal Theme
   - [hugo-universal-theme](https://themes.gohugo.io/hugo-universal-theme/)
   - [hugo-universal-theme github](https://github.com/devcows/hugo-universal-theme)
   - [hugo-universal-theme(Japanese)](https://harada-kogyo.jp/2017/05/15/hugo-universal-theme-ja/)
    
- Bootstrap
   - [Bootstrap Docs](https://getbootstrap.com/docs/4.4/getting-started/introduction/)
    
- Twitter
   - [Twitter Timeline](https://publish.twitter.com/#)
    
> - Gitbook
>    - [Gitbook Docs](https://docs.gitbook.com/)  


## Directory Structure

```
./site
├── archetypes                   //Template of creating new content files
├── config.toml                  //The config of this site 
├── content                      //Content
│   ├── about  
│   │   └── _index.md            //Part of Q&A in about page
│   ├── blog  
│   ├── contact.md  
│   ├── news  
│   └── other  
│       ├── Document.md  
│       ├── PastMembers.md  
│       └── VirtualContest.md  
├── data                         //Data (Not used yet)
├── i18n                         //internationalization(Only Japanese and English)
├── layouts                      //Site page template
│   ├── 404.html                 //404 page
│   ├── archetypes  
│   ├── _default  
│   │   ├── list.html            //List page template like blog or news page
│   │   └── single.html          //Single page template like the post in blog or news
│   ├── index.html               //Homepage template
│   ├── other                    //Single page template like the post in other
│   │   └── single.html    
│   ├── page  
│   │   └── single.html          //Single page template like contact
│   ├── partials                 //Components that can be used in other templates
│   └── section  
│       └── about.html           //About page is almost written by .html
├── package.json                 //Sorry i don't know
├── package-lock.json            //Sorry
├── static                       //Static content like css and image
│   ├── admin                    //Admin page
│   ├── css 
│   ├── img                      //Stores all image
│   └── js                       //JavaScript
└── theme.toml                   //Sorry
```
>[Document of Directory Structure](https://gohugo.io/getting-started/directory-structure/)  
