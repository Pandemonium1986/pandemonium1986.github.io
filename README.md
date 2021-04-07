# Pandemonium1986 Resume

![Github license](https://img.shields.io/github/license/Pandemonium1986/ansible-role-init.svg?logo=github)
![GitHub deployments](https://img.shields.io/github/deployments/Pandemonium1986/pandemonium1986.github.io/github-pages)

A simple resume of myself base on [modern-resume-theme](https://github.com/sproogen/modern-resume-theme)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

The only prerequisite is to have an [Jekyll](https://jekyllrb.com/docs/installation/) >= 3.9.0

### Installing

Start by cloning the project

```sh
sudo mkdir -p /opt/github/Pandemonium1986/pandemonium1986.github.io
sudo chown $USER:$USER -R /opt/github/Pandemonium1986/pandemonium1986.github.io
git clone https://github.com/Pandemonium1986/pandemonium1986.github.io.git /opt/github/Pandemonium1986/pandemonium1986.github.io
```

Use your local jekyll

```sh
cd /opt/github/Pandemonium1986/pandemonium1986.github.io
bunlde install
bundle exec jekyll serve
```

Or use the jekyll docker image

```sh
cd /opt/github/Pandemonium1986/pandemonium1986.github.io
docker run --rm -p 4000:4000 --volume="$PWD:/srv/jekyll" -it jekyll/jekyll:3 jekyll serve -H 0.0.0.0
```

In both cases access the content by opening a browser on `http://localhost:4000`

## Deployment

The deployment is done automatically by [github-pages](https://github.com/Pandemonium1986/pandemonium1986.github.io/deployments)

## Built With

-   [Jekyll](https://jekyllrb.com/docs/) - Templating

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/Pandemonium1986/pandemonium1986.github.io/tags).

## Authors

-   **Michael Maffait** - _Initial work_ - [Pandemonium1986](https://github.com/Pandemonium1986)

See also the list of [contributors](https://github.com/Pandemonium1986/pandemonium1986.github.io/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/Pandemonium1986/pandemonium1986.github.io/blob/main/LICENSE) file for details
