# Ansible Role: ansible-role-gitlab_pipelines_exporter

An Ansible Role that installs and configures the Prometheus Gitlab CI pipelines exporter by [Maxime Visonneau](https://github.com/mvisonneau/gitlab-ci-pipelines-exporter).

## Requirements

- Prometheus instance

## Dependencies

None

## Supported OS

The role currently supports Debian, Ubuntu, CentOS.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    gitlab_url: https://gitlab.com
    gitlab_token: your-token
    gitlab_projects:
      - test1/example.org
      - test2/example.org
      - test3/example.org

## Example Playbook

    - hosts: gitlab
      roles:
        - serverfriendsorg.gitlab_pipelines_exporter

## License

GNU General Public License v3.0

## Author Information

This role was created in 2020 by [Steven Conrad Bayer](https://steven.serverfriends.org/).
