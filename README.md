# Optimus Hub Marketplace

The marketplace index for [Optimus Hub](https://github.com/aikogxstudios/optimus-hub-plugin), a plugin marketplace for [Orca ADE](https://www.onorca.dev).

## Use it

1. In Orca: **Settings → Plugins → Manage sources**.
2. Add this repository:

```
https://github.com/aikogxstudios/optimus-hub-marketplace.git
```

3. **Refresh**, then install **Optimus Hub** from the list.

Add the source, not the plugin URL directly: only marketplace installs report **Check for update** when a new tag is published.

## Contents

`orca-marketplace.json` — the index Orca reads. One entry, pointing at a tagged release of the plugin repository.
