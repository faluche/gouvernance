# Commit convention 
## First Method 

We can use  [gitmoji](https://gitmoji.dev/) and their CLI 

For install CLI:
```
npm i -g gitmoji-cli
```

## Second Method 

We can use scructure such as :
```
<type> (optionnal scope): <description>
[optionnal details]
```

### Few type:
fix --> a commit pathes a bug \
feat --> a commit add a new features \
docs --> a commit add/change the documentation \
style --> a commit change apparence and not structure \
refractor --> a commit change structure for to be consistent

TO AVOID: \
Add ! after the type if it's BREAKING CHANGE  \
(if your changement it's not compatible with the codebase) \


### Optionnal scope
You prevent on wherre you work or on its scope 

### Description
Title or summary of commit (Warning there are 50 chararcteres)

### Optionnal details 
It's to better explain your commit if needed