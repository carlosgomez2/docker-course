# Assignment: Writing a Compose File

> Goal: Create a compose config for a local Drupal CMS website

- [x] This empty directory is where you should create a docker-compose.yml 
- [x] Use the `drupal` image along with the `postgres` image
- [x] Set the version to 2
- [x] Use `ports` to expose Drupal on 8080
- Be sure to setup POSTGRES_PASSWORD on postgres image
- Walk though Drupal config in browser at http://localhost:8080
- Tip: Drupal assumes DB is localhost, but it will actually be on the compose service name you give it
- Use Docker Hub documentation to figure out the right environment and volume settings
- Extra Credit: Use volumes to store Drupal unique data
