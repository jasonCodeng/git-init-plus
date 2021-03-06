# git-init-plus

:construction: __Under construction! Not ready for public use.__ :construction:

git-init-plus.js (or g+) is a JavaScript CLI for quickly bootstrapping a Git project.

It runs git init under the hood, but not only that.
It will also create a remote repository on Github or BitBucket right from the command line.
Ginit generates a .gitignore file  created from templates from [gitignore.io](https://www.gitignore.io/) based on the users needs.
Finally, it performs an initial commit and pushes to the master branch.

## Installation

Install using
```bash
npm install -g git-init-plus
```

## Usage

Run using
```bash
g+
```


## Future
1. [ ] BitBucket support
2. [ ] Gitignore.io templates
3. [ ] Refractor code
4. [ ] Better validation to prompts
5. [ ] Two Step Validation for Github

## Contributing

Feel free to submit pull requests.

## License

This project is licensed under the MIT License - see the
[LICENSE.md](https://github.com/jasonCodeng/git-init-plus/blob/master/LICENSE.md) file for details

## Acknowledgments

* [NodeJS](https://nodejs.org/)
