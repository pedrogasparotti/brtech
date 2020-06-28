# hugo.github.io-maker
A template to quickstart the creation and publishing of [GitHub Pages](https://pages.github.com/) using [Hugo](https://gohugo.io/). 
Contributions are welcome!

## Commands

### `make new`                    
Creates a new **Hugo** project.

### `make add theme=[repository-url]`
Includes the informed **Hugo theme** repository as a submodule. Find available themes [here](https://themes.gohugo.io/). 

Make sure you update the `.hugo/config.toml` file with the new theme settings. Most themes include an `exampleSite/config.toml` you can copy to get started.

### `make update`                    
Updates included themes.

### `make run`
Serves website at http://localhost:1313.

### `make build`                    
Builds deployable version of page.

### `make publish`                    
Pushes changes to repository.

## License

2020 [MIT License](LICENSE).
