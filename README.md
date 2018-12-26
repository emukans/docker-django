# Django 2 docker-compose boilerplate

The goal of this repository is to simplify the project creation process and make a common boilerplate for all new projects using Django.

## Getting started
Please follow the instructions to set up the Django project.


### Prerequisites
* Docker version 18 or higher
* Docker compose 1.20 or higher

### Installing
1. Create a `.env` file from the `.env.example` file. And adapt it according to your Django project needs.
    ```bash
    cp .env.example .env
    ```
2. Start docker-compose by running `docker-compose up -d`

3. (Optional) Dump static files.
    ```bash
    docker-compose exec app python manage.py collectstatic --no-input
    ```


## Authors

* **Eduards Mukans** - *Initial work* - [emukans](https://github.com/emukans)


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
