# True Life Bible-Presbyterian Church Wordpress Theme

Built for Wordpress v4.2.2

## Dev Env

  * LAMP stack
  * Ruby (2.1.X)
  * Foundation, Compass gems

## Quickstart

  * Set up your LAMP stack with [Vagrant (scotchbox)](https://box.scotch.io/)
  * Download the latest [Wordpress installation](https://wordpress.org/) and run it in /public
  * Clone this bare bones theme into your themes folder and start hacking!
  
## CSS Architecture

  * /base
  * /components
  * /layout
  * /pages
  * /themes
  * /utils
  * /vendors <- e.g. Foundation components, Fontawesome etc.
  * main.scss

Run the following command in the theme folder to compile:

```bash
bundle exec compass watch
```

## Upgrading

If you'd like to upgrade to a newer version of Foundation down the road just run:

```bash
bower update
```
