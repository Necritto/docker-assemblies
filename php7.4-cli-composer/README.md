# PHP7.4 with support for installing packages via composer

## To start the build you need:
- Create executable php file in app folder
- Start server with command 
  ```sh
   docker compose up -d
  ```

### Launch
- first time
  ```sh
  docker compose up -d --build
  ```

- subsequent times
  ```sh
  docker compose up -d
  ```

- disabling a container
  ```sh
  docker compose down
  ```

- viewing logs
  ```sh
  docker compose logs -f
  ```
