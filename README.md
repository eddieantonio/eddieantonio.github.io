This repository contains my personal website: <https://eddieantonio.ca>.
This is mostly just a repository for my CV.

My blog is maintained separately: <https://github.com/eddieantonio/blog>.

# Maintenance

> OK why do we all engage in this collective fiction that static site generators are fun and easy to use? I've not once been able to update my webpage without descending into the depths of some kind of ruby-based hell and I don't think any of you have either.
>
> — [@clegoues](https://twitter.com/clegoues/status/1573310365269647360)

To develop on a local machine, make sure you have an up-to-date version
of Ruby (use a Ruby version manager like [rvm][] or [frum][]). On my M1
MacBook, I used [frum][], but I had to provide `./configure` options to
get it working properly:

    furm install 3.1.2 --enable-shared

Once you have the right Ruby, you can install GitHub Page's version of
Jekyll (obtained from the `Gemfile`):

    bundle install

Finally, you can build or serve the website locally!

    bundle exec jekyll serve

[frum]: https://github.com/TaKO8Ki/frum
[rvm]: https://rvm.io/
