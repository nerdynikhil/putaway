## How to Contribute

1.  Fork this repo
2.  Create your feature branch (`git checkout -b my-new-feature`)
3.  Commit your changes (`git commit -am 'useful commit message'`)
4.  Push to the branch (`git push origin my-new-feature`)
5.  Start a Pull Request


## Project Structure
- `public` - Contains the Extension files.
- `src` - Contains the Svelte src files.
- `public/build` - Contains JS/CSS files generated by Svelte Compiler

### src
The three root level files are in src, called `NewTab.svelte`, `Popup.svelte` and `Options.svelte`. You can map the components on the screen by going down from the root level files.

## Setting Up for Development
1. **Clone** the repository to your local machine
2. **Enable '_Developer Mode_'** on your Chrome(ium) browser at 'chrome://extensions/'
3. **Select '_Load unpacked_'** button and point it to the `public` folder
4. Experiment