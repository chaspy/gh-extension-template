# gh-extension-template

# TODO after forked

- Rename repository name

```
NEW_NAME="gh-new-name2"
git grep gh-extension-template | cut -d ':' -f1 | sort | uniq | xargs -I{} sed -i '' "s/gh-extension-template/${NEW_NAME}/g" {}
```

- Set repository secret as `TAGPR_GH_SECRET` . It needs `repo` and `workflow` permission.

## Installation

```bash
gh extension install chaspy/gh-extension-template
```

To upgrade,

```
gh extension upgrade chaspy/gh-extension-template
```

## Usage

TODO

## Environment Variables

TODO