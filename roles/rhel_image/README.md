# rhel_image role

[![License: GPLv3](https://img.shields.io/badge/license-GPLv3-brightgreen.svg)](https://www.gnu.org/licenses/gpl-3.0)

Please see the collection main page for a higher level description.

## Configuration

Below are the role default values from defaults/main.yml:

<pre>
---
# Tasks
rhel_image_do_setup: true
rhel_image_do_build: true
rhel_image_do_cleanup: true
rhel_image_do_uninstall: false

# Setup
rhel_image_update_host: true
rhel_image_create_user: true
rhel_image_builder_user: image-builder

# Blueprint
rhel_image_git_remote_repo: file:///tmp/rhel-image-blueprints.git
rhel_image_git_repo_checkout: master
rhel_image_local_repo_path: /tmp/blueprint-repo

# Build
rhel_image_blueprint: base-image
rhel_image_download_dir: /tmp
rhel_image_build_remove: true

# Image - only define needed options
rhel_image_output_type: qcow2
rhel_image_size_kb:
rhel_image_ostree_ref:
rhel_image_ostree_parent:
rhel_image_ostree_url:
</pre>

## License

GPLv3+
