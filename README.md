# Being.Charity
This is a repo for [being.charity](https://being.charity). Much like [probably.blog](https://probably.blog), this is all made possible thanks to [weblog.lol](https://weblog.lol). Everything should be relatively self explanatory, but see the layout details below if not! Files are all markdown, and they then get interpreted by [weblog.lol](https://weblog.lol).


## Layout

| Folder            | Contents                                                                                                                                       |
|-------------------|------------------------------------------------------------------------------------------------------------------------------------------------|
| .github/workflows | This contains the main.yml file needed to kick off the task of updated the weblog whenever this repo is changed.                               |
| Images            | Hosted images for the charity buttons. In those rare situations, they are hosted here.                                                         |
| Weblog            | This is where all of the files that [weblog.lol](https://weblog.lol) can actually see reside, within subfolders listed below.                  |
| .../Configuration | These configuration files are required for [weblog.lol](https://weblog.lol), and feature the main template and a config file.                  |
| .../Pages         | Any page that isn't a blog post belongs in here, they tend to also require their own template.                                                 |
| .../Files         | Currently, this just contains the CSS base file that all other templates import and piggy-back off of.                                         |
| .../Templates     | Though the main template is housed in `/Configuration`, the secondary templates for non-post pages are hosted within this folder.              |
