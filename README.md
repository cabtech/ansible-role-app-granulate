----
# ansible-role-app-granulate
Installs Granulate as a direct binary
# Required variables
| Name | Type | Comment |
| ---- | ---- | ------- |
| granulate_api_key | string | From Granulate site |
| granulate_svc_name | string | Usually the hostname |
# Default variables
| Name | Type | Value | Comment |
| ---- | ---- | ----- | ------- |
| granulate_binary_name | string | granulate ||
| granulate_download_url | URL | https://github.com/Granulate/gprofiler/releases/latest/download ||
| granulate_install_dir | UnixPath | /opt/granulate.io ||
| granulate_log_file | UnixPath | /var/tmp/granulate.log | Use /dev/null for silent running |

# Future Work
Support Docker install
....
