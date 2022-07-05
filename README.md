# IO Cooperative Policies

This repository contains the source for all legal documents and policies published by [IO Cooperative](https://iocoop.org/).


## Deployment

These files are published at https://iocoop.org/policies/ as part of the [django-iocoop](https://github.com/iocoop/django-iocoop/) application. To deploy the latest versions:

1.  Check out the `master` branch of the [django-iocoop](https://github.com/iocoop/django-iocoop/) git repo locally

2.  Pull the latest versions of the policy files into the `policies` submodule within `django-iocoop`:

    ```sh
    cd django-iocoop
    pushd iocoop/static/policies/
    git pull
    popd
    git commit -m "Update to latest policies" iocoop/static/policies/
    git push
    ```

3.  Then deploy `django-iocoop` using the [normal deploy instructions](https://github.com/iocoop/django-iocoop/blob/master/README.md#to-deploy)

