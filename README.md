# Awesome Compose Files
A collection of ready-to-use Docker Compose Files for common services (mongodb, postgres, redis, pact-broker, etc).

# How To
1 - Download the file that contains the service of interest;

2 - Edit the file variables to match your necessity;

3 - Run the service with `docker-compose -f service.compose.yml up`;

# Contributing

Just open a Pull Request with your file:
- Put the file in the `/files` folder;
- Name you file with the pattern `service.compose.yml`;
- Use the latest Docker Compose spec (current: 3);
