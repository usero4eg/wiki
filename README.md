Restore Postgresql13 from dump to docker container:
docker exec -it --user postgres postgresql pg_restore -C -d demo /var/lib/postgresql/data/demo.dump

Install vim themes: bash -c "$(wget -qO- https://git.io/vQgMr)"
