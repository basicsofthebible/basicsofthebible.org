---
layout: page
title: Introduction
description: >
  Introduction to Basics of the Bible Study Guide.
hide_description: true
sitemap: false
---

Welcome. This course is designed for the person that wants to learn what it means to become or be a follower of Jesus. Many people that seek this knowledge realize that the Bible is where they must look, but have been hampered in their quest for one reason or another (e.g. intimidated by the size of the Bible, don't know where to begin, tried to read the Bible but couldn't make sense of it, got discouraged, etc.).

This is a self-directed study to assist you in your quest for answers. It is intended to take you rapidly through select books of the Bible to give you a "big picture" overview of what it means to be or become a follower of Jesus, and to become familiarized with the Bible—which is the definitive handbook for those who want to follow Jesus. For maximum benefit, plan on spending about 30 minutes every day for the next few weeks.

The course consists of two parts: the first covers the basics and can be completed in two weeks. The second part "digs deeper" into the Bible and takes an additional five weeks of daily reading. This study lays the basic foundation for understanding the Bible and what it means to be a follower of Jesus.

After completing this course, you will be equipped, empowered and excited to continue your study of the Bible.

# The Non-Sequential Reading Approach

Most people that are new to the Bible approach it like any other book that they read—they start at the beginning and read linearly through to the end. 

However, this often leads to frustration because a linear reading approach does not readily facilitate an understanding of the Bible as you are reading it. This course takes a different approach by taking you through books of the Bible in a non-sequential order. As such, this facilitates a greater understanding of the big picture of the Bible as you are reading it—that is, as you progress through the daily reading schedule, you will understand more and more what the Bible is saying.

# Getting Started

You will need a Bible and a pencil or highlighter.

It is not necessary to buy a study version of the Bible for this course, but you may find it beneficial in the long term to start this course using a study Bible. If English is your native language (fn), choose a modern Bible translation—NIV, NRSV, NASB, ESV and NKJV are all excellent choices—but avoid paraphrase versions for this study. (Paraphrase versions are excellent for getting a different perspective on a word in the original Greek or Hebrew text, but this type of study should be saved for later in your journey.)

(fn) Generally, you'll understand the Bible best in your first language, so feel free to use that translation if it is available in your native tongue. If you are bilingual, use the language with which you are most comfortable

# The Importance of Daily Reading

Carve out time each day to complete the readings.

This course requires about 20-40 minutes of focused, uninterrupted daily reading. Every day before you begin reading, pray to God asking that the Holy Spirit would give you insight and understanding into what you are about to read.

Read the Bible selection as quickly as you can without skimming or speed reading (if you have a study Bible, do not stop to read the commentary notes, or do so only sparingly). If you notice a verse of interest, highlight it or underline it with a pencil, but do not stop to contemplate at this point in time yet (instructions will be given at the end of the course on how to read the Bible contemplatively and how to effectively use study Bibles and other commentaries).

It is important to read every day—missing a day or two will make it more difficult to remember where you left off and will also make it harder for you to develop a "big picture" view of the Bible.

# The Bible at a Glance

The Bible consists of the Hebrew and Greek Scriptures.

The Hebrew Scriptures contain 39 books written by many different authors over a one thousand year period, between approximately 1400-400 BC. Except for a few sections, it is written entirely in Hebrew. A more detailed description of the Hebrew Scriptures is included later in this study, but for the purposes of this introduction, it is sufficient to summarize that the Hebrew Scriptures as a whole tell of a special and unique task that the Creator God gave to the descendants of a man named Abraham—the Israelites. The purpose of this task was that the Israelites were "commissioned" to tell all the other people of the world about the Creator God. The Hebrew Scriptures contain many references of the coming of a Messiah (which is the Hebrew word for savior or rescuer).

The Greek Scriptures contain 27 books, also written by several different authors over a period of approximately 50 years, around 40-90 AD. The Greek Scriptures show how the Creator God entered into history by becoming a human, fulfilling what was written in the Hebrew Scriptures about the coming Messiah (Savior). The Messiah is a descendant of Abraham named Yeshua (Joshua), or as translated in English: Jesus. The Greek word for Messiah is Christos, from which the title Christ is derived. Today, we put the name and title together: Jesus (the) Christ.

# Navigating the Bible: Chapters and Verses

The Bible is numbered so that it is easy to navigate and find a particular passage.

Most of the books are divided into chapters (a few of the smallest books have a single un-numbered chapter), and each chapter in turn is divided into verses. A verse is typically one or two sentences. Even those that are unfamiliar with the Bible have probably heard someone quote or refer to John 3:16. This means the book of John, chapter 3, verse 16. When looking up books in the Bible, refer to the table of contents. In this example, the book of John, or the Gospel of John as it is known by its longer title, is located toward the back of the Bible. Once you locate John, flip through a couple of pages until you reach chapter 3. In most Bibles, the font size of the chapter number is much larger than the rest of the text whereas the verse number is a small superscript number embedded within the text itself. See examples:


    Genesis 1:1	1<sup>1</sup>In the beginning God created the heavens and the earth.


    John 3:16	<sup>16</sup>For God so loved the world that he gave his one and only Son, that whoever believes in him shall not perish but have eternal life.







