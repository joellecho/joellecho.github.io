# Hyunmin Cho's Website | [Hello!](https://hyunmin-jasper-cho.github.io)
### (Based on Martin Saveski's Website)

## How to run locally
1. Install [Jekyll](http://jekyllrb.com/)  
1.1. If you run with ARM based MAC, you need to fetch some dependencies.  
```
brew install rbenv 
rbenv install 2.7.2
rbenv global 2.7.2
```
Afterall, you need to fetch ~/.zshrc or ~/.bashrc
```
echo 'if which rbenv > /dev/null; then eval "$(rbenv init -)"; fi' >> ~/.zshrc
source ~/.zshrc
```
Then, you can install jekyll by following [1]. 

2. clone this repo 
3. `cd` into the repo
4. run `bundle exec jekyll serve`

## How to deploy
1. make jekyll build as `jekyll new .`
2. push to the master branch
3. github will automatically build the website

## External Libraries
- Framework: [Jekyll](http://jekyllrb.com/)
- CSS
  - [Skeleton](getskeleton.com)
  - Tabs: [Skeleton Tabs](https://github.com/nathancahill/skeleton-tabs)
  - Experience: [Timeline](https://codepen.io/NilsWe/pen/FemfK)
  - Icons: [Font Awesome](http://fontawesome.io/)
- JS
  - [Jquery (3.1.1)](https://jquery.com/)
