# gitpush
:trident: linux bash command to quick commit, comment and push directly to the Github.com :octocat: master branch  
- with random emoji in comment 😉

### Usage:
copy *gitpush* file into your project main directory and run after your work (when you want to send changes to Github)
```shell
./gitpush
```
every time when you want to commit, comment and push directly to the master branch.

- or with no emoji 😞 , type:

```shell
./gitpush --no-emoji or ./gitpush -ne
```

if you want select specific emoji category:

```shell
./gitpush --emoji-category=category or ./gitpush -ec=category
categories_list=(
github
people
objects
places
symbols
)
```

For more fun 😊 _gitpush_ places random emoji in the comment.  

Used and tested on Debian Linux only