How you install Hydejack depends on whether you [start a new site](#new-sites), 
or change the theme of [an existing site](#existing-sites).

0. this unordered seed list will be replaced by toc as unordered list
{:toc}

## New sites
For new sites, the best way to get started with Hydejack is via the Starter Kit. 
It comes with a documented config file and example content that gets you started quickly.

If you have a GitHub account, fork the [Hydejack Starter Kit][hsc] repository. 
Otherwise [download the Starter Kit][src] and unzip the contents somewhere on your machine.

If you bought the __PRO Version__ of Hydejack, use the contents of the `starter-kit` folder instead.

You can now jump to [running locally](#running-locally).

[hsc]: https://github.com/hydecorp/hydejack-starter-kit
[src]: https://github.com/hydecorp/hydejack-starter-kit/archive/v9.2.1.zip
[nfy]: https://app.netlify.com/start/deploy?repository=https://github.com/hydecorp/hydejack-starter-kit
[dtn]: https://www.netlify.com/img/deploy/button.svg


## Existing sites
If you have an existing site that you'd like to upgrade to Hydejack you can install the theme via bundler.
Add the following to your `Gemfile`:

~~~ruby
# file: `Gemfile`
gem "jekyll-theme-hydejack"
~~~

Next, in your config file, change the `theme` to Hydejack:

~~~yml
# file: `_config.yml`
theme: jekyll-theme-hydejack
~~~

You can now jump to [running locally](#running-locally).

### PRO Customers
If you bought the __PRO Version__ of Hydejack, copy the `#jekyll-theme-hydejack` folder into the root folder of your site,
and add the following to your `Gemfile` instead:

~~~ruby
# file: `Gemfile`
gem "jekyll-theme-hydejack", path: "./#jekyll-theme-hydejack"
~~~

The folder is prefixed with a `#` to indicate that this folder is different from regular Jekyll content. 
The `#` character was chosen because it is on of the four characters ignored by Jekyll by default (`.`, `_` , `#`, `~`)
{:.note}

Alternatively, if you've been added to the ["PRO Customers" team](https://github.com/orgs/hydecorp/teams/pro-customers) on GitHub, you can add __Hydejack PRO__ as a git dependency instead:

~~~ruby
# file: `Gemfile`
gem "jekyll-theme-hydejack", git: "https://github.com/hydecorp/hydejack-pro", tag: "pro/v9.2.1"
~~~

If you've provided your GitHub username during checkout you should have been automatically added to the team. Otherwise you can request an invite via [mail@hydejack.com](mailto:mail@hydejack.com).
{:.note}

In order for Bundle to fetch the private repository, an __environment variable__ named __`BUNDLE_GITHUB__COM`__ must be set to __`x-access-token:<GH_REPO_PAT>`__, where you replace `<GH_REPO_PAT>` with a GitHub [Personal Access Token](https://github.com/settings/tokens) (PAT) that has the "repo" permission.

After you've secured a way to fetch the `jekyll-theme-hydejack` gem, in your config file, change the `theme` to Hydejack:

~~~yml
# file: `_config.yml`
theme: jekyll-theme-hydejack
~~~

Hydejack comes with a default configuration file that takes care most of the configuration,
but it pays off to check out the [annotated example config file][config] from the Starter Kit to see what's available. See chapter [Config](./config.md){:.heading.flip-title} for more.
{:.note}

You can now jump to [running locally](#running-locally).

### Troubleshooting
If your existing site combines theme files with your content (as did previous versions of Hydejack/PRO),
make sure to delete the following folders:

- `_layouts`
- `_includes` 
- `_sass` 
- `assets`

The `assets` folder most likely includes theme files as well as your personal/content files. 
Make sure to only delete files that belong to the old theme!


## GitHub Pages
As of September 2024, the recommended way of deploying to GitHub Pages is through a custom [GitHub Action][gha], which gives you full control over the build process. 
No extra steps are required when using a GH Action and you can jump to [running locally](#running-locally), or learn more in chapter [Deploy](./deploy.md){:.heading.flip-title}.
That being said, Hydejack maintains backwards compatibility with the legacy pipeline and you can continue to use it.
{:.note}

If you want to build your site using the legacy pipeline, you can build off of the [`gh-pages` branch][gpb] in the Hydejack Starter Kit repo.

[ghp]: https://jekyllrb.com/docs/github-pages/
[gpb]: https://github.com/hydecorp/hydejack-starter-kit/tree/gh-pages
[gha]: https://docs.github.com/en/actions

The main difference to the regular starter kit is the use of `remote_theme` setting in the config file. 

```yml
# file: `_config.yml`
remote_theme: hydecorp/hydejack@v9.2.1
```

This setting only works with the Free Version of Hydejack. 
**PRO Customers** should use the `starter-kit-gh-pages` folder in the downloaded zip file when targeting the GitHub Pages legacy pipeline.
{:.note}

`starter-kit-gh-pages` is only required when deploying to GitHub Pages through the legacy build pipeline.
When using [a custom GitHub Action](./deploy.md#github-actions), the regular `starter-kit` provides a cleaner, less cluttered folder structure.
{:.note}

Make sure the `plugins` list contains `jekyll-include-cache` (create if it doesn't exist):

```yml
# file: `_config.yml`
plugins:
  - jekyll-include-cache
```

To run this configuration locally, make sure the following is part of your `Gemfile`:

```ruby
# file: `Gemfile`
gem "github-pages", group: :jekyll_plugins
```

Note that Hydejack has a reduced feature set when built on GitHub Pages. 
Specifically, using KaTeX math formulas doesn't work when built in this way.
{:.note}


## Running locally
Make sure you've `cd`ed into the directory where `_config.yml` is located.
Before running for the first time, dependencies need to be fetched from [RubyGems](https://rubygems.org/):

~~~bash
$ bundle install
~~~

If you are missing the `bundle` command, you can install Bundler by running `gem install bundler`.
{:.note}

Now you can run Jekyll on your local machine:

~~~bash
$ bundle exec jekyll serve
~~~

and point your browser to <http://localhost:4000> to see Hydejack in action.


Continue with [Config](config.md){:.heading.flip-title}
{:.read-more}

[config]: https://github.com/hydecorp/hydejack-starter-kit/blob/v9/_config.yml
[upgrade]: upgrade.md
