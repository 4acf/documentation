---
docs: DOCS-000
---

To pin NGINX Plus to a specific version (for example, R32):

1. Edit the `/etc/yum.repos.d/nginx-plus-8.repo` file.
1. Update the repository base URL to the desired version: 

   ```shell
   baseurl=https://pkgs.nginx.com/plus/R32/centos/8/$basearch/
   ```

3. Save the changes and exit.