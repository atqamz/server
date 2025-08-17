# Simple Local Web Server

A Docker-based web server setup that hosts a PHP application.

## Quick Start

### Prerequisites
- Docker
- Docker Compose

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd server
   ```

2. Start the services:
   ```bash
   docker-compose up -d
   ```

3. Access the application:
   - Main PHP app: http://localhost

### Development

The `www` directory is mounted as a volume, so changes to PHP files are reflected immediately.

## Configuration

### Environment Variables
You can modify the `docker-compose.yml` to add environment variables:
- `PHP_IDE_CONFIG`: Set for debugging support

### PHP Configuration
Custom PHP settings can be added to `php/php.ini`.

### Nginx Configuration
Modify `nginx/default.conf` to adjust web server behavior.
