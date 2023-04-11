#Installing React Native to MAC Ventura
My PC
MacBook Pro
16-inch, 2021
Apple M1 Pro
32 GB
13.3 (22E252)


## Installation
First I just tried to run React Native directly. I had Homebrew and NPM allready installed but I didn't see that there is Ruby version which should be right. So I've got error.

´´´
rbenv install -l
2.7.8
3.0.6
3.1.4
3.2.2
jruby-9.4.2.0
mruby-3.2.0
picoruby-3.0.0
truffleruby-22.3.1
truffleruby+graalvm-22.3.1
´´´
Newest React native needs version

2.7.6

and I can install only the version 2.7.8

So I needed to follow instructions from here https://codecamper.me/blog/122/

but i have M1 so I need ARM64 architecture.

´´´
arch -arm64 bundle install
arch -arm64 bundle exec pod install
sudo xcode-select --switch /Applications/Xcode.app
and then again

´´´
