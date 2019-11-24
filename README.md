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
```
Available categories:  
##### _github_  
### :atom: :basecamp: :basecampy: :bowtie: :electron: :feelsgood: :finnadie: :goberserk: :godmode: :hurtrealbad: :neckbeard: :octocat: :rage1: :rage2: :rage3: :rage4: :shipit: :squirrel: :suspect: :trollface:"

##### _people_
#### 😄😆😊😃☺️😏😍😘😚😳😌😆😁😉😜😝😀😗😙😛😴😟😦😧😮😬😕😯😑
##### _nature_
##### ☀️☔️☁️❄️⛄️⚡️🌀🌁🌊🐱🐶🐭🐹🐰🐺🐸🐯🐨🐻🐷🐽
##### _objects_
##### "🎍💝🎎🎒🎓🎏🎆🎇🎐🎑🎃👻🎅🎄🎁🔔
##### _places_
##### 🏠🏡🏫🏢🏣🏥🏦🏪🏩🏨💒⛪️
##### _symbols_
##### 💲©️®️™️❌❗️‼️⁉️⭕️✖️➕➖➗💮💯✔️☑️🔘🔗➰〰️〽️🔱✅🔲🔳⚫️⚪️🔴🔵🔷🔶🔹🔸🔺🔻  


For more fun 😊 _gitpush_ places random emoji in the comment.  

✔️ Used and tested on Debian Linux only  
☑️ Should work in any linux distribution with bash shell

TO DO list:
- add specific emoji as option value
- emoji random place in comment
- add all emojis with shortcodes
- add options to push to other branches
- tests
