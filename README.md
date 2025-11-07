# Legacy Application Containerization

Containerization of legacy PHP applications with Docker, reducing deployment time by 80% and improving scalability.

## Features

- **PHP 7.4**: Legacy PHP application support
- **Apache**: Web server configuration
- **MySQL**: Database containerization
- **Nginx**: Reverse proxy and load balancing
- **Health Checks**: Container health monitoring

## Quick Start

### Build and run

```bash
docker-compose up -d
```

### Access application

- Application: http://localhost:8080
- Nginx: http://localhost:80

## Migration Steps

1. **Analyze**: Identify dependencies and requirements
2. **Containerize**: Create Dockerfile and docker-compose.yml
3. **Test**: Test in development environment
4. **Deploy**: Deploy to production

## Configuration

Edit `docker-compose.yml` to configure:
- Database credentials
- Port mappings
- Volume mounts
- Environment variables

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

MIT License

## Author

**Dmytro Bazeliuk**
- Portfolio: https://devsecops.cv
- GitHub: [@dmytrobazeliuk-devops](https://github.com/dmytrobazeliuk-devops)
