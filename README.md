# dynamic_dns
Update google domains dns records.

create image by using the command
> docker image build -t dynamic_dns:latest .

deploy yaml
> docker stack deploy dyncont -c dynamic_dns.yaml
