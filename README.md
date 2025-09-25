wordpress-action
================
### TODOs
- [ ] Fix proxying issue cause database failed to connect
  - potential fix
    ```bash
    wp config set WP_SITEURL "???" --raw --type=constant
    wp config set WP_HOME "???" --raw --type=constant
    ```

### DevTunnel
- See [dirkarnez/devtunnel-playground](https://github.com/dirkarnez/devtunnel-playground)

### Web UI
- `https://${Tunnel ID}.devtunnels.ms:8080/`

### Notes
- `sudo chmod -R +x . && ./build.sh` in CI/CD .yaml file is good enough for running docker build on GitHub Action
- too busy - use Docker image instead
  - [wordpress - Official Image | Docker Hub](https://hub.docker.com/_/wordpress)

