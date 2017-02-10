## PHP Parser - simplify static code analysis and manipulation
[![Docker Pulls](https://img.shields.io/docker/pulls/rvannauker/php-parser.svg)](https://hub.docker.com/r/rvannauker/php-parser/) [![Docker Stars](https://img.shields.io/docker/stars/rvannauker/php-parser.svg)](https://hub.docker.com/r/rvannauker/php-parser/) [![](https://images.microbadger.com/badges/image/rvannauker/php-parser:latest.svg)](https://microbadger.com/images/rvannauker/php-parser:latest) [![GitHub issues](https://img.shields.io/github/issues/RichVRed/docker-php-parser.svg)](https://github.com/RichVRed/docker-php-parser) [![license](https://img.shields.io/github/license/RichVRed/docker-php-parser.svg)](https://tldrlegal.com/license/mit-license)

Docker container to install and run php-parser

### Installation / Usage
1. Install the rvannauker/php-parser container:
```bash
docker pull rvannauker/php-parser
```
2. Run php-parser through the php-parser container:
```bash
sudo docker run --rm --volume $(pwd):/workspace --name="php-parser" "rvannauker/php-parser" {file}
```

### Download the source:
To run, test and develop the PHP-PARSER Dockerfile itself, you must use the source directly:
1. Download the source:
```bash
git clone https://github.com/RichVRed/docker-php-parser.git
```
2. Build the container:
```bash
sudo docker build --force-rm --tag "rvannauker/php-parser" --file php-parser.dockerfile .
```
3. Test running the container:
```bash
 $ docker run rvannauker/php-parser --help
```