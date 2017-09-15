# OpenAM

## Initial input

- https://github.com/matosf/openam
- https://www.forgerock.com/platform/access-management/
- https://backstage.forgerock.com/docs/openam/13.5/admin-guide/
- https://forum.forgerock.com/2016/05/deploying-openam-instances-docker/



## Running

`docker-compose up`

It downloads OpenAM from `ForgeRock` repositories and runs it in Tomcat web container.

Open questions:

- Where is data persisted? (e.g. configuration) It does not use any DB in default configuration

## Open in browser

`http://localhost:8080/openam`

Credentials:

- User name: amAdmin
- Password: the one you specified during setup
