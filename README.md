# DockerCron

git clone https://github.com/Team-Resurgent/DockerCron.git

# Edit start.sh/crontab.sh to your liking

cd DockerCron
docker build --tag 'cron' .
docker run --name cron -d cron
