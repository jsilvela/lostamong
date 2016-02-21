# How I migrated my blog from WordPress

1. Run the export function from WP (public, free, option), to get XML file.
2. Run [exitwp](https://github.com/thomasf/exitwp)
3. Install [hugo](https://gohugo.io/)
4. Run hugo import jekyll <exit-wp converted folder> <new folder for hugo>
5. Follow hugo's instructions: get a theme, server content with ```hugo server```

