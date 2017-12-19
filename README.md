# Ansible Role Docker

## Role Variables

- `docker_version` - Docker version (default `17.*`)
- `docker_options` - Options passed to the Docker daemon
- `docker_key_url` - Docker APT repository keyserver to use.
- `docker_package_name` - Name of docker package (`docker-ce` or `docker-ee`, defaults to `docker-ce`
)

## Packages
| Package | Description | Status | Apt | Yum | Homebrew |
| ------- | ----------- | ------ | --- | --- | -------- |
| [Vim](www.vim.org/) | Vim Editor | Required | OK | NaN | NaN |
| [Vim](www.vim.org/) | Vim Editor | Recommended | OK | NaN | NaN |
