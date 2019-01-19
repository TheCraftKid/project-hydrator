# Project Hydrator
*A tool that stores project backups and provides a means of easily fetching them.*

For more information, see the [docs](https://williecubed.github.io/silver-pancake).

## About
The Project Hydrator is a command line tool that manages personal projects
and provides a platform-agnostic way to backup, fetch, and manage them.

Projects are "dehydrated" when they are stored remotely, like on GitHub or
elsewhere, and they are "rehydrated" when they are fetched from a remote source
for use on a local machine.


### History
Because I have more personal projects I'd like to admit that are increasingly
taking up storage space on my computer and are increasingly unorganized, I
thought I should make yet another project that would clean up this mess and
simultaneously allow me to abstract the process of "officially" creating a new
project, whether it was a web app, a Python experiment, or something else
entirely.

Long story short, I have a lot of projects. Managing them is hard. I made
another project to put an end to my misery.

As for the command line tool's name, `pancake` was already [taken](https://www.npmjs.com/package/pancake) on NPM.
`spancake` - the contraction of the project's codename `silver-pancake` - was
naturally the next best choice.

### Future Features
For the 1.0.0 release of this tool, I aim to have these features complete:
- CLI for fetching/cloning projects from a remote source

- Web console to view all projects and their source codes
- Easy method of showcasing UI-based projects

## Usage
### Installation

#### Node.js
Using NPM:
```bash
npm i -g spancake
```

Using Yarn:
```bash
yarn add spancake
```

### Command Line

TODO

First, authenticate with your GitHub account:
```bash
spancake auth
```

(GitLab and other version control system support to be implemented later)

Now fetch your project. By default, this fetches the repository with the given
project name.

```bash
spancake hydrate <project-name>
```

## Development

TODO

### Testing

TODO