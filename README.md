# GHPFS - Github Pages File Server
A File Server made to run on Github Pages using Jekyll.
consider looking in to the Original Project from [Karlheinzniebuhr](https://github.com/Karlheinzniebuhr/ghpages-fileserver) 

## Installation and Usage

### Github Pages

> [!IMPORTANT]
> Github may Complain if you host binaries or large files, when wanting to uploading things like that consider using the [Git Large File Storage](https://git-lfs.github.com/) or compressing the files.

Fork this Repository and enable Github Pages on the forked repository.

Put the files you want to host in the `/resources` directory.

It can then be accessed at `https://<username>.github.io/<repository>/` or you custom Domain.

### Local or on a Server

You can also run this on your local machine or on your own server.

Install the required Packages:

Ubuntu/Debian:
```bash
sudo apt install ruby-full git
```
Fedora:
```bash
sudo dnf install ruby git
```

Clone this repository with the following command:

```bash
git clone https://github.com/Noriskky/GHPFS.git
```

Install the dependencies:

```bash
bundle install
```

Run the server:

```bash
bundle exec jekyll serve
```