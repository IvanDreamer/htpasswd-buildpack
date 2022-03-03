# htpasswd buildpack

This buildpack creates a `.htpasswd` file inside the `config` directory when the `nginx` buildpack is used and if a `nginx.conf.erb` is inside the `config` directory present. The data is retrieved from the `HTPASSWD` environment variable.
