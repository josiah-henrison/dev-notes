# Files
How to find a file
```
find . -type f -exec grep -l "example_string" {} +
```
# Svelte
- [Start learning SvelteKit](https://kit.svelte.dev/docs/introduction)

# Steps for development

1. Create developer branch

# Git

```
git config user.name "josiah-henrison"
git config user.email "jdeleon.career@gmail.com"
git config --global user.name ""
git config --global user.email ""
# check source history for previous version
git checkout c20a98c -- src/main/java/com/legalmatch/consumer/service/SuspiciousCaseRestTemplateService.java
```

Clean up branches

```
# Remove references for the non existing remote branches
git fetch --prune
# Remove local branches that don't have remote references ("Gone" status)
git branch -lvv | cut -c3- | awk '/: gone]/ {print $1}' | xargs git branch -d
```

# Daily routine

1. 
2. Spend the last 10 minutes of work for planning the next day