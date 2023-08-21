## Docker Commands

### Get docker info

#### General

Command | Description
--- | ---
docker version | provides full description of docker version
docker -v | provides a short description of docker version
docker info | display system wide information
docker info --format '{{.DriverStatus}}' | display 'DriverStatus' fragment from docker information
docker info --format '{{json .DriverStatus}}' | display 'DriverStatus' fragment from docker information in JSON format
