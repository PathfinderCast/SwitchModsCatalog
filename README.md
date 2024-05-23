# Switch Mods Catalog

Currently this repository does not host any mods directly. It just links to them using submodules.

Submit a repo by opening a github issue.

## Switch Emulator Modders that I link to

- [StevensND](https://github.com/StevensND)
- [Fl4sh](https://github.com/Fl4sh9174)
- [KeatonTheBot](https://github.com/KeatonTheBot)
- [theboy181](https://github.com/theboy181)
- [lasyan3](https://github.com/lasyan3/yuzuMods)

## Other Mirrors
- [https://git.h3cjp.net/H3cJP/yuzu/wiki/Switch-Mods](https://git.h3cjp.net/H3cJP/yuzu/wiki/Switch-Mods)
- [LexouilleTM/yuzu-mods-archive](https://github.com/LexouilleTM/yuzu-mods-archive)

## Cloning a Repository with Submodules

When working with Git repositories that include submodules, follow these steps to clone the main repository along with all its submodules:

1. **Clone the Repository:**
   Use the following command to download the main repository:

`git clone git clone https://github.com/PathfinderCast/SwitchModsCatalog.git`


2. **Navigate to the Cloned Repository:**
Change directories to the newly cloned repository:

`cd SwitchModsCatalog`


3. **Initialize and Update Submodules:**
Run the following command to initialize and update all submodules within the repository:

`git submodule update --init --recursive`

- The `--init` flag initializes any submodules that haven't been initialized yet.
- The `--recursive` flag ensures that nested submodules are also initialized and updated.

4. **Fetch Submodule Contents:**
To fetch the contents of the submodules (i.e., clone the submodule repositories), use:

`git submodule update --recursive --remote`
