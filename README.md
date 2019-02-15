# docker-auto-ssl

自动生成相关域名证书并同步到各个服务器，由于安全密钥问题，使用在 Jenkins 中创建凭据，并使用 `jenkinsfile` 中完成生成，结合 Jenkins Pipeline 并行的特性提高证书生成效率。